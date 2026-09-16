# The AI Forecast Registry — 更新手順書

このファイルは公開されている。台帳に書くのは著者一人であり（README「Governance」参照）、その一人が実際にどの手順で追記・訂正を行っているかを、読者が検証できる状態に置くためである。本書が読者に求める検証可能性を、著者自身の運用手順にも適用している。

**対象リポジトリ**：`https://github.com/Leading-AI-IO/the-ai-forecast-registry`
**ローカルパス**：環境依存のため各自のクローン先を用いる
**署名鍵**：`3DD95BA9EC194524`（`Satoshi Yamauchi <s3atoshi@gmail.com>`・ed25519）
この鍵IDと公開鍵は GitHub の著者アカウントに登録済みであり、`https://github.com/Leading-AI-IO/the-ai-forecast-registry/commits/main` の各コミットの `Verified` バッジと照合できる。秘密鍵はここに含まれない。
**最終更新**：2026-09-15（v1.0・8行）

（2026年9月16日訂正）

最終更新を「2026-09-15（v1.0・8行）」から「2026-09-16（v1.0・10行）」に改めた。
2026年9月16日に009・010を登録し、あわせて本手順書に事故防止の手順を追記したためである。

**最終更新**：2026-09-16（v1.0・10行）

---

## この手順書が守っているもの

本書が本文で宣言している運用は4つある。**手順はすべてこの4つを実装するために存在する。**

1. **追記専用** ── 行を削除も書き換えもしない。訂正は新しい行として追記する
2. **登録と帰結は別コミット** ── 予測が帰結より前に記録されたことを第三者が検証できるようにする
3. **全コミットに署名** ── 誰が変更したかを後から偽装できない形で証明する
4. **本文と機械可読ファイルは同時更新** ── どちらか一方だけが新しい状態を作らない

手順の途中で迷ったら、その操作が上の4つのどれを守るためのものかに戻ること。

（2026年9月16日追記）

上の4つに加えて、次の1つを守る。
4つの運用はすべて、署名が本人だけのものであることを前提にしているからである。

5. **秘密鍵をリポジトリに入れない** ── 秘密鍵・失効証明書を、リポジトリのフォルダの中に一時的にも置かない

この項目は、2026年9月16日の作業で、秘密鍵のバックアップファイル（`backup-private-key.asc`）がリポジトリのフォルダ内に置かれ、`git add -A` によって登録のコミットに含まれた事故を受けて追加した。
push前に気づいてコミットを取り消したため、外部には出ていない。

---

## 0. 作業前の確認（毎回）

```powershell
cd <リポジトリのクローン先>
git pull
git status
```

`git status` が `nothing to commit, working tree clean` であることを確認する。
別端末やGitHub Web UIで変更していた場合、`git pull` を飛ばすと衝突する。

署名設定の確認（新しい端末で作業する場合のみ）：

```powershell
git config --get user.signingkey
git config --get commit.gpgsign
gpg --list-secret-keys --keyid-format=long
```

3つとも値が出なければ、末尾の「付録A：新しい端末での署名設定」へ。

（2026年9月16日追記）

上の確認に加えて、作業の前に次の5つを毎回確認する。
2026年9月16日の作業で、5つすべてに関わる問題が起きたためである。

**① 正しいフォルダにいるか。**
ダウンロードしたファイルを展開したフォルダなど、同じ名前の別フォルダで作業しない。
`git` のコマンドが `fatal: not a git repository` を返したら、そこはクローン先ではない。

```powershell
git remote -v
```

`https://github.com/Leading-AI-IO/the-ai-forecast-registry.git` が表示されることを確認する。

**② リモートに、手元にない変更がないか。**
`git status` の「up to date」は、最後に取得した時点との比較にすぎない。
GitHub Web UIでのアップロード（`Add files via upload`）など、別の場所での変更は、取得するまで表示されない。

```powershell
git fetch origin
git log --oneline HEAD..origin/main
```

2行目の出力が空であることを確認する。
何か表示された場合は、編集を始める前に `git pull --no-rebase` で取り込む。

**③ pull の方式が merge であるか。**

```powershell
git config --get pull.rebase
```

