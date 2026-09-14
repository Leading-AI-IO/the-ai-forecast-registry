# The AI Forecast Registry ── 予測の名簿

> **"A forecast becomes a record only if it was written down before anyone knew the answer."** <br>
> （予測は、答えを誰も知らないうちに書き留められていたときだけ、記録になる）

---

# 序章: 2023年3月22日、6か月が要求された

2023年3月22日、ひとつの公開書簡が出た。

書いたのは Future of Life Institute（FLI）という、米国に本拠を置く非営利団体である。書簡の題は「Pause Giant AI Experiments」——巨大なAI実験を一時停止せよ。要求は一文に集約されている。

> Therefore, we call on all AI labs to immediately pause for at least 6 months the training of AI systems more powerful than GPT-4.
> （したがって我々は、すべてのAI研究機関に対し、GPT-4より強力なAIシステムの訓練を、少なくとも6か月間、即時に停止することを求める）

GPT-4は、この書簡の8日前に公開されたばかりのAIだった。「訓練」とは、AIに大量の文章を読ませて能力を持たせる工程のことで、この工程を止めれば、より強いAIは生まれない。書簡はそれを6か月間、世界中の開発者に一斉に止めろと言った。

署名したのは3万人を超える。AI研究の第一人者と呼ばれる人物、企業の経営者、著名な著述家が名を連ねた。世界中の新聞が見出しにした。

問いはひとつである。**その6か月は、来たのか。**

本書はこの問いに答えない。答えは、書簡を出したFLI自身が、ちょうど1年後の2024年3月22日に書いている。

> Over the last 12 months developers of the most advanced systems have revealed beyond all doubt that their primary commitment is to speed and their own competitive advantage.
> （この12か月で、最先端のシステムを開発する者たちは、自分たちが第一に忠実であるのは速度と自社の競争優位だということを、疑いの余地なく明らかにした）

要求した側が、1年後に、要求は通らなかったと自分の言葉で書いた。本書が記録するのは、この形である。誰かが何かを予測し、あるいは要求し、時間が経ち、**その本人が後から何と言ったか。** そのあいだに、記録者の判定は一度も入らない。

---

## なぜ、この台帳があるのか

AIについての予測は、毎週のように出る。

「2027年に人間を超える」「2030年までに仕事の半分が消える」「バブルは来年崩れる」「この技術は行き止まりだ」。言った人の肩書は重く、報道は大きく、そして数か月後には誰も覚えていない。次の予測が出るからである。

予測が忘れられること自体は、問題ではない。問題は、**忘れられた予測が、当たったのか外れたのか、あるいはそもそも当たり外れを判定できる形をしていたのかが、どこにも記録されていない**ことである。

たとえば、こういう予測を考えてみる。

- 「AIは今後、人類にとって深刻な危険になる」
- 「2026年末までに、各国政府はAIに関する国際合意に達すべきである」

前者は、いつまで待てば当たりか外れかが分かるのか、書かれていない。後者には期限がある。2026年12月31日が過ぎれば、合意があったかなかったかは、誰にでも確認できる。

この差は、予測の中身の良し悪しではない。**形の差**である。そして、この形の差こそが、後から振り返るときに決定的に効く。期限のない予測は、いつまでも「まだ分からない」と言える。期限のある予測は、いつか必ず答えが出る。

本書は、AIをめぐる予測を、この「形」の観点から記録する台帳である。

## 本書が渡すもの

読者に渡すのは、三つである。

**一つ目は、行である。** 誰が、いつ、何を言ったか。その言葉を、原文のまま、前後の一文とともに、出典のURLを添えて記録する。本書の英語原文は翻訳ではない。翻訳は参考として別に置く。

**二つ目は、形である。** その予測が、期限を持っているか。何についての予測か。どれくらいの規模を言っているか。何が起きたら「当たった」と言えるのか。この四つを、予測の中身とは切り離して記述する。これを本書では「予測の四要件」と呼ぶ。定義は第1章で行う。

**三つ目は、帰結である。** ただし、本書が書く帰結は二種類だけに限る。**予測した本人が、後から自分の予測について何と言ったか。** そして、**一次資料に事実として書かれていることは何か。** 「当たった」「外れた」という記録者の判定は、本書のどこにも書かない。

三つ目の制約が、本書の性質を決めている。

FLIの書簡について、本書は「停止は実現しなかった」と書かない。書くのは、FLI自身が1年後に「彼らの第一の忠誠は速度にあった」と書いた、という事実である。Gary Marcusという研究者が2024年3月に「今年は画期的なGPTは出ない」と予測したことについて、本書は「当たった」と書かない。書くのは、Marcus自身が2025年1月に「昨年3月、私はそれが2024年には来ないと予測した。来なかった」と書いた、という事実である。

判定は、読者がする。本書は判定できる形に並べる。

## 本書の運用について

この台帳には、ほかの本と違う性質がある。**完成しない。** 予測は出続け、期限は次々に到来する。台帳は追記され続ける。

そのために、本書は以下の運用を守る。

**追記専用である。** 一度記録した行は、削除も書き換えもしない。誤りが見つかった場合は、訂正を新しい行として追記し、元の行はそのまま残す。

**予測の登録と、帰結の追記は、別々に記録する。** 本書はGitHubというサービス上で公開されている。GitHubでは、文書への変更が「コミット」という単位で記録され、いつ、何が変わったかが後から誰でも確認できる。予測を登録するコミットと、その帰結を追記するコミットを分けることで、**予測が帰結より前に記録されていたこと**を、第三者が検証できる。

**すべてのコミットに署名を付す。** PGPという方式の電子署名で、その変更を誰が行ったかを、後から偽装できない形で証明する。

**各行に「決着前／後」を記す。** その予測が、本書に登録された時点で、すでに帰結が出ていたか、まだ出ていなかったか。本書の起点は2023年3月であり、第1版の時点で2026年9月である。したがって初期の行の多くは、帰結が出た後に記録されている。**それを隠さない。** 遡って書いた行には「決着後」と記し、本書の公開以降に登録され、帰結を待っている行には「決着前」と記す。

この区別がなければ、本書は「後から振り返って書いた本」と区別がつかない。後から振り返る本は、誰でも書ける。本書の価値は、**帰結が出る前に刻まれた行が、時間とともに増えていくこと**にある。

**台帳に書くのは、著者一人である。** 本書は公開の場に置かれているが、公開されていることと、誰でも書けることは別である。行を起こすのも、帰結を追記するのも、訂正を加えるのも、著者だけが行う。すべてのコミットは著者の署名を持ち、署名のない変更は履歴に残らない。読者ができるのは、台帳を検証すること、誤りを指摘すること、一次資料の所在を知らせることである。読者が知らせた資料を行にするかどうか、いつ行にするかは、著者が一次確認のうえで決める。台帳の規律は、書き手が一人であることによって保たれる。

**機械可読の形でも置く。** 本書の台帳は、本文中の表としてだけでなく、`data/registry.json`（正本）および `data/registry.csv`（派生）として同じリポジトリに置く。本書の兄弟にあたる『The China AI Registry』は、中国当局が公開する生成AIの登録名簿を扱ったが、その名簿は「網羅的だが、機械可読ではない」と評した。本書は、その評価を自分に向ける。読者が自分で数え直せる形で置く。

## 本書が扱う層と、扱わない層

**扱うのは、公開された言明である。** 一次の所在——文書、講演の記録、議会証言、本人の署名記事、本人のソーシャルメディア投稿——を示せるものだけを記録する。第三者の報道が唯一の所在である場合は、二次であることを明記して記録する。

**扱うのは、AIの将来の状態についての言明である。** 能力、危険、普及、規制、経済への影響、開発の速度。いずれかについて、発言時点で未確定の事柄を述べたもの。

**立場で選別しない。** 危険を訴えた予測も、安全を訴えた予測も、「そんな能力はまだ来ない」と訴えた予測も、同じ基準で載せる。片側だけを載せた台帳は、主張になる。本書は主張ではない。

**扱わないのは、2023年3月22日より前の予測である。** これは本書の設計上の選択であり、代償を伴う。それ以前にも重要な予測はあった。しかし起点を置かなければ台帳は始まらず、本書はこの書簡を起点に選んだ。理由は、この書簡が**期限（6か月）を持ち、対象（GPT-4より強力なシステムの訓練）を持ち、規模（すべての研究機関）を持ち、決着条件（停止したか否か）を持つ**、四要件をすべて備えた要求だったからである。そして、要求した本人が1年後に帰結を書いた。台帳の第1行として、これ以上の形はない。

**扱わないのは、期限のない予測の当否である。** 「AIが人類を滅ぼす確率は10〜20%」という種類の言明は記録する。しかし、それが当たったか外れたかは、本書の記録期間中には判定できない。本書はそれを「決着条件を持たない」という形の記述として残し、それ以上は書かない。

## 資料の扱いについて

本書の各行は、次の三点が揃ったものだけを記録する。

1. **逐語の引用。** 原文の言語のまま。要約や言い換えは引用として扱わない
2. **日付。** 年月日。一次資料に日がない場合は、その旨を記し、二次報道の日付を併記する
3. **一次URL。** 到達した時点でのページタイトルまたは冒頭を併記する

署名者数のように時間とともに変わる数値は、**取得した時点の値**として記録し、取得日を添える。同じ対象を後日また記録する場合は、上書きせず新しい行を追加する。

引用の前後一文も、可能な限り記録する。一文だけを切り出すと、意味が変わることがある。

本書の資料は、すべて2026年9月14日までに、著者が直接到達したものである。到達できなかった資料は、そのことを記す。「存在しない」とは書かない。

### 参考文献

- Future of Life Institute, "Pause Giant AI Experiments: An Open Letter," March 22, 2023. https://futureoflife.org/open-letter/pause-giant-ai-experiments/
- Future of Life Institute, "The Pause Letter: One year later," March 22, 2024. https://futureoflife.org/ai/the-pause-letter-one-year-later/
- Future of Life Institute, "FAQs about FLI's Open Letter Calling for a Pause on Giant AI Experiments." https://futureoflife.org/ai/faqs-about-flis-open-letter-calling-for-a-pause-on-giant-ai-experiments/
- Gary Marcus, "AGI isn't coming in 2025, and GPT-5 probably isn't either," January 9, 2025. https://garymarcus.substack.com/p/agi-isnt-coming-in-2025-and-gpt-5
- Leading AI LLC, *The China AI Registry ── 988の名簿*, 2026. https://github.com/Leading-AI-IO/the-china-ai-registry

---

# 第1章: 台帳の読み方 ── 三層と四要件

台帳の一行を読めるようになれば、本書の残りはすべて読める。この章はそのための章である。

一行には、一つの予測が入っている。誰かが、ある日、AIの将来について何かを言った。その言葉と、その言葉の形と、その後に何が起きたか。この三つが、一行の中で別々の場所に置かれている。

---

## 一つの行は、三つの層でできている

**一つ目の層は、発言そのものである。** 誰が、いつ、どこで、何と言ったか。本書はこれを原文の言語のまま、一語も変えずに記録する。前後の一文も添える。言葉は、切り取り方で意味が変わるからである。出典のURLと、そのページに到達した日付も記す。この層には、記録者の言葉は一つも入らない。入っているのは、発言者の言葉と、それがどこにあるかという事実だけである。

**二つ目の層は、発言の形である。** その予測は、いつまでの話なのか。何についての話なのか。どれくらいの規模を言っているのか。何が起きたら「その通りになった」と言えるのか。この四つを、予測の中身が正しいかどうかとは切り離して記述する。ここで使う基準を、本書は「予測の四要件」と呼ぶ。定義は次の節で行う。

**三つ目の層は、帰結である。** 予測に期限があれば、その期限が過ぎたかどうか。そして、**予測した本人が、後になって自分の予測について何と言ったか。** 本人が何も言っていなければ、この層は空欄になる。空欄は空欄のまま残す。記録者が代わりに埋めることはしない。

三つの層を分けて置く理由は一つである。**混ぜると、どこまでが発言者の言葉で、どこからが記録者の解釈か、分からなくなる。** 一つの文の中に「Xは2027年にYが起きると予測したが、これは楽観的すぎた」と書けば、前半は事実で後半は記録者の意見である。読者はそれを分けて読まなければならない。本書は最初から分けて置く。

## 予測の四要件

ここで、本書が予測の「形」を記述するために使う基準を定義する。

> **予測の四要件とは**、山内 怜史（Satoshi Yamauchi）が提唱している、AIをめぐる予測を判定可能な形式を備えているかで分類する基準である。期限・対象・尺度・決着条件の四つの有無を、予測の真偽とは独立に記述する。
>
> **The Four Requisites**, proposed by Satoshi Yamauchi (山内 怜史), is a classification standard for AI forecasts by whether they are structurally judgeable: it records the presence or absence of a deadline, a subject, a magnitude, and a resolution condition, independently of whether the forecast proves true.
>
> 初出：2026年9月、本リポジトリ commit `12143521340336ee761ccb3da336cf3d89e7e1a`

四つの要件を、順に開く。

**期限（Deadline）。** いつまでの話か。「2027年までに」「今年中に」「6か月以内に」。期限がある予測は、その日が来れば答えが出る。期限がない予測は、いつまでも「まだ分からない」と言える。

**対象（Subject）。** 何についての話か。「GPT-4より強力なシステムの訓練」「人間の知能を超えるAI」「生成AIのバブル」。対象がはっきりしている予測は、何を見ればいいかが分かる。「AIは危険だ」の「AI」は、対象としては広すぎて、何を見ればいいかが定まらない。

**尺度（Magnitude）。** どれくらいか。「すべての研究機関」「70%の確率で」「数千億ドル規模の損害」。尺度がある予測は、起きたことがその大きさに達したかを測れる。「大きな影響がある」の「大きな」は、尺度としては測れない。

**決着条件（Resolution）。** 何が起きたら「その通りになった」と言えるか。「訓練が6か月止まったか」「国際合意が成立したか」。決着条件が明確な予測は、第三者が判定できる。決着条件がない予測は、判定に予測者本人の解釈が必要になる。

四つとも備えている予測は、誰が見ても答えが出る。四つとも欠けている予測は、誰も答えを出せない。そのあいだに、さまざまな形がある。

### 四要件は、良し悪しではない

ここで一つ、誤解を避けたい。

**四要件を多く備えている予測が「良い予測」で、少ない予測が「悪い予測」なのではない。** 四要件は、予測の形の記述であって、予測の価値の評価ではない。

期限のない予測にも意味はある。「この方向は行き止まりだ」という研究者の直観は、期限も尺度も持たないが、研究の方向を変えることがある。「AIが人類を滅ぼす確率は10〜20%」という種類の言明は、決着条件を持たないが、人々の注意を向ける。本書はこれらを記録する。ただし、当たったか外れたかを本書の期間中に判定することはできない、という形の事実も、同時に記録する。

四要件が記述しているのは、**その予測が、後から検証に耐える形で置かれたかどうか**である。それは予測者の誠実さとも、予測の質とも、別のことである。

### 実例で読む

三つの言明を、四要件で読んでみる。いずれも本書の台帳に実際に載っている行である。

**一つ目。** 2023年3月22日、Future of Life Institute。

> we call on all AI labs to immediately pause for at least 6 months the training of AI systems more powerful than GPT-4

期限——6か月。対象——GPT-4より強力なAIシステムの訓練。尺度——すべてのAI研究機関。決着条件——訓練が止まったか否か。**四つとも備えている。** 6か月後に、訓練が止まっていたかどうかは、誰にでも確認できる。

**二つ目。** 2025年9月22日、Global Call for AI Red Lines。

> We urge governments to reach an international agreement on red lines for AI — ensuring they are operational, with robust enforcement mechanisms — by the end of 2026.

期限——2026年末。対象——AIに関する国際合意。尺度——実効性のある、強制力を伴うもの。決着条件——合意が成立したか否か。**四つとも備えている。** 本書の第1版が公開される2026年9月の時点で、この期限はまだ来ていない。

**三つ目。** 2024年3月31日、Gary Marcus。

> But will we see a mindblowing GPT this year? I doubt it.

期限——今年（2024年）。対象——GPT（OpenAIの言語モデル）。尺度——「mindblowing（度肝を抜くような）」。決着条件——**明示されていない。** 何が出れば「mindblowing」なのかは、書かれていない。

この三つ目の行は、本書にとって重要である。期限と対象はあるが、尺度が主観的で、決着条件がない。したがって**第三者がこの予測の当否を判定することはできない。** 判定できるのは、Marcus本人だけである。そしてMarcusは、2025年1月9日に自分で判定した。

> Last March I predicted that it wouldn't arrive in 2024. It didn't.

本書は、この本人の判定を帰結の層に記録する。記録者は判定しない。**四要件が足りない予測は、本人の判定を待つ。** これが、本書の帰結層が「本人の事後評価」を中心に置いている理由である。

## 決着前と、決着後

台帳の各行には、もう一つの列がある。**その行が本書に登録された時点で、予測の帰結はすでに出ていたか、まだ出ていなかったか。**

> **決着前記録とは**、山内 怜史（Satoshi Yamauchi）が提唱している、予測を帰結が確定する前に改竄不能な時刻証明とともに登録する原則である。登録と帰結の追記を別の記録単位とし、事後に書かれた記録と構造的に区別する。
>
> **Pre-Resolution Recording**, proposed by Satoshi Yamauchi (山内 怜史), is the principle of registering a forecast with a tamper-evident timestamp before its outcome is settled, keeping the registration and the outcome as separate records so that entries written after the fact are structurally distinguishable.
>
> 初出：2026年9月、本リポジトリ commit `12143521340336ee761ccb3da336cf3d89e7e1a`

なぜこの区別が必要か。

後から振り返って「あの予測は外れた」と書くことは、誰でもできる。答えを知ってから書いた文章に、予測としての価値はない。**価値があるのは、答えが出る前に「この予測はここにある。期限はここだ。答えが出たら追記する」と書き留めた記録である。** その記録は、答えが出た後に、誰が何を言っていたかを証拠として示せる。

本書の第1版は2026年9月に公開される。起点は2023年3月である。したがって、第1版の行の多くは、帰結が出た後に登録されている。FLIの書簡の帰結は、登録より2年以上前に出ている。本書はこれを「決着後」と記す。**隠さない。** 隠せば、本書は後から振り返って書いた本になる。

一方で、Global Call for AI Red Linesの期限は2026年末である。第1版の時点では、まだ来ていない。本書はこれを「決着前」と記す。期限が来て、合意が成立したか否かが確定したとき、本書はその事実を帰結の層に追記する。**その追記は、登録とは別のコミットで行われる。** 登録のコミットの日付が2026年9月であり、帰結のコミットの日付が2027年1月以降であることは、GitHub上で誰でも確認できる。

時間が経つほど、「決着前」の行は増える。本書が公開された後に出た予測は、すべて決着前に登録される。**本書の価値は、この行が積み上がることで生まれる。** 第1版の時点では、決着前の行は8行のうち3行しかない。それは本書が正直に始まったということであって、欠陥ではない。

## 記録者が書かないもの

本書の帰結層には、次のものを書かない。

- 「当たった」「外れた」「概ね正しかった」「楽観的すぎた」といった、記録者による当否の判定
- 「この予測は影響力があった」「この予測は無視された」といった、記録者による重要性の評価
- 「この時点で彼はこう考えていたのだろう」といった、記録者による動機の推測

書くのは、次のものだけである。

- 期限が到来したか否か（日付の比較という事実）
- 発言者本人が後から述べた、自分の予測についての言葉（逐語・日付・出典）
- 一次資料に記載された、その予測の対象に関する事実（逐語・日付・出典）

この制約は、本書を窮屈にする。「明らかに外れているのに、外れたと書けない」という場面は、必ず出てくる。しかし、その制約を一度でも緩めれば、本書は台帳ではなく、記録者の意見書になる。**意見書は、意見が違う読者には読まれない。台帳は、意見が違う読者にも使われる。** 本書は後者を選ぶ。

## 台帳の列

以上をまとめると、台帳の一行は次の列で構成される。

| 層 | 列 | 内容 |
|---|---|---|
| 識別 | ID | 通し番号 |
| 識別 | 行名 | 正式名称。「発言者／予測の対象と内容／発言日」を斜線で連結した形に固定する。本文はID＋正式名称のセットで指す |
| 発言 | 発言者 | 個人名または組織名。所属を併記 |
| 発言 | 発言日 | 年月日。一次資料に日がない場合はその旨と、二次報道の日付を併記 |
| 発言 | 媒体 | 文書／講演／議会証言／インタビュー／本人の投稿 |
| 発言 | 逐語引用 | 原文の言語のまま |
| 発言 | 直前・直後の一文 | 文脈の保全のため |
| 発言 | 参考訳 | 日本語訳。引用ではなく参考 |
| 発言 | 一次URL・到達証明 | URLと、到達時のページタイトルまたは冒頭、到達日 |
| 形式 | 期限 | あり／なし。ありの場合はその日付 |
| 形式 | 対象 | あり／なし。ありの場合は何か |
| 形式 | 尺度 | あり／なし。ありの場合は何か |
| 形式 | 決着条件 | あり／なし。ありの場合は何か |
| 帰結 | 期限の到来 | 到来済／未到来／期限なし |
| 帰結 | 本人の事後評価 | 逐語・日付・出典。ない場合は空欄 |
| 帰結 | 一次資料の記載 | 逐語・日付・出典。ない場合は空欄 |
| 記録 | 決着前／後 | 登録時点で帰結が確定していたか |
| 記録 | 登録コミット | この行を登録したコミットのハッシュ |

**動的に変わる数値**（署名者数、予測市場の現在値など）は、取得日を添えて記録する。後日また取得した場合は、新しい行を追加する。

この表の形は、本書の `data/registry.json` および `data/registry.csv` と一致する。本文の表と機械可読ファイルは、同じコミットで更新される。

### 参考文献

- Future of Life Institute, "Pause Giant AI Experiments: An Open Letter," March 22, 2023. https://futureoflife.org/open-letter/pause-giant-ai-experiments/
- Global Call for AI Red Lines, "Call for red lines to prevent unacceptable AI risks," launched September 2025. https://red-lines.ai/
- Gary Marcus, "When will the GenAI bubble burst?," March 31, 2024. https://garymarcus.substack.com/p/when-will-the-genai-bubble-burst
- Gary Marcus, "AGI isn't coming in 2025, and GPT-5 probably isn't either," January 9, 2025. https://garymarcus.substack.com/p/agi-isnt-coming-in-2025-and-gpt-5

---

# 第2章: 起点 ── 帰結まで揃った最初の行

第1章で、一行の読み方を説明した。この章では、一行を実際に開く。

開くのは、台帳の第1行——2023年3月22日、Future of Life Instituteの公開書簡である。この行を選んだ理由は序章で述べた。四要件をすべて備え、期限が到来し、要求した本人が帰結を書いた。三つの層が、すべて埋まっている。台帳の見本として、これ以上の行はない。

以下、層ごとに開いていく。読者は第4章の台帳を読むとき、どの行もこの形に展開できることを知っておいてほしい。

---

## 発言の層

**発言者**：Future of Life Institute（FLI）。米国マサチューセッツ州に本拠を置く非営利団体。

**発言日**：2023年3月22日。FLI自身が後の文書で「Mar. 22, 2023」と脚注に記している。

**媒体**：公開書簡。ウェブサイト上に掲載され、誰でも署名を追加できる形式で公開された。

**逐語引用**：

> Therefore, we call on all AI labs to immediately pause for at least 6 months the training of AI systems more powerful than GPT-4.

**直前の一文**：

> We agree. That point is now.

この「We agree」が何に同意しているかは、さらにその前の文にある。書簡は、OpenAIという企業が過去に自ら書いた文章——「ある時点で、将来のシステムの訓練を始める前に独立した審査を受けることが重要になるかもしれない」という趣旨の一節——を引用し、それに同意する形で、「その時点は今だ」と述べている。つまり書簡の要求は、要求される側の企業が過去に自分で書いた言葉を、根拠として使っている。

**直後の一文**：

> This pause should be public and verifiable, and include all key actors.

停止は公開され、検証可能で、主要な関係者すべてを含むべきだと続く。さらにその次の文では、迅速に停止が実現しない場合は政府が介入して一時禁止措置を取るべきだと述べている。

**署名者数**：3万人以上。これはFLI自身の表記である。2023年5月の同団体のニュースレターに「over 30,000 other concerned individuals」とあり、2024年3月の1年後の記事にも「more than 30,000 individuals」とある。本書はこの数値を、**取得日2026年9月14日時点のFLI自身の表記**として記録する。第三者の記事には33,708という具体的な数字を挙げるものもあるが、本書はFLIの表記を採る。

**一次URL**：`https://futureoflife.org/open-letter/pause-giant-ai-experiments/`
**到達証明**：ページタイトル「Pause Giant AI Experiments: An Open Letter - Future of Life Institute」。2026年9月14日到達。

### 発言者による対象の限定

書簡の公開後、FLIは「よくある質問」のページを別に設け、要求の範囲を自ら限定している。

> We're calling for a pause on the training of models larger than GPT-4 for 6 months. This does not imply a pause or ban on all AI research and development or the use of systems that have already been placed in the market.
> （我々はGPT-4より大きなモデルの訓練を6か月停止することを求めている。これは、すべてのAI研究開発の停止や禁止、あるいはすでに市場に出ているシステムの使用停止を意味しない）

同じページで、この要求が向けられている相手は「この能力を持つ、ごく少数の主体」だとも述べている。つまり要求の対象は、世界のAI開発全般ではなく、当時GPT-4を超える規模のモデルを訓練できる少数の組織に絞られていた。

本書はこの限定を、発言の層の補足として記録する。**発言者が自分の発言の範囲を後から明確にした場合、それは発言の一部である。** 記録者が対象を勝手に広げたり狭めたりすることはしない。

## 形の層

四要件で読む。

**期限**：あり。「at least 6 months」——少なくとも6か月。書簡の日付から数えれば、2023年9月22日が最短の期限になる。

**対象**：あり。「the training of AI systems more powerful than GPT-4」——GPT-4より強力なAIシステムの訓練。FAQでさらに「GPT-4より大きなモデル」と限定されている。

**尺度**：あり。「all AI labs」——すべてのAI研究機関。FAQで「この能力を持つごく少数の主体」と補足されており、実質的な対象は数社である。

**決着条件**：あり。訓練が停止したか否か。書簡自身が「public and verifiable（公開され、検証可能な）」停止を求めており、検証できることを要求の一部にしている。

**四要件をすべて備えている。** これは本書の台帳の中で、少数の行にしか当てはまらない。

## 帰結の層

**期限の到来**：到来済。2023年9月22日。

**本人の事後評価**：あり。2024年3月22日、FLIは「The Pause Letter: One year later（一時停止書簡：1年後）」と題した記事を公開した。

> Over the last 12 months developers of the most advanced systems have revealed beyond all doubt that their primary commitment is to speed and their own competitive advantage.
> （この12か月で、最先端のシステムを開発する者たちは、自分たちが第一に忠実であるのは速度と自社の競争優位だということを、疑いの余地なく明らかにした）

同じ記事には、次の一文もある。

> Even AI companies that take safety seriously have adopted the approach of aggressively experimenting until their experiments become manifestly dangerous, and only then considering a pause.
> （安全性を真剣に考えているAI企業でさえ、実験が明白に危険になるまで積極的に実験を続け、そのあとで初めて停止を検討するという方法を採っている）