`false` であることを確認する。
`true` の場合は `git config pull.rebase false` とする。
rebase で取り込むと、登録コミットのハッシュが変わり、行に書き戻したハッシュと一致しなくなる。

**④ 追跡されていないファイルがないか。**
`git status` に「Untracked files」が表示された場合、その一つ一つが何かを確認してから進む。
意図しないファイルがあれば、リポジトリのフォルダの外へ移す。

**⑤ 秘密鍵がフォルダ内にないか。**

```powershell
Get-ChildItem -Recurse -File -Include *.asc,*.rev,*.gpg,*.key,*.pgp
```

何も表示されないことを確認する。
表示された場合は、手順に進まず、そのファイルをリポジトリのフォルダの外へ移す（付録B）。

---

## 1. 行を追加する場合

### 1-1. 一次資料に到達する

**正式名称の3要素が揃わなければ、行を起こしてはならない。**

```
発言者 ／ 予測の対象と内容 ／ 発言日
```

揃わない場合の対応は決まっている。

| 欠けているもの | 対応 |
|---|---|
| 発言者が特定できない | 収載しない |
| 対象と内容を一文にできない | 収載しない |
| 発言日が確定しない | 一次に日付がなければ「一次表示／二次報道の日付」を併記して収載可 |

### 1-2. 記録する内容を揃える

**発言層（必須）**

- [ ] 逐語引用 ── **原文の言語のまま**。要約・言い換えは引用ではない
- [ ] 直前の一文・直後の一文 ── 取得できない場合は「（第1版時点で未取得）」と記す
- [ ] 一次URL
- [ ] 到達証明 ── 取得時のページタイトルまたは冒頭1行＋到達日
- [ ] 出典の階層 ── 一次／二次（二次の場合は理由も）

**形式層（必須・逐語だけを見て判定する）**

- [ ] 期限 ── あり／なし。ありならその日付
- [ ] 対象 ── あり／なし／△
- [ ] 尺度 ── あり／なし／△
- [ ] 決着条件 ── あり／なし／△

**帰結層（登録時は原則すべて空欄）**

- [ ] 期限の到来 ── 到来済／未到来／期限なし
- [ ] 本人の事後評価 ── 到達していなければ空欄
- [ ] 一次資料の記載 ── 到達していなければ空欄

**記録層**

- [ ] 決着前／後
- [ ] 登録コミット ── この時点では空欄。手順1-5で埋める

> **帰結層に「当たった」「外れた」と書かない。** 書けるのは、発言者本人が述べた言葉と、一次資料に記載された事実だけ。

### 1-3. ファイルを編集する

編集対象は4ファイル。**同時に更新する。**

```
data/registry.json                      ← 正本。ここを最初に編集する
data/registry.csv                       ← 正本から生成
docs/jp/the-ai-forecast-registry_JP.md  ← 第4章の一覧表＋各行テーブル
docs/en/the-ai-forecast-registry_EN.md  ← 同上
```

**あわせて更新が必要な箇所**

| ファイル | 箇所 | 内容 |
|---|---|---|
| 両本文 | 第3章の一覧表 | 新しい行を追加し、四要件の○×を記入 |
| 両本文 | 第3章「数えると」 | 3分類の件数を更新 |
| 両本文 | 第4章「第1版の8行」 | 見出しの行数と、決着前後・一次二次の内訳 |
| 両本文 | 第5章 | 本人の事後評価があれば、該当節に追記 |
| 両本文 | 第6章 | 修正に該当する場合、対の表を追加 |
| `README.md` / `README_en.md` | バッジ `Rows-8` | 行数を更新 |
| `README.md` / `README_en.md` | 更新履歴の表 | 版・日付・内容を1行追加 |
| `llms.txt` | 冒頭ブロックと Key Facts | 行数と、追加した行に関する記述 |


（2026年9月16日追記）

**改行コードを保つ。**
`data/registry.csv` の改行コードは CRLF、それ以外のファイル（`registry.json`・両本文・README・`llms.txt`）は LF である。
エディタや生成スクリプトが改行コードを変えると、中身が同じでも既存の全行が「変更」として記録され、追記専用の履歴が読めなくなる。
2026年9月16日の作業では、CSVがLFで出力され、既存9行がすべて変更扱いになった（コミット前に気づいて修正した）。