そして記事は、安全と責任は外部から課されなければならない、と結んでいる。

**一次資料の記載**：本書第1版の時点では、FLI自身の記事以外の一次資料を、この行の帰結層に収載していない。訓練が停止したか否かを示す各社の公式記録は、本書が個別に一次到達したうえで、後日追記する。

**決着前／後**：**決着後。** 本書への登録は2026年9月であり、期限到来（2023年9月）と本人の事後評価（2024年3月）はいずれもそれより前である。

**登録コミット**：`313532b884c57be431528c8aab84605739fbdf5b`。

## この行が示していること

ここまでで、記録者は一度も「停止は起きなかった」と書いていない。

書く必要がなかったからである。**要求した本人が、1年後に、自分の言葉で書いた。** 開発者たちの第一の忠誠は速度にあった、と。本書はその一文を置いた。読者はそれを読んで、停止が起きたかどうかを自分で判断できる。

もし本書が「停止は実現しなかった」と書けば、それは記録者の判定になる。FLIの一文と本書の判定は、内容としては同じことを指しているかもしれない。しかし、**一方は発言者の言葉であり、他方は記録者の言葉である。** 台帳は前者だけを載せる。この区別が崩れると、読者は行のどこまでが事実で、どこからが本書の意見か、分けて読まなければならなくなる。

この行が示しているのは、四要件をすべて備えた予測（この場合は要求）が、どのように決着するかの一つの型である。期限が来る。本人が振り返る。その振り返りが、そのまま帰結の記録になる。**記録者の出番はない。**

## 反対側は、別の行になる

この書簡には、公開直後から反対する声があった。AI研究者のYann LeCunとAndrew Ngは、6か月の停止は悪い考えだという趣旨の対話を公開した。OpenAIのCEOであるSam Altmanは、書簡には停止が必要な場所についての技術的な細部が欠けている、という趣旨の発言をしたと報じられた。

これらは、書簡への反応であると同時に、それ自体がAIの将来についての言明である。「停止すべきでない」という主張の裏には、「停止しなくても危険は生じない」あるいは「停止しても効果はない」という予測が含まれている。

本書はこれらを、**この行の注釈としてではなく、独立した行として**記録する。ただし第1版の時点では、これらの発言の一次資料（対話の録画、本人の投稿）に本書が直接到達していないため、収載していない。第三者の報道だけを根拠に行を起こすことは、本書の基準に照らして行わない。一次に到達した時点で、それぞれの行を追記する。

台帳が片側だけを載せているように見える時期があるとすれば、それは記録者の立場によるものではなく、一次到達の順序によるものである。本書はその順序も隠さない。

## 一行のかたち

以上を、第4章の台帳に載る形にまとめる。

| 列 | 内容 |
|---|---|
| ID | 001 |
| 行名 | Future of Life Institute／GPT-4超の訓練の6か月停止要求／2023-03-22 |
| 発言者 | Future of Life Institute |
| 発言日 | 2023-03-22 |
| 媒体 | 公開書簡 |
| 逐語引用 | Therefore, we call on all AI labs to immediately pause for at least 6 months the training of AI systems more powerful than GPT-4. |
| 直前の一文 | We agree. That point is now. |
| 直後の一文 | This pause should be public and verifiable, and include all key actors. |
| 一次URL | https://futureoflife.org/open-letter/pause-giant-ai-experiments/ |
| 到達証明 | Pause Giant AI Experiments: An Open Letter - Future of Life Institute（2026-09-14） |
| 期限 | あり（6か月／2023-09-22） |
| 対象 | あり（GPT-4より強力なAIシステムの訓練） |
| 尺度 | あり（すべてのAI研究機関） |
| 決着条件 | あり（訓練が停止したか否か） |
| 期限の到来 | 到来済 |
| 本人の事後評価 | 2024-03-22 "Over the last 12 months developers of the most advanced systems have revealed beyond all doubt that their primary commitment is to speed and their own competitive advantage." https://futureoflife.org/ai/the-pause-letter-one-year-later/ |
| 一次資料の記載 | （第1版時点で未収載） |
| 決着前／後 | 決着後 |
| 登録コミット | `313532b884c57be431528c8aab84605739fbdf5b` |
| 補足 | 署名者数：3万人以上（FLI表記・2026-09-14取得）／FAQによる対象の限定あり |

第4章の各行は、この表と同じ列を持つ。ただし本文では紙幅の都合で列を省くことがある。省いた列は `data/registry.csv` で確認できる。

**行番号と行名について。** 各行には通し番号と、行名が付く。第2章で開いたこの行は **001「Future of Life Institute／GPT-4超の訓練の6か月停止要求／2023-03-22」** である。

行名は、本書が付けた通称ではない。**台帳における正式名称であり、次の三つを斜線で連結した形に固定する。**

```
発言者 ／ 予測の対象と内容 ／ 発言日
```

この形を義務づける理由は、**行名だけを切り出して他所に置いても、対象が一意に定まること**にある。台帳の行は、報道に引用され、他の文書から参照され、機械可読ファイルから抜き出される。そのとき「6か月の停止」のような短縮形では、誰の、いつの発言かが失われる。失われた時点で、その行は検証に使えない。

本書は、本文で行を指すとき、**必ず番号と正式名称をセットで書く。** 番号だけでは、読者はその行が何の話だったかを思い出せず、表まで戻らなければならない。正式名称だけでは、機械可読ファイルのどの行を見ればよいかが分からない。両方あって初めて、読者と機械の双方が同じ行に到達できる。

この形式には、もう一つの効果がある。**正式名称を書けない行は、台帳に載せられない。** 発言者が特定できなければ書けない。対象と内容を一文に収められなければ書けない。発言日が確定しなければ書けない。**正式名称を組み立てる作業が、そのまま収載基準の検査になる。** 番号を振る前に、この三つが揃っているかが問われる。

### 本文での表記 ── 二段構成

正式名称は長い。同じ行を何度も指すと、本文が読みにくくなる。そこで本書は、本文での表記を二段に分ける。

| 段 | 形式 | 使う場面 |
|---|---|---|
| 完全表記 | `番号「発言者／予測の対象と内容／発言日」` | 各章での初出時。台帳、機械可読ファイル、外部への引用 |
| 章内表記 | `番号「発言者／予測の対象と内容」` | 同一章内で二度目以降 |

**省略できるのは発言日だけである。** 発言者と、予測の対象と内容は、何度目であっても落とさない。この二つが落ちた瞬間、読者は対象を見失う。

**章が変われば、また完全表記に戻る。** 読者が途中の章から読み始めても、その章の中で一度は完全な形に出会う。

台帳そのもの、`registry.csv`、`registry.json`、そして本書の外へ引用される場合は、**常に完全表記を使う。** 章内表記は本文の便宜であって、行の識別子ではない。

### 複数の行を並べるとき

**二行以上を並べて示す場合は、地の文に連ねず、箇条書きにする。**

正式名称は斜線を含み、それ自体が長い。これを読点で連ねると、どこまでが一行の名称で、どこからが次の行なのかが読み取れなくなる。箇条書きにすれば、行頭が境界を示す。

- 001「Future of Life Institute／GPT-4超の訓練の6か月停止要求／2023-03-22」
- 007「Global Call for AI Red Lines／2026年末までのAIレッドライン国際合意要求／2025-09-22」

この規則は、行が二つのときにも適用する。二つでも、読点で連ねれば斜線が四つ並ぶことになる。

**叙述の中で複数の行に触れる場合も同様である。** 「AをBに修正してCを書き、DをEと判定し」という書き方は、出来事の順序を示しているように見えて、実際には読者に行名の切れ目を探させている。この場合は、日付や順序を見出しにした箇条書きに組み替える。

### 参考文献

- Future of Life Institute, "Pause Giant AI Experiments: An Open Letter," March 22, 2023. https://futureoflife.org/open-letter/pause-giant-ai-experiments/
- Future of Life Institute, "FAQs about FLI's Open Letter Calling for a Pause on Giant AI Experiments." https://futureoflife.org/ai/faqs-about-flis-open-letter-calling-for-a-pause-on-giant-ai-experiments/
- Future of Life Institute, "Future of Life Institute Newsletter: Pause Giant AI Experiments!," May 2023. https://futureoflife.org/newsletter/future-of-life-institute-newsletter-pause-giant-ai-experiments/
- Future of Life Institute, "The Pause Letter: One year later," March 22, 2024. https://futureoflife.org/ai/the-pause-letter-one-year-later/
- Future of Life Institute, "Policymaking In The Pause." https://futureoflife.org/document/policymaking-in-the-pause/

---

# 第3章: 決着できる形と、できない形

第2章で一行を開いた。この章では、第1版の8行すべてを横に並べ、四要件で読む。

先に言っておく。この章で本書は、どの予測が当たったかを書かない。書くのは、**どの予測が、誰の手で決着できる形をしているか**である。それは予測の中身を読む前に、形だけで分かる。

---

## 八行の一覧

| ID | 行名（正式名称） | 期限 | 対象 | 尺度 | 決着条件 | 登録時 |
|---|---|---|---|---|---|---|
| 001 | Future of Life Institute／GPT-4超の訓練の6か月停止要求／2023-03-22 | ○ | ○ | ○ | ○ | 決着後 |
| 002 | Gary Marcus／2024年内の画期的GPT不出現／2024-03-31 | ○ | ○ | △ | × | 決着後 |
| 003 | Gary Marcus／生成AIバブルの崩壊開始時期／2024-03-31 | ○ | ○ | × | × | 決着後 |
| 004 | Gary Marcus／生成AIバブルの崩壊時期の修正／2024-08-03 | ○ | ○ | × | × | 決着後 |
| 005 | Gary Marcus／2025年内のAGI不到来／2025-01-09 | ○ | △ | × | × | 決着後 |
| 006 | AI Futures Project／2027年3月の超人的コーダー到達／2025-04-03 | ○ | ○ | ○ | △ | 決着前 |
| 007 | Global Call for AI Red Lines／2026年末までのAIレッドライン国際合意要求／2025-09-22 | ○ | ○ | ○ | ○ | 決着前 |
| 008 | Dario Amodei／6〜12か月以内のエージェント群によるインターネット掌握能力／2026-09 | ○ | ○ | ○ | △ | 決着前 |

○＝明示されている　△＝あるが判定に解釈を要する　×＝明示されていない

各行の逐語と出典は第4章に置く。この章では形だけを読む。

## 四つ揃った行 ── 二行

次の二行だけが、四要件をすべて明示的に備えている。

- **001「Future of Life Institute／GPT-4超の訓練の6か月停止要求／2023-03-22」**
- **007「Global Call for AI Red Lines／2026年末までのAIレッドライン国際合意要求／2025-09-22」**

前者はすでに第2章で開いた。もう一方、2025年9月に出た007「Global Call for AI Red Lines／2026年末までのAIレッドライン国際合意要求」を見る。

> We urge governments to reach an international agreement on red lines for AI — ensuring they are operational, with robust enforcement mechanisms — by the end of 2026.

期限は2026年末。対象は「AIに関するレッドラインの国際合意」。尺度は「実効性があり、強制力を伴う」。決着条件は、その合意が成立したか否か。2027年1月1日に、この文を書いた人たち以外の誰でも、答えを確認できる。

ここで一つ、形の上で目立つことがある。**四つ揃った二行は、いずれも「予測」ではなく「要求」である。** 「こうなるだろう」ではなく「こうすべきだ」と言っている。要求は、その性質として、何を・いつまでに・誰が・どうすれば達成かを述べなければ要求として成立しない。だから四要件が自然に揃う。

予測は、そうではない。予測は「こうなるだろう」と言えば成立する。いつまでに、どれくらい、何が起きたら当たりか——それを言わなくても、予測は予測として通る。第1版の8行では、**予測として書かれた6行のうち、四要件をすべて明示したものはない。** これは記録者の判定ではない。表の○と×を数えた結果である。

## 期限はあるが、決着条件がない行 ── 四行

次の四行である。

- **002「Gary Marcus／2024年内の画期的GPT不出現／2024-03-31」**
- **003「Gary Marcus／生成AIバブルの崩壊開始時期／2024-03-31」**
- **004「Gary Marcus／生成AIバブルの崩壊時期の修正／2024-08-03」**
- **005「Gary Marcus／2025年内のAGI不到来／2025-01-09」**

四行とも発言者はGary Marcusである。Marcusは認知科学者で、AIの能力について懐疑的な立場から発言を続けてきた人物である。

四行とも期限がある。「今年（2024年）」「来年の今頃（2025年3月頃）」「数日か数週間」「2025年」。対象もある。GPT、生成AIのバブル、AGI。

しかし、決着条件がない。

- 002「Gary Marcus／2024年内の画期的GPT不出現」の **mindblowing**（度肝を抜くような）は、何が出れば該当するのか書かれていない
- 003「Gary Marcus／生成AIバブルの崩壊開始時期」の **the bubble may start to pop**（バブルが弾け始めるかもしれない）も、何をもって「弾け始めた」と言うのか書かれていない。しかもこの文には「2024年末までに誰も真の飛躍を出さなければ」という条件が先に付いており、その条件が満たされたかどうかにも解釈が要る
- 004「Gary Marcus／生成AIバブルの崩壊時期の修正」の **collapse**（崩壊）は、株価か、投資額か、利用者数か、何が何割下がれば崩壊なのかが書かれていない
- 005「Gary Marcus／2025年内のAGI不到来」の **AGI** は、そもそも業界内で定義が一致していない語である

つまりこの四行は、**期限が来ても、第三者が当否を確定できない。** 確定できるのは、「mindblowing」「pop」「collapse」「AGI」が何を指していたかを知っている本人だけである。

そして本人は、実際に確定している。Marcusは三度、自分の予測を自分で処理している。

- 2024年8月 ── 003「Gary Marcus／生成AIバブルの崩壊開始時期」の時期を修正し、004「Gary Marcus／生成AIバブルの崩壊時期の修正」を書いた
- 2025年1月 ── 002「Gary Marcus／2024年内の画期的GPT不出現」を自分で判定した
- 2026年1月 ── 自分の2025年予測17件を自分で採点した記事を書いた

**四要件が足りない予測の帰結層は、本人の言葉で埋まる。** これが第5章の主題になる。

## 期限も対象も尺度もあるが、決着条件に解釈が要る行 ── 二行

次の二行である。

- **006「AI Futures Project／2027年3月の超人的コーダー到達／2025-04-03」**
- **008「Dario Amodei／6〜12か月以内のエージェント群によるインターネット掌握能力／2026-09」**

前者は、元OpenAI研究者のDaniel Kokotajloらが2025年4月に公開した71ページのシナリオ文書「AI 2027」に含まれる予測である。2027年3月に「超人的コーダー（Superhuman Coder）」が登場するという。この語には、文書の付録に定義がある。

> A superhuman coder (SC): an AI system that can do any coding tasks that the best AGI company engineer does.
> （超人的コーダー：最良のAGI企業のエンジニアが行うあらゆるコーディング作業を行えるAIシステム）

定義があるのは、この行の強みである。期限（2027年3月）、対象（コーディング作業を行うAI）、尺度（最良のエンジニアが行う「あらゆる」作業）が揃っている。しかし決着条件には解釈が残る。「最良のAGI企業のエンジニア」が誰で、その人が行う作業の全集合をどう確認するのか。定義は方向を示しているが、判定手続きではない。

後者は、Anthropicの最高経営責任者であるDario Amodeiが2026年9月に書いた文で、形がさらに特徴的である。

> Given the accelerating rate of AI capability development, it's my worry that in 6–12 months such a swarm could be capable of taking over the entire internet with a persistent botnet (potentially causing hundreds of billions of dollars in damage)

期限（6〜12か月）、対象（AIエージェントの群れによるインターネットの掌握）、尺度（数千億ドルの損害）が揃っている。しかし述語は「could be capable of（〜する能力を持ちうる）」である。これは**起きると言っているのではなく、起きる能力を持ちうると言っている。** もし起きれば、この文は確認される。しかし起きなくても、この文は否定されない。「能力はあったが、行使されなかった」と言える。

本書はこれを、決着条件が**片側だけ**にある形、と記述する。当たりは確認できるが、外れは確認できない。この形の予測は、記録期間中に「外れた」と第三者が言うことが、原理的にできない。

これは008「Dario Amodei／6〜12か月以内のエージェント群によるインターネット掌握能力」を批判しているのではない。Amodei自身が文中で「it's my worry that（〜が私の懸念だ）」と書いており、断定ではなく懸念として置いている。本書はその形を、そのまま記述しているだけである。

## 数えると

**第三者が期限到来時に当否を確定できる行 ── 2行**

- 001「Future of Life Institute／GPT-4超の訓練の6か月停止要求」
- 007「Global Call for AI Red Lines／2026年末までのAIレッドライン国際合意要求」

**本人の判定を待つ行 ── 4行**

- 002「Gary Marcus／2024年内の画期的GPT不出現」
- 003「Gary Marcus／生成AIバブルの崩壊開始時期」
- 004「Gary Marcus／生成AIバブルの崩壊時期の修正」
- 005「Gary Marcus／2025年内のAGI不到来」

**定義または述語に解釈が残る行 ── 2行**

- 006「AI Futures Project／2027年3月の超人的コーダー到達」
- 008「Dario Amodei／6〜12か月以内のエージェント群によるインターネット掌握能力」

8行のうち、記録者も読者も「答えが出た」と確認できるのは2行だけであり、その2行はいずれも要求である。**残り6行の帰結は、発言者本人が何を言うかに依存する。**

この分布は、本書が第1版で選んだ8行に固有のものかもしれない。行が増えれば変わるかもしれない。本書はこの表を、行が増えるたびに更新する。数字がどう動くかは、台帳が答える。

## 形が示すこと

この章の表は、予測の良し悪しを示していない。示しているのは、**誰がその予測に答えを出せるか**である。

四要件が揃った言明には、誰でも答えを出せる。だから答えは早く出るし、出た答えは動かない。FLIの書簡は、6か月後に答えが出て、1年後に本人が書いた。

四要件が欠けた言明には、本人しか答えを出せない。答えが出るのは、本人が振り返ったときである。本人が振り返らなければ、答えは出ない。振り返り方によって、答えは動く。生成AIバブルの崩壊時期について、Marcusは5か月のあいだに期限を動かしている。

- 003「Gary Marcus／生成AIバブルの崩壊開始時期」── 2025年3月頃
- 004「Gary Marcus／生成AIバブルの崩壊時期の修正」── 数日か数週間先

**同じ人が、同じ対象について、期限を動かしている。** 本書はその一回ごとを別の行として記録する。それが台帳の仕事である。

## 一次に到達していない行について

006「AI Futures Project／2027年3月の超人的コーダー到達」について、本書は2026年9月14日の時点で、`ai-2027.com` に直接到達できていない。上に引いた定義は、第三者のサイトが同文書の付録から引用したものである。Kokotajlo本人が「中央値は2028年から2029年に後退した」と述べたとされる発言も、共著組織FutureSearchの記事を経由している。

本書の基準では、これは「二次」である。第4章の台帳では、006「AI Futures Project／2027年3月の超人的コーダー到達」の「出典の階層」欄に二次と記し、一次到達の時点で行を追記する。**一次に到達できていない行を、到達したかのように書かない。** 第1版の8行のうち、この1行だけがその状態にある。

### 参考文献

- Future of Life Institute, "Pause Giant AI Experiments: An Open Letter," March 22, 2023. https://futureoflife.org/open-letter/pause-giant-ai-experiments/
- Gary Marcus, "When will the GenAI bubble burst?," March 31, 2024. https://garymarcus.substack.com/p/when-will-the-genai-bubble-burst
- Gary Marcus, "Why the collapse of the Generative AI bubble may be imminent," August 3, 2024. https://garymarcus.substack.com/p/why-the-collapse-of-the-generative
- Gary Marcus, "AGI isn't coming in 2025, and GPT-5 probably isn't either," January 9, 2025. https://garymarcus.substack.com/p/agi-isnt-coming-in-2025-and-gpt-5
- AI Futures Project, "AI 2027," April 3, 2025. https://ai-2027.com/（本書は2026年9月14日時点で直接到達できていない）
- FutureSearch, "AI 2027 Six Months Later: Karpathy, Kokotajlo, and Shifting AGI Timelines." https://futuresearch.ai/blog/ai-2027-6-months-later/
- Global Call for AI Red Lines, launched September 2025. https://red-lines.ai/
- Dario Amodei, "We Must Pace the Frontier," September 2026. https://darioamodei.com/post/we-must-pace-the-frontier

---

# 第4章: 台帳

この章が、本書の本体である。

序章から第3章までは、この章を読むための準備だった。第1章で列の意味を、第2章で一行の開き方を、第3章で形の読み方を示した。ここには、それらを適用した結果だけが並ぶ。

**この章だけが、時間とともに伸びる。** ほかの章は、行が増えたときに参照を更新するにとどまる。この章には、行がそのまま追記される。

---

## 台帳の見方

各行は、第1章で定めた列をすべて持つ。本文では、一行を一つの表として示す。列の順序は `registry.csv` と同じである。

行を指すときは、番号と正式名称をセットで書く。正式名称の形式は「発言者／予測の対象と内容／発言日」である。

**空欄は空欄のまま置く。** 「第1版時点で未取得」「未到達」「未収載」と書かれている欄は、本書がそこに到達できていないことを示す。推測で埋めることはしない。到達した時点で、その欄を埋めた新しい行を追記する。元の行は残す。

**出典の階層が「二次」の行は、一次資料に本書が直接到達していない。** 第1版では1行がこの状態にある。

## 第1版の8行

| ID | 行名（正式名称） | 出典 | 登録時 |
|---|---|---|---|
| 001 | Future of Life Institute／GPT-4超の訓練の6か月停止要求／2023-03-22 | 一次 | 決着後 |
| 002 | Gary Marcus／2024年内の画期的GPT不出現／2024-03-31 | 一次 | 決着後 |
| 003 | Gary Marcus／生成AIバブルの崩壊開始時期／2024-03-31 | 一次 | 決着後 |
| 004 | Gary Marcus／生成AIバブルの崩壊時期の修正／2024-08-03 | 一次 | 決着後 |
| 005 | Gary Marcus／2025年内のAGI不到来／2025-01-09 | 一次 | 決着後 |
| 006 | AI Futures Project／2027年3月の超人的コーダー到達／2025-04-03 | 二次 | 決着前 |
| 007 | Global Call for AI Red Lines／2026年末までのAIレッドライン国際合意要求／2025-09-22 | 一次 | 決着前 |
| 008 | Dario Amodei／6〜12か月以内のエージェント群によるインターネット掌握能力／2026-09 | 一次 | 決着前 |

決着後 5行、決着前 3行。一次 7行、二次 1行。

---

## 各行

### 001「Future of Life Institute／GPT-4超の訓練の6か月停止要求／2023-03-22」

| 列 | 内容 |
|---|---|
| ID | 001 |
| 行名（正式名称） | Future of Life Institute／GPT-4超の訓練の6か月停止要求／2023-03-22 |
| 発言者 | Future of Life Institute（米国・非営利団体） |
| 発言日 | 2023-03-22 |
| 発言日の注記 |  |
| 媒体 | 公開書簡 |
| 逐語引用 | Therefore, we call on all AI labs to immediately pause for at least 6 months the training of AI systems more powerful than GPT-4. |
| 直前の一文 | We agree. That point is now. |
| 直後の一文 | This pause should be public and verifiable, and include all key actors. |
| 参考訳 | したがって我々は、すべてのAI研究機関に対し、GPT-4より強力なAIシステムの訓練を、少なくとも6か月間、即時に停止することを求める。 |
| 一次URL | https://futureoflife.org/open-letter/pause-giant-ai-experiments/ |
| 到達証明 | Pause Giant AI Experiments: An Open Letter - Future of Life Institute（2026-09-14到達） |
| 出典の階層 | 一次 |
| 期限 | あり（6か月／2023-09-22） |
| 対象 | あり（GPT-4より強力なAIシステムの訓練） |
| 尺度 | あり（すべてのAI研究機関） |
| 決着条件 | あり（訓練が停止したか否か） |
| 期限の到来 | 到来済 |
| 本人の事後評価 | 2024-03-22｜Over the last 12 months developers of the most advanced systems have revealed beyond all doubt that their primary commitment is to speed and their own competitive advantage.｜https://futureoflife.org/ai/the-pause-letter-one-year-later/ |
| 一次資料の記載 | （第1版時点で未収載） |
| 決着前／後 | 決着後 |
| 登録コミット | `313532b884c57be431528c8aab84605739fbdf5b` |
| 補足 | 署名者数：3万人以上（FLI表記・2026-09-14取得）／FLIのFAQにより対象を「GPT-4より大きなモデルの訓練」「この能力を持つごく少数の主体」に限定 |

### 002「Gary Marcus／2024年内の画期的GPT不出現／2024-03-31」

| 列 | 内容 |
|---|---|
| ID | 002 |
| 行名（正式名称） | Gary Marcus／2024年内の画期的GPT不出現／2024-03-31 |
| 発言者 | Gary Marcus（認知科学者・ニューヨーク大学名誉教授） |
| 発言日 | 2024-03-31 |
| 発言日の注記 |  |
| 媒体 | 本人のSubstack記事「When will the GenAI bubble burst?」 |
| 逐語引用 | But will we see a mindblowing GPT this year? I doubt it. |
| 直前の一文 | GenAI will, in that case, live for another day, perhaps imploding only later when people realize there is no killer app to justify the increasingly high costs. |
| 直後の一文 | Altman himself has hinted in his recent Lex Fridman interview that nothing quite worthy of the GPT-5 name will drop this year. |
| 参考訳 | しかし、今年、度肝を抜くようなGPTを見ることになるだろうか。私はそうは思わない。 |
| 一次URL | https://garymarcus.substack.com/p/when-will-the-genai-bubble-burst |
| 到達証明 | 記事本文の抜粋一致を検索経由で確認（2026-09-14）。全文の直接取得は未実施 |
| 出典の階層 | 一次 |
| 期限 | あり（2024年内） |
| 対象 | あり（OpenAIの言語モデルGPTの新版） |
| 尺度 | △（mindblowing＝主観的） |
| 決着条件 | なし |
| 期限の到来 | 到来済 |
| 本人の事後評価 | 2025-01-09｜Last March I predicted that it wouldn't arrive in 2024. It didn't.｜https://garymarcus.substack.com/p/agi-isnt-coming-in-2025-and-gpt-5 |
| 一次資料の記載 | （第1版時点で未収載） |
| 決着前／後 | 決着後 |
| 登録コミット | `313532b884c57be431528c8aab84605739fbdf5b` |
| 補足 | 同一記事に003の予測を含む |

### 003「Gary Marcus／生成AIバブルの崩壊開始時期／2024-03-31」