**編集後、コミットの前に差分を確認する。**

```powershell
git status
git diff --stat
git diff -- data/registry.csv
(Get-Content data\registry.csv).Count
```

- 変更ファイルが、意図したファイルだけであること
- `data/registry.csv` と `data/registry.json` の差分が、追加（`+`）だけであること。削除（`-`）が出たら、改行コードか既存行の書き換えを疑う
- CSVの行数が「ヘッダー1行＋行数」であること

**第4章「第1版の8行」の扱い。**
2026年9月16日の追記では、見出し「第1版の8行」を第1版の記述として残し、その下に日付付きの「第1版以降に追記された行」を設けて、行数と内訳を記した。
以後の追記も、この節の表に行を加え、合計と内訳を更新する。

### 1-4. 登録のコミットを打つ

```powershell
git add -A
git commit -m "Register row 009: <正式名称>"
```

パスフレーズの入力を求められたら入力する。署名は自動で付く（`commit.gpgsign true`）。

（2026年9月16日訂正）

上のコマンドの `git add -A` は使わない。
`git add -A` は、フォルダ内の追跡されていないファイルもすべて追加する。
2026年9月16日の作業では、これによって秘密鍵のバックアップファイルが登録のコミットに含まれた。
以後は、編集したファイルを名前で指定して追加し、コミットの前後で中身を確認する。
この訂正は、手順1-6・2-2・3-2の `git add -A` にも同じく適用する。

```powershell
git add data/registry.json data/registry.csv docs/jp/the-ai-forecast-registry_JP.md docs/en/the-ai-forecast-registry_EN.md README.md README_en.md llms.txt
git status
git diff --cached --stat
git commit -m "Register row 009: <正式名称>"
git show --stat HEAD
```

- `git status` の「Changes to be committed」に、意図したファイルだけが並んでいること
- `git show --stat HEAD` のファイル一覧に、`.asc` などの鍵ファイルや意図しないファイルが**含まれていない**こと

含まれていた場合は、push前であれば手順5「秘密鍵などをコミットしてしまった（push前）」で取り消す。

**複数の行を一度に登録する場合**は、件名を `Register rows 009 and 010` とし、各行の正式名称を本文に置く。
件名が `Register row` で始まるため、付録Cの `--grep="^Register row"` でも抽出できる。

```powershell
git commit -m "Register rows 009 and 010" -m "009: <正式名称>" -m "010: <正式名称>"
```

### 1-5. ハッシュを取得して書き戻す

```powershell
git rev-parse HEAD | Set-Clipboard
git rev-parse HEAD
```

取得したハッシュを、**追加した行の「登録コミット」欄**に書き戻す。

```
data/registry.json                      ← 該当行の commit フィールド
data/registry.csv                       ← 該当行の「登録コミット」列
docs/jp/the-ai-forecast-registry_JP.md  ← 該当行のテーブル
docs/en/the-ai-forecast-registry_EN.md  ← 同上
```

> **既存8行のハッシュ（`313532b884c57be431528c8aab84605739fbdf5b`）は書き換えない。** 新しい行だけが新しいハッシュを持つ。

（2026年9月16日追記）

書き戻しに、PowerShell の `Set-Content` や `Out-File` を使わない。
PowerShell 5 のこれらのコマンドは、文字コードを変えたりBOMを付けたりするため、日本語やCSVが壊れる。
文字コードと改行コードを保てるエディタで、該当欄だけを書き換える。

書き戻した後、差分が該当欄だけであることを確認する。

```powershell
git status
git diff --stat
```

変更ファイルが上の4つだけであり、各ファイルの変更が「書き戻した行数」と一致すること（例：2行を登録した場合、各ファイル2行の追加と2行の削除）。

### 1-6. 書き戻しをコミットして push

```powershell
git add -A
git commit -m "Record registration commit hash for row 009"
git push
git verify-commit HEAD
```

最後のコマンドで `Good signature from "Satoshi Yamauchi <s3atoshi@gmail.com>"` が出れば完了。

（2026年9月16日追記）

push の前に、リモートの変更を改めて確認する。
手順0から時間が経っている場合、その間に別の場所で変更されている可能性がある。

```powershell
git fetch origin
git log --oneline HEAD..origin/main
```