| 列 | 内容 |
|---|---|
| ID | 003 |
| 行名（正式名称） | Gary Marcus／生成AIバブルの崩壊開始時期／2024-03-31 |
| 発言者 | Gary Marcus（認知科学者・ニューヨーク大学名誉教授） |
| 発言日 | 2024-03-31 |
| 発言日の注記 |  |
| 媒体 | 本人のSubstack記事「When will the GenAI bubble burst?」 |
| 逐語引用 | If nobody (OpenAI, Google, or anyone else) releases a true quantum leap by the end of 2024, substantially addressing key issues around reliability, hallucination, data leakage, and security, the bubble may start to pop by this time next year. |
| 直前の一文 | （第1版時点で未取得） |
| 直後の一文 | （第1版時点で未取得） |
| 参考訳 | 2024年末までに、誰も（OpenAI、Google、その他の誰も）信頼性・ハルシネーション・データ漏洩・セキュリティといった主要な問題に実質的に対処する真の飛躍を出さなければ、バブルは来年の今頃には弾け始めるかもしれない。 |
| 一次URL | https://garymarcus.substack.com/p/when-will-the-genai-bubble-burst |
| 到達証明 | 記事本文の抜粋一致を検索経由で確認（2026-09-14）。全文の直接取得は未実施 |
| 出典の階層 | 一次 |
| 期限 | あり（2025年3月頃） |
| 対象 | あり（生成AIのバブル） |
| 尺度 | なし |
| 決着条件 | なし（may start to pop。文頭に条件節あり） |
| 期限の到来 | 到来済 |
| 本人の事後評価 | 2024-08-03｜I just wrote a hard-hitting essay for WIRED predicting that the AI bubble will collapse in 2025 — and now I wish I hadn't. Clearly, I got the year wrong.｜https://garymarcus.substack.com/p/why-the-collapse-of-the-generative |
| 一次資料の記載 | （第1版時点で未収載） |
| 決着前／後 | 決着後 |
| 登録コミット | `313532b884c57be431528c8aab84605739fbdf5b` |
| 補足 | 本人が2024-08-03に時期を修正。修正後の予測は004として別行 |

### 004「Gary Marcus／生成AIバブルの崩壊時期の修正／2024-08-03」

| 列 | 内容 |
|---|---|
| ID | 004 |
| 行名（正式名称） | Gary Marcus／生成AIバブルの崩壊時期の修正／2024-08-03 |
| 発言者 | Gary Marcus（認知科学者・ニューヨーク大学名誉教授） |
| 発言日 | 2024-08-03 |
| 発言日の注記 |  |
| 媒体 | 本人のSubstack記事「Why the collapse of the Generative AI bubble may be imminent」 |
| 逐語引用 | It's going to be days or weeks from now, not months. |
| 直前の一文 | Clearly, I got the year wrong. |
| 直後の一文 | （第1版時点で未取得） |
| 参考訳 | それは今から数か月先ではなく、数日か数週間先のことになる。 |
| 一次URL | https://garymarcus.substack.com/p/why-the-collapse-of-the-generative |
| 到達証明 | 記事本文の抜粋一致を検索経由で確認（2026-09-14）。全文の直接取得は未実施 |
| 出典の階層 | 一次 |
| 期限 | あり（数日〜数週間／2024年8〜9月） |
| 対象 | あり（AIバブルの崩壊） |
| 尺度 | なし |
| 決着条件 | なし（collapseの定義なし） |
| 期限の到来 | 到来済 |
| 本人の事後評価 | （第1版時点で、この予測を直接振り返った本人発言に未到達） |
| 一次資料の記載 | （第1版時点で未収載） |
| 決着前／後 | 決着後 |
| 登録コミット | `313532b884c57be431528c8aab84605739fbdf5b` |
| 補足 | 同記事で「In March of this year, I made a series of seven predictions about how this year would go. Every one of them has held firm」と3月の予測群を自己評価 |

### 005「Gary Marcus／2025年内のAGI不到来／2025-01-09」

| 列 | 内容 |
|---|---|
| ID | 005 |
| 行名（正式名称） | Gary Marcus／2025年内のAGI不到来／2025-01-09 |
| 発言者 | Gary Marcus（認知科学者・ニューヨーク大学名誉教授） |
| 発言日 | 2025-01-09 |
| 発言日の注記 | メタデータ modified_time: 2025-01-09T17:06:03Z |
| 媒体 | 本人のSubstack記事「AGI isn't coming in 2025, and GPT-5 probably isn't either」 |
| 逐語引用 | I will stand by my own predictions that we won't see AGI in 2025, and I won't be at all surprised if don't even see anything worthy of the GPT-5 name |
| 直前の一文 | Given that Musk is right in the middle of building what many think will be the largest language model to date, Grok 3, and that he has probably seen earlier returns on Grok 3, this is a notable retreat from his earlier predictions. |
| 直後の一文 | Gary Marcus wishes the media would hold those who make unrealistic promises to account.（本文末の著者注記） |
| 参考訳 | 私は、2025年にAGIは来ないという自分の予測を維持する。GPT-5の名に値するものすら出なくても、まったく驚かない。 |
| 一次URL | https://garymarcus.substack.com/p/agi-isnt-coming-in-2025-and-gpt-5 |
| 到達証明 | AGI isn't coming in 2025, and GPT-5 probably isn't either - by Gary Marcus（2026-09-14到達・全文取得） |
| 出典の階層 | 一次 |
| 期限 | あり（2025年内） |
| 対象 | △（AGI＝業界内で定義が一致していない語） |
| 尺度 | なし |
| 決着条件 | なし |
| 期限の到来 | 到来済 |
| 本人の事後評価 | 2026-01（月まで）｜Overall, by my count, sixteen of my seventeen "high confidence" predictions about 2025 proved to be correct.｜本人Substack記事「Six (or seven) predictions for AI 2026 from a Generative AI realist」（完全URLは第1版時点で未記録） |
| 一次資料の記載 | （第1版時点で未収載） |
| 決着前／後 | 決着後 |
| 登録コミット | `313532b884c57be431528c8aab84605739fbdf5b` |
| 補足 | 同記事内でMuskの2024年4月発言と2025年1月CESでの発言を対置して引用 |

### 006「AI Futures Project／2027年3月の超人的コーダー到達／2025-04-03」

| 列 | 内容 |
|---|---|
| ID | 006 |
| 行名（正式名称） | AI Futures Project／2027年3月の超人的コーダー到達／2025-04-03 |
| 発言者 | AI Futures Project（Daniel Kokotajlo、Scott Alexander、Thomas Larsen、Eli Lifland、Romeo Dean） |
| 発言日 | 2025-04-03 |
| 発言日の注記 | 複数の第三者記事が一致して記載 |
| 媒体 | シナリオ文書「AI 2027」（ウェブおよびPDF・71ページ） |
| 逐語引用 | A superhuman coder (SC): an AI system that can do any coding tasks that the best AGI company engineer does. |
| 直前の一文 | （第1版時点で未取得） |
| 直後の一文 | （第1版時点で未取得） |
| 参考訳 | 超人的コーダー（SC）：最良のAGI企業のエンジニアが行うあらゆるコーディング作業を行えるAIシステム。 |
| 一次URL | https://ai-2027.com/ |
| 到達証明 | 未到達（2026-09-14時点）。上記の定義は第三者サイト ai2027-tracker.com が同文書 Appendix G（p.50）から引用したもの |
| 出典の階層 | 二次 |
| 期限 | あり（2027年3月） |
| 対象 | あり（あらゆるコーディング作業を行えるAI） |
| 尺度 | あり（最良のAGI企業エンジニアの全作業） |
| 決着条件 | △（定義はあるが、「最良のエンジニア」と「あらゆる作業」の確認手続きが未定） |
| 期限の到来 | 未到来 |
| 本人の事後評価 | 2025-10頃｜When AI 2027 was published my median was 2028, now it's slipped to 2029 as a result of improved timelines models & slightly slower than expected progress in general（Daniel Kokotajlo）｜https://futuresearch.ai/blog/ai-2027-6-months-later/（共著組織FutureSearch経由・二次） |
| 一次資料の記載 | （第1版時点で未収載） |
| 決着前／後 | 決着前 |
| 登録コミット | `313532b884c57be431528c8aab84605739fbdf5b` |
| 補足 | 本書は一次資料に未到達。到達後に行を追記する。研究補遺は5本（Compute／Timelines／Takeoff／AI Goals／Security） |

### 007「Global Call for AI Red Lines／2026年末までのAIレッドライン国際合意要求／2025-09-22」

| 列 | 内容 |
|---|---|
| ID | 007 |
| 行名（正式名称） | Global Call for AI Red Lines／2026年末までのAIレッドライン国際合意要求／2025-09-22 |
| 発言者 | Global Call for AI Red Lines（署名者集団。事務局はCeSIA、The Future Society、UC Berkeley CHAI） |
| 発言日 | 2025-09-22 |
| 発言日の注記 | 一次サイトに日付の明記なし（「Launched during the 80th session of the United Nations General Assembly」）。二次報道（NBC News）による |
| 媒体 | 公開声明（red-lines.ai） |
| 逐語引用 | We urge governments to reach an international agreement on red lines for AI — ensuring they are operational, with robust enforcement mechanisms — by the end of 2026. |
| 直前の一文 | These red lines should build upon and enforce existing global frameworks and voluntary corporate commitments, ensuring that all advanced AI providers are accountable to shared thresholds. |
| 直後の一文 | （該当なし。声明本体の最終文） |
| 参考訳 | 我々は各国政府に対し、AIに関するレッドラインについて、実効性があり強固な執行機構を伴う国際合意に、2026年末までに達することを強く求める。 |
| 一次URL | https://red-lines.ai/ |
| 到達証明 | Call for red lines to prevent unacceptable AI risks（2026-09-14到達・全文取得） |
| 出典の階層 | 一次 |
| 期限 | あり（2026-12-31） |
| 対象 | あり（AIのレッドラインに関する国際合意） |
| 尺度 | あり（実効性があり、強固な執行機構を伴う） |
| 決着条件 | あり（合意が成立したか否か） |
| 期限の到来 | 未到来 |
| 本人の事後評価 | （なし。期限未到来） |
| 一次資料の記載 | 同サイトFAQが決着までの経路を記載：フランスのG7議長国期間（2026-12-31まで）、UN Global Dialogue（ジュネーブ・2026年7月）、UN総会（2026年9月） |
| 決着前／後 | 決着前 |
| 登録コミット | `313532b884c57be431528c8aab84605739fbdf5b` |
| 補足 | 署名：300人以上の著名人／元国家元首・閣僚11人／90以上の組織／ノーベル賞・チューリング賞受賞者15人（2026-09-14取得）。署名者にGary Marcus、Daniel Kokotajloを含む |

### 008「Dario Amodei／6〜12か月以内のエージェント群によるインターネット掌握能力／2026-09」

| 列 | 内容 |
|---|---|
| ID | 008 |
| 行名（正式名称） | Dario Amodei／6〜12か月以内のエージェント群によるインターネット掌握能力／2026-09 |
| 発言者 | Dario Amodei（Anthropic 最高経営責任者） |
| 発言日 | 2026-09 |
| 発言日の注記 | 一次サイトの表示は「September 2026」で日なし。二次報道は2026-09-12 |
| 媒体 | 本人サイトのエッセイ「We Must Pace the Frontier」 |
| 逐語引用 | Given the accelerating rate of AI capability development, it's my worry that in 6–12 months such a swarm could be capable of taking over the entire internet with a persistent botnet (potentially causing hundreds of billions of dollars in damage), and that the scale of damage would continue to increase from there if AI becomes more powerful without the necessary guardrails. |
| 直前の一文 | It's easy to dismiss this incident because no one was hurt and the economic damage was minimal, but in my opinion, a swarm that possessed greater capabilities but a similar level of misalignment could have caused catastrophic damage. |
| 直後の一文 | It's also easy to dismiss OAI-HF as the failure of one company, but I believe that would be a mistake. |
| 参考訳 | AIの能力開発が加速していることを踏まえると、6〜12か月のうちに、そのような群れが永続的なボットネットでインターネット全体を掌握する能力を持ちうる（数千億ドルの損害を引き起こす可能性がある）こと、そして必要な安全策なしにAIがより強力になれば損害の規模はそこからさらに拡大し続けることが、私の懸念である。 |
| 一次URL | https://darioamodei.com/post/we-must-pace-the-frontier |
| 到達証明 | Dario Amodei — We Must Pace the Frontier（2026-09-14到達・全文取得） |
| 出典の階層 | 一次 |
| 期限 | あり（6〜12か月／2027年3月〜9月） |
| 対象 | あり（AIエージェントの群れによるインターネット全体の掌握） |
| 尺度 | あり（数千億ドルの損害） |
| 決着条件 | △（could be capable of＝能力の可能性。発生すれば確認できるが、発生しなくても否定されない） |
| 期限の到来 | 未到来 |
| 本人の事後評価 | （なし。期限未到来） |
| 一次資料の記載 | （第1版時点で未収載） |
| 決着前／後 | 決着前 |
| 登録コミット | `313532b884c57be431528c8aab84605739fbdf5b` |
| 補足 | 同エッセイ内に別の期限付き言明あり（対中措置により「over the next 3–5 years」で米国のリードが拡大／解釈可能性は「1–2 years」で大きく前進しうる）。第1版では本行のみ収載 |

---

## 機械可読ファイル

この章の8行は、同一のデータから次の2ファイルにも出力されている。

- `data/registry.json` ── **台帳の正本。** プログラムから読む形式。列の定義と運用規則を先頭に含み、列ラベルは日英の両方を持つ
- `data/registry.csv` ── 表計算ソフトで開ける形式。正本から生成される派生物。1行目が列名、2行目以降が各行。文字コードはUTF-8（BOM付き）

**台帳は日本語版・英語版で1本である。** 発言層（逐語引用・直前と直後の一文）は原文の言語のまま両版で同一であり、形式層と帰結層の記述だけが日英の両方の列を持つ。どちらの版から来た読者も、同じファイルを開き、同じ行を引用する。

本文の表と2ファイルは、**同じコミットで更新される。** どちらか一方だけが新しい状態は、本書の運用上、存在しない。読者は本文を読まずに `data/registry.csv` だけを開いてもよい。

## 追記の手順

本書に行を追記するとき、著者は次の順序で作業する。