出力が空でなければ、push の前に取り込む。
`--no-rebase` で merge 方式を明示し、`--no-edit` でマージのメッセージ編集画面（Vim）を開かずに完了させる。

```powershell
git pull --no-rebase --no-edit
git log --oneline -5
git verify-commit <登録コミットのハッシュ>
```

- 取り込み後も、登録コミットのハッシュが、行に書き戻した値と同じであること
- `CONFLICT` と表示された場合は、push せずに競合箇所を解消する

`--no-edit` を付けずに Vim が開いた場合は、`Esc` を押し、`:wq` と入力して `Enter` で保存・終了する。

**push が `rejected`（`fetch first`）で拒否された場合**も、同じく `git pull --no-rebase --no-edit` で取り込んでから push し直す。
`git pull --rebase` と `git push --force` は使わない。

push の後、`https://github.com/Leading-AI-IO/the-ai-forecast-registry/commits/main` で、登録と書き戻しの2つのコミットに `Verified` が付いていることを確認する。

---

## 2. 帰結を追記する場合

**登録とは必ず別のコミットで行う。** これが決着前記録の実装そのものである。

### 2-1. 追記できる内容か確認する

追記してよいのは2種類だけ。

- **発言者本人の事後評価** ── 逐語・日付・一次URLの3点が揃っていること
- **一次資料に記載された事実** ── 同上

期限が到来しただけでは、帰結層の「期限の到来」欄を更新する以外に書くことはない。**本人が振り返らなければ、本人の事後評価欄は空欄のまま残す。**

### 2-2. 編集して、帰結のコミットを打つ

```powershell
git add -A
git commit -m "Append outcome for row 007: <正式名称>"
git push
git verify-commit HEAD
```

**メッセージの先頭を `Append outcome for` に固定する。** 登録（`Register row`）と帰結（`Append outcome for`）がコミットメッセージで区別できることが、後から履歴を辿る第三者にとっての手がかりになる。

---

## 3. 訂正する場合

**元の行は消さない。** 訂正は新しい行として追記する。

### 3-1. 訂正行を作る

- 正式名称は元の行と同じにする
- 補足欄に「〇〇（元の行のID）の訂正。誤：××／正：△△」と記す
- 指摘によって判明した場合、**指摘者の名を補足欄に記す**
- 元の行の補足欄に「ID △△△により訂正」と追記する

### 3-2. コミット

```powershell
git add -A
git commit -m "Correct row 00X: <何を訂正したか>"
git push
git verify-commit HEAD
```

---

## 4. 版を上げる場合

行の追加が一定数たまったとき、または節目のとき。

| ファイル | 箇所 |
|---|---|
| `README.md` / `README_en.md` | 更新履歴の表に `v1.1` などの行を追加 |
| `README.md` / `README_en.md` | `Last Updated` バッジの日付 |
| `data/registry.json` | `version` と `snapshot_date` |

GitHub上でリリースを作る場合は、リポジトリの Releases から新規作成し、タグを `v1.1` 形式にする。

```powershell
git tag -s v1.1 -m "v1.1: <内容>"
git push origin v1.1
```

`-s` で署名付きタグになる。

---

## 5. 差し戻し・失敗時の対応

### コミットメッセージを間違えた（push前）

```powershell
git commit --amend -m "正しいメッセージ"
```

**push後は amend しない。** ハッシュが変わり、本文に書き込んだ登録コミットハッシュと不一致になる。

### 内容を間違えた（push前）

```powershell
git reset --soft HEAD~1
```

変更内容は残したままコミットだけ取り消す。修正して打ち直す。

### 内容を間違えた（push後）

**取り消さない。訂正の行を追記する（手順3）。** 追記専用の原則が、ここで効く。

### 署名に失敗する

```powershell
gpg --list-secret-keys --keyid-format=long
git config --get user.signingkey
```

鍵が出ない場合は付録A。鍵はあるが署名できない場合、gpgのパスを確認する。

```powershell
git config --global gpg.program "C:\Program Files\Git\usr\bin\gpg.exe"
```


（2026年9月16日追記）

### 秘密鍵などをコミットしてしまった（push前）

```powershell
git reset --soft HEAD~1
git restore --staged <ファイル名>
git status
```

コミットを取り消し、そのファイルだけをステージから外す。
その後、ファイルをリポジトリのフォルダの外へ移し（付録B）、手順1-4からやり直す。
2026年9月16日の事故は、この手順で解消した。

### 秘密鍵などを push してしまった

**その鍵は漏洩したものとして扱う。**
push した時点で、第三者が取得できた可能性を否定できないからである。

1. 失効証明書（付録B）で、その鍵を失効させる
2. 失効させた公開鍵を GitHub に再登録し、失効を反映する
3. 付録Aの「新しい鍵を作る場合」で新しい鍵を作り、GitHub に登録する
4. 本手順書冒頭の「署名鍵」を新しい鍵IDに改め、その変更と理由を訂正として記す

履歴からファイルを消す操作（履歴の書き換え）は、追記専用の原則と、登録コミットのハッシュを壊す。
鍵の失効を先に行い、履歴の扱いは別に判断する。

### push が拒否された（rejected）

手順1-6の追記に従い、`git pull --no-rebase --no-edit` で取り込んでから push し直す。

---

## 付録A：新しい端末での署名設定

既存の鍵を持ち込む場合（推奨・署名者が一貫する）：

```powershell
# 鍵のある端末で
gpg --export-secret-keys --armor 3DD95BA9EC194524 > private-key.asc
# 新しい端末で（ファイルは物理媒体で運ぶ。メール・クラウド経由は避ける）
gpg --import private-key.asc
git config --global user.signingkey 3DD95BA9EC194524
git config --global user.email "s3atoshi@gmail.com"
git config --global commit.gpgsign true
git config --global gpg.program "C:\Program Files\Git\usr\bin\gpg.exe"
```

（2026年9月16日訂正）

上の `gpg --export-secret-keys ... > private-key.asc` は、コマンドを実行した場所にファイルを書き出す。
リポジトリのフォルダで実行すると、秘密鍵がリポジトリ内に置かれる。
以後は、書き出し先をリポジトリの外（物理媒体）に明示する。

```powershell
# 鍵のある端末で（書き出し先は物理媒体。<ドライブ> は物理媒体のドライブ文字）
gpg --export-secret-keys --armor 3DD95BA9EC194524 > <ドライブ>:\private-key.asc
# 新しい端末で
gpg --import <ドライブ>:\private-key.asc
```

新しい鍵を作る場合：

```powershell
gpg --full-generate-key
# Real name / Email address は必ず入力する（空欄だとキャンセルされる）
# Email は GitHub に登録済みのものにする
gpg --list-secret-keys --keyid-format=long   # sec の行の鍵IDを控える
gpg --armor --export s3atoshi@gmail.com      # 出力全文を GitHub に登録
```

公開鍵の登録先（**ブラウザで開く。PowerShellに打たない**）：

```
https://github.com/settings/gpg/new
```

---

## 付録B：鍵のバックアップ

**この鍵を失うと、同じ署名者として台帳を更新できなくなる。**

```powershell
gpg --export-secret-keys --armor 3DD95BA9EC194524 > backup-private-key.asc
```

（2026年9月16日訂正）

上の `gpg --export-secret-keys ... > backup-private-key.asc` は、コマンドを実行した場所にファイルを書き出す。
2026年9月16日の事故は、このファイルがリポジトリのフォルダ内に置かれていたことで起きた。
以後は、書き出し先を物理媒体に明示し、リポジトリのフォルダでも、デスクトップなどの平文の場所でも書き出さない。

```powershell
gpg --export-secret-keys --armor 3DD95BA9EC194524 > <ドライブ>:\backup-private-key.asc
```

保管先は暗号化された物理媒体。クラウドストレージには置かない。
**秘密鍵の漏洩は、第三者が「あなたとして」台帳に署名できる状態を意味する。**

失効証明書の場所（鍵が漏洩した場合に鍵を無効化するためのもの）：

```
<GnuPGホームディレクトリ>\openpgp-revocs.d\5C29A160024D620F297E0EC33DD95BA9EC194524.rev
```

このファイルも同様に保管する。

---

## 付録C：確認用コマンド集