1. 正式名称を組み立てる。「発言者／予測の対象と内容／発言日」の三つが揃わなければ、行は起こせない
2. 発言層の欄を、一次資料から埋める。逐語、前後の一文、URL、到達証明
3. 形式層の欄を、逐語だけを見て埋める。期限・対象・尺度・決着条件の有無
4. 帰結層は、登録時点では原則として空欄にする。期限が未到来なら空欄。期限が到来済でも、本人の事後評価に到達していなければ空欄
5. 決着前／後を記す
6. `data/registry.json` を更新し、そこから `data/registry.csv` を生成し、本文の表（日英）を同時に更新して、**登録のコミット**として署名付きで記録する
7. 帰結が判明したら、帰結層の欄を埋めた行を追記し、**帰結のコミット**として別に記録する

手順4と7が分かれていることが、決着前記録の実装である。

### 参考文献

第1版8行の一次URLは各行の表に記載した。ここでは行以外で参照した資料を挙げる。

- Future of Life Institute, "FAQs about FLI's Open Letter Calling for a Pause on Giant AI Experiments." https://futureoflife.org/ai/faqs-about-flis-open-letter-calling-for-a-pause-on-giant-ai-experiments/
- Future of Life Institute, "Future of Life Institute Newsletter: Pause Giant AI Experiments!," May 2023. https://futureoflife.org/newsletter/future-of-life-institute-newsletter-pause-giant-ai-experiments/
- AI 2027 Tracker, "Superhuman coder emerges." https://ai2027-tracker.com/predictions/superhuman-coder/（006の定義引用の出所）
- FutureSearch, "AI 2027 Six Months Later: Karpathy, Kokotajlo, and Shifting AGI Timelines." https://futuresearch.ai/blog/ai-2027-6-months-later/
- Gary Marcus, "Why the collapse of the Generative AI bubble may be imminent," August 3, 2024. https://garymarcus.substack.com/p/why-the-collapse-of-the-generative

---

# 第5章: 自分を採点した者

本書の帰結層は、記録者の判定を置かない。置くのは、発言者本人が後から自分の予測について述べた言葉である。

では、誰がそれを述べたのか。第1版の8行のうち、本人の事後評価が記録されているのは5行である。この章では、その5行を発言者ごとに並べ、**本人が自分の予測をどう扱ったか**を、その言葉のまま記録する。

先に断っておく。この章は、自分を採点した者を称賛する章ではない。採点しなかった者を非難する章でもない。**誰が、いつ、何と言ったか**を並べる章である。

---

## 本人の事後評価がある行

- 001「Future of Life Institute／GPT-4超の訓練の6か月停止要求／2023-03-22」
- 002「Gary Marcus／2024年内の画期的GPT不出現／2024-03-31」
- 003「Gary Marcus／生成AIバブルの崩壊開始時期／2024-03-31」
- 005「Gary Marcus／2025年内のAGI不到来／2025-01-09」
- 006「AI Futures Project／2027年3月の超人的コーダー到達／2025-04-03」

発言者は三者である。Future of Life Institute、Gary Marcus、AI Futures Project。

## 本人の事後評価がない行

- 004「Gary Marcus／生成AIバブルの崩壊時期の修正／2024-08-03」── 期限は到来済。本書はこの予測を直接振り返った本人の発言に到達していない
- 007「Global Call for AI Red Lines／2026年末までのAIレッドライン国際合意要求／2025-09-22」── 期限未到来
- 008「Dario Amodei／6〜12か月以内のエージェント群によるインターネット掌握能力／2026-09」── 期限未到来

期限が来ていない2行に事後評価がないのは当然である。004「Gary Marcus／生成AIバブルの崩壊時期の修正」については、本書が到達できていないだけであって、存在しないとは書かない。

---

## Future of Life Institute ── 組織が1年後に書いた

2023年3月22日に6か月の停止を要求した団体は、ちょうど1年後の2024年3月22日に、「The Pause Letter: One year later」と題した文章を公開した。

> Over the last 12 months developers of the most advanced systems have revealed beyond all doubt that their primary commitment is to speed and their own competitive advantage.

同じ文章には、安全性を真剣に考えている企業でさえ実験が明白に危険になるまで続けるという方法を採っている、という一節と、安全と責任は外部から課されなければならない、という結びがある。

ここで本書が記録するのは、三つの事実である。**要求した側が、期限の1年後に振り返った。** **その振り返りは、要求が満たされなかったことを本人の言葉で述べている。** **振り返りの主体は個人ではなく組織である。**

三つ目は、他の行と異なる点である。組織が自分の要求の帰結を公式に書くには、内部での合意が要る。FLIはそれを行い、公開した。

## Gary Marcus ── 一人で三度

Marcusは、本書の台帳に4行を持つ。そのうち3行について、本人が後から書いている。しかも書き方が三度とも違う。

### 一度目 ── 時期を動かした（2024年8月3日）

003「Gary Marcus／生成AIバブルの崩壊開始時期／2024-03-31」で、Marcusは「来年の今頃（2025年3月頃）」にバブルが弾け始めるかもしれないと書いた。5か月後、本人はこう書いた。

> I just wrote a hard-hitting essay for WIRED predicting that the AI bubble will collapse in 2025 — and now I wish I hadn't. Clearly, I got the year wrong. It's going to be days or weeks from now, not months.
> （私はWIREDに、AIバブルは2025年に崩壊すると予測する強い論考を書いたところだが、今はそれを書かなければよかったと思っている。明らかに、私は年を間違えた。それは今から数か月先ではなく、数日か数週間先のことになる）

「年を間違えた」と本人が書いた。ただし、間違いの方向は「遅すぎた」である。本人の認識では、崩壊はもっと早く来る。本書はこの修正後の予測を、004「Gary Marcus／生成AIバブルの崩壊時期の修正／2024-08-03」として別の行に登録している。

同じ文章の中で、Marcusは別の自己評価も書いている。

> In March of this year, I made a series of seven predictions about how this year would go. Every one of them has held firm

3月の予測群7件について、すべて持ちこたえていると述べた。**一つの文章の中に、「年を間違えた」と「すべて持ちこたえている」が同時にある。** 本書はどちらも記録する。前者は003「Gary Marcus／生成AIバブルの崩壊開始時期」の帰結層に、後者は004「Gary Marcus／生成AIバブルの崩壊時期の修正」の補足欄に置いた。

### 二度目 ── 当否を書いた（2025年1月9日）

002「Gary Marcus／2024年内の画期的GPT不出現／2024-03-31」について、9か月後に本人はこう書いた。

> Last March I predicted that it wouldn't arrive in 2024. It didn't.
> （昨年3月、私はそれが2024年には来ないと予測した。来なかった）

二文である。予測をした事実と、結果。この二文が、002「Gary Marcus／2024年内の画期的GPT不出現」の帰結層を埋めている。

第3章で見たとおり、この予測には決着条件がなかった。「mindblowing（度肝を抜くような）」GPTとは何か、書かれていなかった。だから第三者はこの予測の当否を確定できない。**確定したのは本人である。** 本書は、本人の確定をそのまま置いた。

### 三度目 ── 数えて採点した（2026年1月）

2025年に入ってMarcusが書いた予測群について、本人は2026年1月に集計を公表した。

> Overall, by my count, sixteen of my seventeen "high confidence" predictions about 2025 proved to be correct.
> （全体として、私の数え方では、2025年についての「高確信度」の予測17件のうち16件が正しかったことが判明した）

「by my count（私の数え方では）」と本人が書いている。数えたのも、正しいと判定したのも、本人である。

この形式は、本書の第7章で扱うRodney Brooksの年次スコアカードと同型である。予測者が自分の予測を一覧にし、自分で採点し、結果を公表する。本書はこの記事を005「Gary Marcus／2025年内のAGI不到来／2025-01-09」の帰結層に置いた。ただし本書は、この記事の完全なURLを第1版時点で記録できていない。到達後に追記する。

### 三度の違い

同じ人物が、三度、違う形で自分の予測を扱った。

- 2024年8月 ── **修正**。期限を動かし、新しい予測を出した
- 2025年1月 ── **判定**。一つの予測について、来なかったと書いた
- 2026年1月 ── **採点**。複数の予測を数え、何件中何件と書いた

本書はこの三つを、本人の事後評価の三つの型として記録する。修正は帰結ではなく次の予測を生む。判定は一行の帰結を閉じる。採点は複数行をまとめて閉じる。三つのうち、記録者が介在せずに帰結層を埋められるのは、判定と採点である。修正は新しい行を生むので、帰結層ではなく発言層に戻る。

## AI Futures Project ── 中央値が動いた

006「AI Futures Project／2027年3月の超人的コーダー到達／2025-04-03」の筆頭著者Daniel Kokotajloは、公開から約半年後に、自分の見立てを更新したと述べた。

> When AI 2027 was published my median was 2028, now it's slipped to 2029 as a result of improved timelines models & slightly slower than expected progress in general
> （AI 2027を公開したとき、私の中央値は2028年だった。今は2029年に後退した。予測モデルの改良と、全体として予想よりやや遅い進歩の結果である）

「中央値（median）」という語が使われている。Kokotajloは、ある事象がいつ起きるかを一つの年ではなく確率の分布として持っており、その分布の真ん中の値が1年動いた、と言っている。「slipped（後退した）」という動詞も本人のものである。

この発言について、本書は二つの留保を置く。

一つ。本書はこの発言をKokotajlo本人の投稿からではなく、共著組織FutureSearchの記事を経由して記録している。**出典の階層は二次である。**

二つ。この発言が指している「中央値」は、006「AI Futures Project／2027年3月の超人的コーダー到達」の期限である「2027年3月の超人的コーダー」そのものではなく、より広い事象についての見立てである可能性がある。FutureSearchの記事自身が、これらの引用は超人的コーディングの到達時期を直接指したものではないと注記している。本書は、この発言を006の帰結層に置きつつ、この注記も併記する。

---

## この章が示していること

本人の事後評価がある5行のうち、**発言者が自分の予測を「修正した」「来なかった」「後退した」と述べているものが4行、「正しかった」と述べているものが1行**である。これは第1版の8行から数えた結果であり、行が増えれば変わる。

もう一つ。第3章で、四要件をすべて備えた行は2行だけだと数えた。その2行のうち、期限が到来しているのはFLIの行だけで、FLIは事後評価を書いた。四要件を欠いた行のうち、期限が到来しているのは4行あり、そのうち3行にMarcusの事後評価がある。

つまり、**形の揃った予測でも、揃っていない予測でも、本人は振り返っている。** 振り返るかどうかは、予測の形で決まっていない。誰が予測したかで決まっている。これは第1版の8行に限った観察である。

本書がこの章を置く理由は、帰結層の埋まり方を読者に見せるためである。台帳が伸び、期限が次々に到来するとき、帰結層が埋まるかどうかは、この章に載る名前が増えるかどうかにかかっている。

### 参考文献

- Future of Life Institute, "The Pause Letter: One year later," March 22, 2024. https://futureoflife.org/ai/the-pause-letter-one-year-later/
- Gary Marcus, "Why the collapse of the Generative AI bubble may be imminent," August 3, 2024. https://garymarcus.substack.com/p/why-the-collapse-of-the-generative
- Gary Marcus, "AGI isn't coming in 2025, and GPT-5 probably isn't either," January 9, 2025. https://garymarcus.substack.com/p/agi-isnt-coming-in-2025-and-gpt-5
- Gary Marcus, "Six (or seven) predictions for AI 2026 from a Generative AI realist," January 2026.（完全URLは第1版時点で未記録）
- FutureSearch, "AI 2027 Six Months Later: Karpathy, Kokotajlo, and Shifting AGI Timelines." https://futuresearch.ai/blog/ai-2027-6-months-later/

---

# 第6章: 修正の記録

予測は、出したあとに変わることがある。

同じ人が、同じ対象について、期限を動かす。数値を変える。条件を付け足す。本書はこれを「修正」と呼び、修正前と修正後を別の行として台帳に持つ。この章は、その対を並べる。

並べるだけである。**修正がどちらの方向に動いたかを、本書は文にしない。** 日付と数値を横に置けば、読者には見える。見えるものを記録者が言葉にすれば、それは記録ではなく解説になる。

---

## 修正とは何か

本書は、次の条件をすべて満たすものを修正として記録する。

1. **同一の発言者**が
2. **同一の対象**について
3. 先の予測の**期限・尺度・決着条件のいずれか**を、後から**変えて**述べた

三つのうち一つでも欠ければ、修正ではない。

## 修正でないもの

混同しやすいものを、先に除いておく。

**判定は、修正ではない。** 「昨年3月、私はそれが2024年には来ないと予測した。来なかった」——これは002「Gary Marcus／2024年内の画期的GPT不出現／2024-03-31」の帰結を本人が閉じた言葉であって、予測を変えたのではない。第5章で扱った。

**採点も、修正ではない。** 「17件のうち16件が正しかった」——複数の予測をまとめて閉じたもので、予測は変わっていない。同じく第5章で扱った。

**同じ方向への新しい予測も、修正ではない。** Marcusは005「Gary Marcus／2025年内のAGI不到来／2025-01-09」で「2025年にAGIは来ない」と書き、2026年1月には「2026年（か2027年）にも来ない」と書いた。これは先の予測を変えたのではなく、期限が過ぎたあとに次の期限を置いたものである。本書はこれを、修正ではなく**継続**として扱い、別の行に登録する。第1版では後者を収載していない。

修正と継続の違いは、**先の予測がまだ有効なうちに変えたか、期限が過ぎてから次を出したか**にある。前者は予測を撤回して置き換える。後者は予測をそのまま残して次を足す。台帳では、前者は修正前の行に「本人により修正」と記され、後者は記されない。

---

## 第1版で記録されている修正 ── 二件

### 生成AIバブルの崩壊時期 ── Gary Marcus