```powershell
# 全コミットの署名状態（E は「検証鍵がない」であって未署名ではない）
git --no-pager log --pretty=format:"%h %G? %s" --reverse

# 特定コミットの署名検証
git verify-commit <ハッシュ>

# 台帳ファイルに触れたコミットだけを時系列で
git --no-pager log --follow --stat --reverse -- data/registry.json

# 登録コミットと帰結コミットを分けて一覧
git --no-pager log --pretty=format:"%h %ci %s" --grep="^Register row"
git --no-pager log --pretty=format:"%h %ci %s" --grep="^Append outcome"

# 行数の確認（ヘッダー1行を含む）
(Get-Content data\registry.csv).Count
```

（2026年9月16日追記）

```powershell
# リモートにだけある変更の一覧（空であること）
git fetch origin
git --no-pager log --oneline HEAD..origin/main

# 追跡されている鍵ファイルがないか（何も表示されないこと）
git ls-files | Select-String -Pattern "\.(asc|rev|gpg|key|pgp)$"

# .gitignore が効いているか（パターンと行番号が表示されること）
git check-ignore -v backup-private-key.asc

# 直前のコミットに含まれたファイルの一覧
git show --stat HEAD
```

**GitHub上での署名確認**（ローカルの鍵設定に依存しない・最も確実）：

```
https://github.com/Leading-AI-IO/the-ai-forecast-registry/commits/main
```

各コミットに緑の `Verified` バッジが並んでいることを確認する。

---

## 付録D：直近の検証点

| 日付 | 対象 | 必要な作業 |
|---|---|---|
| **2026-12-31** | 007「Global Call for AI Red Lines／2026年末までのAIレッドライン国際合意要求／2025-09-22」 | 期限到来。合意の成否を一次資料で確認し、**帰結のコミット**を打つ |
| 2027-03〜09 | 008「Dario Amodei／6〜12か月以内のエージェント群によるインターネット掌握能力／2026-09」 | 期限到来 |
| 2027-03 | 006「AI Futures Project／2027年3月の超人的コーダー到達／2025-04-03」 | 期限到来。ただし一次未到達のため、先に `ai-2027.com` への到達が必要 |
| （2026年9月16日追記）<br>**2026-09-21〜09-27の週** | 009「Bernie Sanders／米中首脳会談での先端AI開発停止と超知能禁止の条約交渉への期待／2026-09-15」 | 期限到来。首脳会談で条約が交渉・締結されたかを一次資料で確認し、**帰結のコミット**を打つ |
| （2026年9月16日追記）<br>2027-09〜2028-03 | 010「Bill Gates／AIの恩恵の行き先を決める今後12〜18か月の決定／2026-09-15」 | 期限到来 |

**2026年12月31日が最初の検証点である。** その日が過ぎたとき、帰結の行が登録とは別のコミットで追記されるかどうかが、本書が台帳であるか回顧記事であるかを分ける。

（2026年9月16日訂正）

上の段落の「2026年12月31日が最初の検証点である」は、2026年9月16日の時点で事実ではなくなった。
同日に009を登録し、その期限が「next week」、すなわち2026年9月21日から27日の週だからである。

**最初の検証点は、2026年9月21日から27日の週である。**
その週が過ぎたとき、009の帰結が登録とは別のコミットで追記されるかどうかが、最初に問われる。

---

## 付録E：一次到達が残っている項目

第1版時点で「未到達」と記している。到達したら行を起こすか、欄を埋める。

- AI Futures Project「AI 2027」本体（`ai-2027.com`）
- Daniel Kokotajlo本人による中央値更新の一次投稿
- AI Futures Projectによる2025年6月の定量批判への応答
- Gary Marcus「Six (or seven) predictions for AI 2026 from a Generative AI realist」（2026年1月）の完全URL
- Gary MarcusのWIRED寄稿（AIバブルが2025年に崩壊すると予測したもの）
- Yann LeCun・Andrew Ngの対話（2023年3月の公開書簡への反対）の一次記録
- Sam Altmanの当該発言の一次所在
- Metaculus のAI関連の個別の問い（解決基準の文言と解決済みの結果）
- AI Impacts 研究者調査（2016／2022／2023）の一次ページ
- Marcus 004 の期限（2024年8〜9月）に対する本人の事後評価