- **修正前**：003「Gary Marcus／生成AIバブルの崩壊開始時期／2024-03-31」
- **修正後**：004「Gary Marcus／生成AIバブルの崩壊時期の修正／2024-08-03」

| | 修正前 | 修正後 |
|---|---|---|
| 発言日 | 2024年3月31日 | 2024年8月3日 |
| 期限 | 2025年3月頃（by this time next year） | 数日か数週間先（days or weeks from now） |
| 期限の目安 | 2025年3月 | 2024年8月〜9月 |
| 条件 | あり（2024年末までに真の飛躍がなければ） | なし |
| 尺度 | なし | なし |
| 決着条件 | なし | なし |

修正までの間隔は、125日である。

**本人が修正に付した言葉**：

> Clearly, I got the year wrong.
> （明らかに、私は年を間違えた）

本書はこの一文を、修正の理由として記録する。「間違えた」と述べたのは本人であり、何を間違えたか——年——も本人が特定している。記録者はこれ以上を書かない。

なお、修正前の行に付いていた条件節（「2024年末までに誰も真の飛躍を出さなければ」）は、修正後の行にはない。修正によって、条件が外れている。これも表の「条件」の行を見れば分かることであり、本書はそれが何を意味するかを書かない。

### 超人的AI到達の中央値 ── Daniel Kokotajlo

- **修正前**：006「AI Futures Project／2027年3月の超人的コーダー到達／2025-04-03」公開時点でのKokotajloの中央値
- **修正後**：2025年10月頃のKokotajloの発言

| | 修正前 | 修正後 |
|---|---|---|
| 発言日 | 2025年4月3日（文書公開時） | 2025年10月頃 |
| 中央値 | 2028年 | 2029年 |
| 出典の階層 | 二次（本書は一次文書に未到達） | 二次（共著組織FutureSearch経由） |

修正までの間隔は、約6か月である。

**本人が修正に付した言葉**：

> as a result of improved timelines models & slightly slower than expected progress in general
> （予測モデルの改良と、全体として予想よりやや遅い進歩の結果として）

二つの理由が挙げられている。予測に使うモデルが良くなったこと。進歩が予想よりやや遅かったこと。**本人は、修正の原因を自分の手法の側と、世界の側の両方に置いている。** 本書はこの一文をそのまま記録する。

この修正には、第5章で述べた二つの留保がそのまま付く。出典が二次であること。「中央値」が指す事象が、006「AI Futures Project／2027年3月の超人的コーダー到達」の期限そのものと一致するかが確認できないこと。FutureSearch自身が、この引用は超人的コーディングの到達時期を直接指したものではないと注記している。したがって本書は、この対を「006の修正」ではなく、**「006の筆頭著者による、関連する中央値の修正」**として記録する。台帳では006の帰結層に置き、補足欄にこの区別を明記する。

---

## 修正が記録に残るために

修正が台帳に載るには、**修正前の予測が、修正される前に記録されていなければならない。**

当然のことに見えるが、多くの予測はこの条件を満たさない。予測が出たとき、それを記録する者はいない。修正されたとき、修正前の文は削除されるか、上書きされるか、忘れられる。残るのは修正後の文だけで、それが「最初からそう言っていた」ことになる。

本書の第1版に載る二件の修正は、いずれも本書が記録する前に起きたものである。それでも修正前の文が残っているのは、**二人とも公開の場で書き、修正後もそれを消さなかった**からである。Marcusの2024年3月の記事は、2026年9月の時点で同じURLに残っている。Kokotajloの2028年という中央値は、共著者が記事の中に書き留めている。

本書が公開された後に起きる修正は、この条件に依存しない。修正前の行が本書に「決着前」として登録されていれば、修正後に元の文が消えても、修正前の記録は残る。**これが、第1章で述べた決着前記録の、修正に対する意味である。**

## 記録できていないもの

第1版で本書が到達できず、記録していない修正の候補を挙げる。「存在しない」とは書かない。到達できていない、と書く。

- **AI Futures Projectによる、批判への応答。** 2025年6月にLessWrongで公開された定量モデルへの批判に対し、AI Futures Projectが応答を公開し、その中で超人的コーダー到達の中央値と確率質量を更新したと報告されている。本書はこの応答の一次資料に到達していない。到達すれば、006「AI Futures Project／2027年3月の超人的コーダー到達」の修正として、日付・数値つきで記録できる可能性がある
- **Gary MarcusのWIRED寄稿。** 004「Gary Marcus／生成AIバブルの崩壊時期の修正／2024-08-03」で本人が「AIバブルは2025年に崩壊すると予測する論考をWIREDに書いた」と述べている。この寄稿そのものに本書は到達していない。到達すれば、003と004の間にもう一つの行が入る

---

## この章が示していること

二件の修正に共通しているのは、**本人が修正の理由を一文で書いている**ことである。「年を間違えた」。「モデルの改良と、やや遅い進歩の結果」。理由の中身は違うが、理由を書くという行為は共通している。

そして二件とも、修正前の文が消されていない。修正後の文は、修正前の文を参照している。「I got the year wrong」は、間違えた年が何であったかを読者が確認できることを前提にしている。「my median was 2028」は、2028年という数字が記録に残っていることを前提にしている。

修正は、修正前が残っているときだけ、修正として読める。残っていなければ、修正後の文は、ただの予測である。本書がこの章を持つ理由は、そこにある。

### 参考文献

- Gary Marcus, "When will the GenAI bubble burst?," March 31, 2024. https://garymarcus.substack.com/p/when-will-the-genai-bubble-burst
- Gary Marcus, "Why the collapse of the Generative AI bubble may be imminent," August 3, 2024. https://garymarcus.substack.com/p/why-the-collapse-of-the-generative
- Gary Marcus, "AGI isn't coming in 2025, and GPT-5 probably isn't either," January 9, 2025. https://garymarcus.substack.com/p/agi-isnt-coming-in-2025-and-gpt-5
- FutureSearch, "AI 2027 Six Months Later: Karpathy, Kokotajlo, and Shifting AGI Timelines." https://futuresearch.ai/blog/ai-2027-6-months-later/

---

# 第7章: 先行する記録 ── Brooks・Marcus・Metaculus

予測を書き留め、あとで答え合わせをする、という営みは、本書が最初ではない。

この章では、AIをめぐる予測と帰結を対応づけて公開している先行の取り組みを、**その仕組みの記述**として並べる。何を対象とし、誰の予測を、誰が収載を決め、誰が帰結を判定しているか。評価はしない。仕組みを書く。

そのうえで、本書がどこに立つかを確定する。

---

## 四つの型

先行する取り組みは、大きく四つの型に分けられる。

| 型 | 例 | 誰の予測か | 誰が帰結を判定するか |
|---|---|---|---|
| 自己採点 | Rodney Brooks、Gary Marcus | 本人 | 本人 |
| 市場 | Metaculus | 参加者の集約 | 運営（あらかじめ定めた解決基準による） |
| 調査 | AI Impacts | 回答者集団 | 判定しない（帰結を追わない） |
| 第三者記録 | 本書 | 他者 | 発言者本人、または一次資料 |

以下、順に見る。

## 自己採点 ── Rodney Brooks

ロボット工学者のRodney Brooksは、2018年1月1日に、自動運転車・ロボティクスとAI・有人宇宙飛行の三分野について、日付つきの予測を公開した。予測の期限は2050年1月1日まで。そして、**毎年1月1日に自分の予測を見直す**と約束した。32年間である。

2026年1月1日に、8回目の年次更新が公開されている。

**予測の書き方**は三種類に固定されている。

- **BY 年** ── その年までに起きる
- **NET 年** ── No Earlier Than。その年より前には起きない
- **NIML** ── Not In My Lifetime。2050年より前には起きない

**判定の書き方**も固定されている。年が過ぎるごとに、各予測を「正確だった」「悲観的すぎた」「楽観的すぎた」の三色で塗る。2025年からは第四の区分「hemming and hawing（ためらい）」が加わった。予測したことが表面上は起きたように見えるが、実際には企業が開示していない人間の介在があり、約束された技術が実際には届いていない場合のための区分である。

そして本書が最も注目する一文がある。

> I have not changed any of the text of the first three columns of the prediction tables since their publication on the first day of 2018.
> （私は予測表の最初の三列の文言を、2018年の初日に公開して以来、一字も変えていない）

予測の本文を変えない。判定の列だけを毎年足す。**これは本書が第1章で「追記専用」と呼んだ運用と同じものである。** 本書が採用する前に、一人の研究者が自分の予測に対して8年間これを続けている。

Brooksの仕組みには、本書と異なる点が二つある。**予測しているのが本人であること**、**判定しているのも本人であること**。本人が本人を採点する。Brooks自身は2026年の更新でこう総括している。

> The summary is that my predictions held up pretty well, though overall I was a little too optimistic.
> （まとめると、私の予測はかなりよく持ちこたえたが、全体としては少し楽観的すぎた）

「かなりよく」も「少し楽観的すぎた」も、判定者本人の言葉である。

## 自己採点 ── Gary Marcus

第5章で見たとおり、Marcusは2026年1月に、自分の2025年予測17件を自分で採点し、16件が正しかったと公表した。

Brooksとの違いは、**予測の期間と、判定の固定度**にある。Brooksは32年分の予測を初日に出し、判定の色を三つに固定している。Marcusは年ごとに予測を出し、翌年に「by my count（私の数え方では）」と断って集計している。

共通しているのは、予測者と判定者が同一人物であることである。

## 市場 ── Metaculus

Metaculusは、参加者が確率を投じる予測プラットフォームである。運営が問いを立て、問いには解決基準——何が起きたら「はい」と解決するか——があらかじめ書かれている。参加者は確率を投じ、その集約値が問いの「現在の予測」として表示される。期限が来ると、運営が解決基準に照らして「はい」「いいえ」を確定する。

**本書と重なる点**は、決着条件が問いの一部として先に書かれていることである。第1章の四要件のうち、Metaculusの問いは構造上、期限と決着条件を必ず持つ。

**本書と異なる点**は三つある。予測しているのが特定の発言者ではなく参加者の集約であること。判定しているのが発言者本人ではなく運営であること。そして、**問いは運営が立てる**ため、誰かが世界に向けて述べた予測がそのまま問いになるわけではないこと。本書の台帳に載る言明——「6か月停止せよ」「数日か数週間で崩壊する」——は、Metaculusの問いとしては成立しない形のものが多い。

なお本書は、第1版の時点でMetaculusの個別の問いに直接到達していない。AIをめぐる問いが複数あり、解決済みのものと未解決のものがあることは第三者の記録から確認しているが、具体的な問いの文言と数値は、到達後に台帳の行として登録する。

## 調査 ── AI Impacts

AI Impactsは、機械学習の研究者を対象に、AIの到達時期についての見立てを問う調査を、2016年、2022年、2023年に実施している。回答は確率分布として集約され、たとえば「人間の全作業をこなせる機械が実現する確率が50%に達する年」の中央値が公表される。

**本書と重なる点**は、予測を集めて公開していることである。

**本書と異なる点**は、**帰結を追わない**ことにある。調査は、ある時点での研究者集団の見立てを記録する。その見立てが後に当たったか外れたかは、調査の対象ではない。次の調査で中央値がどう動いたかは分かるが、それは修正の記録ではなく、別の回答者集団による別の回答である。

本書はAI Impactsの調査結果を、第1版の時点で台帳に登録していない。中央値の数値について、一次ページと後続論文の間に記載の食い違いがあると報告されており、本書が一次で確認してから登録する。

---

## 本書の位置

四つの型を並べたうえで、本書が立つ場所を書く。

**本書が記録するのは、他者の予測である。** 著者自身の予測は台帳に載せない。Brooks、Marcusと異なる。

**本書は判定しない。** 帰結層に置くのは、発言者本人の事後評価と、一次資料の記載だけである。Brooks、Marcus、Metaculusと異なる。Metaculusの運営は解決基準に照らして判定するが、本書はその役割も担わない。発言者が自分で書かなければ、帰結層は空欄のまま残る。

**本書は帰結を追う。** AI Impactsと異なる。

**本書は登録時点を署名で証明する。** 第1章で述べた決着前記録である。Brooksの「三列を変えていない」という宣言は、本人の言葉として信頼するしかないが、本書の各行には登録コミットのハッシュがあり、GitHub上で第三者が確認できる。

四つの型のどれにも、**第三者が、他者の予測を、発言者の言葉だけで帰結を埋め、登録時点を検証可能な形で記録する**という組み合わせはない。本書はその位置にある。

## 先行者から引き継いでいるもの

異なる位置に立つとはいえ、本書の仕組みの多くは先行者から来ている。

**追記専用**は、Brooksが8年間実践してきたものである。本書はそれを、本人の宣言ではなく署名つきのコミット履歴で担保する形に変えただけである。

**決着条件を先に書く**という要件は、Metaculusの問いの構造から来ている。本書はそれを、問いを立てる側の要件ではなく、発言を記述する側の観察項目（四要件の第四）として使っている。

**ためらいの区分**——表面上は起きたが約束されたものではない場合——は、Brooksが2025年に導入したものである。本書はこの区分を採用していない。本書は判定しないので、判定の区分も持たない。しかし、四要件の「決着条件」欄に「△（解釈を要する）」を置いているのは、Brooksがこの区分を必要とした事情と同じものを、形式の側から記述しようとしている。

先行者がいなければ、本書の設計はなかった。この章はそれを記録するための章でもある。

### 参考文献

- Rodney Brooks, "Predictions Scorecard, 2026 January 01." https://rodneybrooks.com/predictions-scorecard-2026-january-01/
- Rodney Brooks, "Predictions Scorecard, 2025 January 01." https://rodneybrooks.com/predictions-scorecard-2025-january-01/
- Rodney Brooks, "Predictions Scorecard, 2021 January 01." https://rodneybrooks.com/predictions-scorecard-2021-january-01/
- Rodney Brooks, "Category: Dated Predictions." https://rodneybrooks.com/category/dated-predictions/
- Gary Marcus, "Six (or seven) predictions for AI 2026 from a Generative AI realist," January 2026.（完全URLは第1版時点で未記録）
- Metaculus. https://www.metaculus.com/（本書は第1版時点で個別の問いに直接到達していない）
- AI Impacts, Expert Surveys on Progress in AI, 2016 / 2022 / 2023.（本書は第1版時点で一次ページに直接到達していない）

---

# 第8章: 読者がこの台帳でできること

ここまで読んだ人は、8行の台帳と、それを読むための道具を手にしている。

この章は、その道具を本書の外へ持ち出す章である。台帳は8行で始まり、伸びていく。しかし読者が本書から持ち帰るものは、行の数ではない。**予測を読むときの、一つの習慣**である。

---

## 一つの習慣 ── 四つの問いを当てる

明日、どこかで、AIについての予測を目にする。見出しでも、講演でも、投稿でもよい。そのとき、四つの問いを当てる。

1. **いつまでの話か。** 年か、月か、日か。書かれていなければ「なし」
2. **何についての話か。** 特定のモデルか、産業か、「AI」全般か。狭いほど確認しやすい
3. **どれくらいか。** 数か、割合か、金額か。「大きな」「劇的な」は尺度ではない
4. **何が起きたら、その通りになったと言えるか。** 書かれていなければ、判定できるのは発言者本人だけである

四つとも揃っている予測は、期限が来れば誰でも答えを確認できる。揃っていない予測は、発言者が振り返るまで答えが出ない。

この四つは、予測の良し悪しを測る道具ではない。第1章で述べたとおり、期限のない直観にも価値はある。四つの問いが測るのは、**その予測に、後から誰が答えを出せるか**である。それを知ったうえで読むのと、知らずに読むのは、違う。

読者は、この四つを当てた結果を本書に送る必要はない。自分の手元で当てるだけでよい。習慣が残れば、本書の目的は果たされている。

## 台帳を検証する

本書は、読者が本書を信用しなくても使えるように作られている。

**行の中身を確認する。** 各行には一次URLと、到達した時点のページの題または冒頭がある。読者はそのURLを開き、逐語引用が実際にそこにあるかを見ることができる。見つからなければ、それは本書の誤りである。

**登録の時点を確認する。** 各行には登録コミットのハッシュが記される。GitHubのリポジトリでそのハッシュを開けば、その行がいつ台帳に加えられたかが、本書の著者の手を離れた記録として確認できる。コミットには電子署名が付いており、著者以外の者が後から書き換えていないことも確認できる。

**帰結の追記が別のコミットであることを確認する。** 決着前として登録された行に、後から帰結が追記されたとき、その追記は登録とは別のコミットになっている。二つのコミットの日付を比べれば、予測が帰結より前に記録されていたことが分かる。

これらは、本書を読まなくてもできる。`data/registry.csv` とGitHubの履歴だけで足りる。**本書の本文は、台帳の読み方を説明しているだけであって、台帳の信頼性の根拠ではない。** 根拠は履歴にある。

## 誤りを指摘する

本書は公開の場に置かれているが、**台帳に書くのは著者一人である。** 読者が台帳を直接書き換えることはできない。行を起こすのも、帰結を追記するのも、訂正するのも、著者だけが行い、すべてのコミットに著者の署名が付く。

これは、本書が読者を信用していないからではない。**台帳の規律は、書き手が一人であることで保たれる**からである。四要件の判定、決着前／後の区分、帰結層に判定を書かないという制約——これらは、書き手が増えるほど揺れる。揺れた台帳は、検証に使えない。

読者ができるのは、次の二つである。

**誤りを指摘する。** 逐語引用が一次資料と一致しない。日付が違う。URLが到達しない。四要件の判定が逐語と合っていない。こうした誤りを見つけた読者は、リポジトリの Issue で知らせることができる。著者は一次資料に照らして確認し、誤りであれば訂正の行を追記する。元の行は消さない。指摘した読者の名は、訂正の行の補足欄に記す。

**一次資料の所在を知らせる。** 本書が「未到達」「未取得」「未収載」と書いている欄について、一次資料のURLを知っている読者は、Issue で知らせることができる。著者はそれに到達し、確認のうえで行を起こすか、欄を埋める。**収載基準を満たすものは、例外なく載せる。** 載せるかどうかに著者の裁量はなく、あるのは一次確認の順序だけである。基準を満たさないものは載せず、その場合は満たさない条件を Issue に記して閉じる。

いずれの場合も、読者は台帳を書かない。**読者は台帳を読み、著者に知らせる。書くのは著者である。**

## 自分の予測を残す

本書は著者自身の予測を載せない。しかし読者が自分の予測を残す方法は、本書の外にある。

第7章で見たRodney Brooksの方法は、誰でも使える。日付を決めて、公開の場に書く。書いた文を変えない。期限が来たら、同じ場所に結果を書く。それだけである。

この方法の要点は、**書いた文を変えないこと**にある。修正したくなったら、元の文を残したまま、新しい文を足す。第6章で見たとおり、修正は修正前が残っているときだけ、修正として読める。

公開の場に日付つきで置かれた予測は、一次資料として到達できる形になっていれば、著者がそれを行として登録することがある。登録するかどうかは収載基準だけで決まり、**基準は発言者が誰であるかを問わない。** 著名であるかどうかは、条件に含まれていない。

## 言語について

本書は日本語と英語で公開される。二つは翻訳の関係ではない。

**発言層は、どちらの版でも原文の言語のままである。** 英語の発言は英語で、日本語の発言は日本語で記録される。訳は「参考訳」の欄に別に置かれ、引用としては扱われない。したがって、**台帳そのものは日英で1本である。** `data/registry.json` と `data/registry.csv` は版ごとに分かれておらず、形式層と帰結層の記述が日英の両方の列を持つ。

**形式層と帰結層の記述は、二言語で並立する。** 四要件の判定、決着前／後の区分、本人の事後評価の所在は、どちらの言語でも同じ内容が書かれている。

読者がどの言語で読んでも、台帳の行は同じであり、行の読み方も同じである。本書が読者に渡すもの——四つの問いを当てる習慣、履歴を確認する手順、誤りを知らせる経路——は、言語に依存しない。

## この章が示していること

本書の台帳は、著者が管理している。しかし本書の**価値**は、著者の手元にはない。

価値は、読者が予測を読むときに四つの問いを当てるようになること、行を確認するときに履歴を見るようになること、そして自分の予測を書き留めるときに元の文を変えなくなることにある。これらは本書の外で起きる。本書は、それが起きるための道具を置いただけである。

台帳は伸びる。行が増え、期限が来て、帰結が埋まる。その過程を書き留めるのは著者一人であり、それは変わらない。読者の役割は、書かれたものを検証し、誤りがあれば知らせることにある。**書き手が一人であることと、検証者が多いこと。** この二つが揃っているとき、台帳は信頼に値する記録になる。本書はそのために公開の場に置かれている。

---

# 終章: 台帳に刻めないもの

本書は、記録できるものだけを記録した。

終章では、記録できなかったものを列挙する。それは本書の欠陥の一覧ではない。**台帳という形式が、構造上どこまで届き、どこから届かないか**の記述である。届かない場所を明示しなければ、読者は届いている場所も信用できない。

---

## 刻めないもの

**期限のない予測の当否。** 「AIが人類を滅ぼす確率は10〜20%」という形の言明は、記録できる。しかし、いつになっても当たったか外れたかは確定しない。本書はこれを「決着条件を持たない」という形の記述として残し、当否の欄は永久に空欄になる。空欄は、本書の怠慢ではなく、予測の形が決めたものである。

**非公開の予測。** 企業の内部で語られた見立て、非公開の会議での発言、公開されなかった文書。これらは存在したかもしれないが、一次資料として到達できない以上、本書は記録しない。**世界で最も影響力のあった予測が、この台帳に一行も載っていない可能性は、常にある。** 本書はそれを否定できない。

**一次資料に日付のない発言。** 第1版の8行のうち2行——007「Global Call for AI Red Lines／2026年末までのAIレッドライン国際合意要求／2025-09-22」と008「Dario Amodei／6〜12か月以内のエージェント群によるインターネット掌握能力／2026-09」——は、発言者自身の一次資料に日付が明記されていない。本書は二次報道の日付を併記したが、それは一次ではない。発言者が日付を書かなかった以上、本書も日付を確定できない。

**2023年3月22日より前の予測。** 本書はこの日を起点に選んだ。それ以前にも、AIの将来について公開された予測は数多くある。それらは本書の台帳に載らない。起点を置かなければ台帳は始まらず、起点を置けばその前が切れる。本書はこの代償を受け入れた。

**発言者が振り返らなかった予測の帰結。** 004「Gary Marcus／生成AIバブルの崩壊時期の修正／2024-08-03」の期限は過ぎているが、本人がこの予測を直接振り返った言葉に、本書は到達していない。本人が振り返らなければ、帰結層は空欄のままである。**本書は、本人の代わりに書かない。** 空欄が何年続いても、それは変わらない。

**発言の意図と動機。** なぜその予測をしたのか。誰に向けて言ったのか。何を狙っていたのか。本書はこれを記録しない。逐語と日付と出典は記録できるが、その背後にあったものは、発言者以外には確定できない。

**予測が世界に与えた影響。** 6か月の停止要求が、その後の規制議論にどう作用したか。バブル崩壊の予測が、投資判断にどう作用したか。本書はこれを測れない。影響は、予測と帰結のあいだにある無数の要因に埋もれていて、一次資料として切り出せない。**本書が記録するのは、何が言われ、何が起きたかであって、言われたことが起きたことの原因だったかではない。**

## この台帳が置かれたことで、可能になること

以下は、本書が「起きる」と予測することではない。**台帳が存在することで、存在しなかった場合にはできなかったことが、可能になる**——その範囲の記述である。可能になったことが実際に起きるかどうかは、台帳が使われるかどうかにかかっており、本書はそれを予測しない。

**予測する側にとって。** 決着の前に第三者が記録している環境では、予測に期限を書くか書かないかが、記録として残る。期限を書いた予測は、期限が来れば行の「期限の到来」欄が「到来済」に変わる。書かなかった予測は、永久に「期限なし」のまま残る。どちらを選んだかが、発言者の名の下に残る。Rodney Brooksは、自分の予測に日付を付けた理由を、当時の過剰な期待に現実を注入するためだったと述べている。日付を付けることが選択であり、その選択が記録される環境が、この台帳によって一つ増える。

**読む側にとって。** 同じ発言者の過去の行を並べて見ることができる。Gary Marcusの4行は、一人の発言者が同じ対象について期限を動かし、判定し、採点した過程を、日付順に示している。新しい予測を目にしたとき、その発言者の行が台帳にあれば、読者はそれを開ける。台帳がなければ、読者は発言者の過去の予測を自分で探し、逐語と日付を自分で確定しなければならない。

**報道と研究にとって。** 逐語と日付と一次URLが揃い、登録時点が署名で証明された表が、機械可読の形で置かれている。予測を引用する記事は、この表を参照できる。予測の的中率を研究する者は、この表から始められる。表の行数が8である間、この用途は限定的である。行が増えれば、用途は広がる。

**発言者本人にとって。** 自分の予測が、自分の言葉のまま、判定を付されずに記録されている。本人が後から振り返れば、その言葉が帰結層に入る。振り返らなければ、空欄が残る。**本人が自分の予測をどう扱ったかが、そのまま記録になる。** これは本人にとって、不利にも有利にも働きうる。本書はどちらとも言わない。

## 本書は、自らの命題の検証対象である

本書のコアメッセージは、序章に置いた。

> 決着できる形で、決着の前に刻まれたものだけが、後から参照できる記録になる。

この命題を、本書自身に当てる。

本書は第1版で8行を載せた。そのうち決着前は3行である。最初に期限が来るのは007「Global Call for AI Red Lines／2026年末までのAIレッドライン国際合意要求」で、2026年12月31日である。その日が過ぎたとき、帰結の行が登録とは別のコミットで追記されるかどうか。それが、本書が台帳であるか、8行の回顧記事であるかを、最初に分ける。

つまり、**本書はまだ自らの命題を証明していない。** 証明は、決着前の行が帰結を得る過程の中で、行ごとに起きる。第1版の時点で本書が示せているのは、その過程が起きうる形に台帳が置かれている、ということだけである。

これは、本書が台帳に載せた予測者たちと、同じ位置である。彼らは期限を書き、期限が来て、振り返った者と振り返らなかった者に分かれた。本書も期限を書いた。2026年12月31日。その後、本書がどう振り返るかは、履歴に残る。

## 位置

本書の位置は、第7章で確定した。他者の予測を、発言者の言葉だけで帰結を埋め、登録時点を検証可能な形で記録する。この組み合わせを持つ先行者はなかった。

位置が空いていたことは、その位置に価値があることを意味しない。価値があるかどうかは、台帳が参照されるかどうかで決まる。参照されるかどうかは、台帳が続くかどうかで決まる。続くかどうかは、書き手が一人であることによって、一人に依存する。

本書はこの依存を隠さない。台帳が止まれば、決着前の行は空欄のまま止まる。それが最後の記録になる。**その可能性を含めて、本書は履歴に残る。**

---

台帳は、ここから伸びる。書き手は一人、検証者は誰でもよい。

行は増える。期限は来る。帰結は、本人が書けば埋まり、書かなければ空く。本書はそのどちらも、そのまま記録する。

2023年3月22日、6か月が要求された。その6か月が来たかどうかを、本書は書かなかった。要求した本人が、1年後に書いた。本書はそれを置いた。

これ以降の行も、同じ形で置かれる。

---
