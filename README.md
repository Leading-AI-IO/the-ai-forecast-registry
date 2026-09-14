# The AI Forecast Registry

"A forecast becomes a record only if it was written down before anyone knew the answer." <br>
（予測は、答えを誰も知らないうちに書き留められていたときだけ、記録になる）

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Language](https://img.shields.io/badge/Language-Japanese%20%7C%20English-blue)](docs/)
[![Rows](https://img.shields.io/badge/Rows-8-informational)](data/registry.csv)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--09--14-brightgreen)](https://github.com/Leading-AI-IO/the-ai-forecast-registry/releases)

<p align="left">
  <img src="./assets/ogp_design.png" width="80%">
</p>

*Read this in other languages: [English](README_en.md)*

---

> **定義｜What is The AI Forecast Registry**
>
> **本書とは**、山内怜史（Satoshi Yamauchi）による、AIをめぐる公開された予測を
> 逐語・日付・一次URLの三点で記録し、その帰結を発言者自身の言葉だけで追う
> 追記専用の台帳である。起点は2023年3月22日、Future of Life Instituteの
> 公開書簡「Pause Giant AI Experiments」。各行は三つの層に分かれる。
> **発言層**は原文の言語のまま、前後の一文とともに記録する。**形式層**は
> 期限・対象・尺度・決着条件の四つの有無を、予測の真偽とは独立に記述する。
> **帰結層**に置くのは、発言者本人の事後評価と、一次資料に記載された事実の
> 二つだけであり、**「当たった」「外れた」という記録者の判定は本書のどこにも
> 書かない。** 予測の登録と帰結の追記は別のコミットとして署名付きで記録され、
> **予測が帰結より前に記録されていたことを第三者が検証できる。** 危険を訴えた
> 予測も、安全を訴えた予測も、能力の到来を否定した予測も、同じ基準で載せる。
> 中心命題：**決着できる形で、決着の前に刻まれたものだけが、後から参照できる
> 記録になる。**
>
> **This registry** records public forecasts about AI with verbatim text, dates
> and primary URLs, and fills their outcomes using only the forecaster's own
> later words. It begins on 22 March 2023 with the Future of Life Institute's
> open letter. Each row separates the statement, its form, and its outcome. The
> form layer describes the presence or absence of a deadline, a subject, a
> magnitude and a resolution condition — independently of whether the forecast
> proves true. The outcome layer holds only what the forecaster said afterwards
> and what a primary source states; **no verdict by the recorder appears
> anywhere.** Registration and outcome are separate signed commits, so a third
> party can verify that a forecast was recorded before its outcome was known.
> Forecasts warning of danger, arguing safety, and denying the arrival of
> capabilities are admitted on identical criteria.
>
> **管理と責任 / Governance**：台帳に書くのは著者一人である。公開されている
> ことと、誰でも書けることは別である。行を起こすのも、帰結を追記するのも、
> 訂正するのも著者だけが行い、すべてのコミットに署名が付く。読者ができるのは、
> 台帳を検証すること、誤りを指摘すること、一次資料の所在を知らせることである。
> **収載基準を満たすものは例外なく載せる。載せるかどうかに著者の裁量はなく、
> あるのは一次確認の順序だけである。** The author is the sole writer. Readers
> verify, report errors, and point to primary sources. Anything meeting the
> admission criteria is admitted without exception; there is no editorial
> discretion, only an order of verification.
>
> *著者・全書籍一覧 / Author & full catalog: [github.com/Leading-AI-IO](https://github.com/Leading-AI-IO)*

---

## 📖 概要

AIについての予測は、毎週のように出る。「2027年に人間を超える」「2030年までに仕事の半分が消える」「バブルは来年崩れる」「この技術は行き止まりだ」。言った人の肩書は重く、報道は大きく、そして数か月後には誰も覚えていない。

**問題は、忘れられることではない。忘れられた予測が、当たったのか外れたのか、あるいはそもそも当たり外れを判定できる形をしていたのかが、どこにも記録されていないことである。**

二つの言明を比べてみる。「AIは今後、人類にとって深刻な危険になる」と、「2026年末までに、各国政府はAIに関する国際合意に達すべきである」。前者は、いつまで待てば答えが出るのか書かれていない。後者には期限がある。2026年12月31日が過ぎれば、合意があったかなかったかは誰にでも確認できる。**この差は予測の中身の良し悪しではなく、形の差である。**

本書は、AIをめぐる予測をこの「形」の観点から記録する台帳である。

### 三つの層

**発言層**には、誰が、いつ、どこで、何と言ったかを置く。原文の言語のまま、一語も変えず、前後の一文とともに、一次URLと到達日を添えて。**記録者の言葉は一つも入らない。**

**形式層**には、予測の四要件——期限・対象・尺度・決着条件——の有無を置く。予測の中身が正しいかどうかとは切り離して記述する。**四要件は良し悪しの尺度ではない。** 期限のない直観にも価値はある。四要件が記述しているのは、**その予測に、後から誰が答えを出せるか**である。

**帰結層**に置くのは二つだけ。**発言者本人が後から自分の予測について述べた言葉**と、**一次資料に記載された事実**である。本人が何も言っていなければ、この層は空欄になる。**空欄は空欄のまま残す。**

Future of Life Instituteの書簡について、本書は「停止は実現しなかった」と書かない。書くのは、FLI自身が1年後に `Over the last 12 months developers of the most advanced systems have revealed beyond all doubt that their primary commitment is to speed and their own competitive advantage.` と書いた、という事実である。**判定は読者がする。本書は判定できる形に並べる。**

### 決着前記録

この台帳には、もう一つの列がある。**その行が登録された時点で、予測の帰結はすでに出ていたか、まだ出ていなかったか。**

後から振り返って「あの予測は外れた」と書くことは、誰でもできる。答えを知ってから書いた文章に、予測としての価値はない。**価値があるのは、答えが出る前に「この予測はここにある。期限はここだ。答えが出たら追記する」と書き留めた記録である。**

そのために本書は、**予測の登録と帰結の追記を別のコミットで行い、すべてのコミットにPGP署名を付す。** 登録のコミットが2026年9月であり、帰結のコミットが2027年1月以降であることは、GitHub上で誰でも確認できる。

**第1版の8行のうち、決着前は3行しかない。** 起点が2023年3月で、初版が2026年9月だからである。残り5行は帰結が出た後に登録されており、本書はそれを「決着後」と記して隠さない。**隠せば、本書は後から振り返って書いた本になる。**

### 第1版の8行が示していること

四要件をすべて明示している行は**2行**で、いずれも予測ではなく**要求**である（停止せよ、合意せよ）。要求は、何を・いつまでに・誰が・どうすれば達成かを述べなければ要求として成立しないため、四要件が自然に揃う。**予測として書かれた6行のうち、四要件をすべて明示したものはない。** これは記録者の判定ではなく、表の○×を数えた結果である。

したがって、**第三者が期限到来時に当否を確定できるのは2行だけであり、残り6行の帰結は発言者本人が何を言うかに依存する。**

本人の事後評価が記録されているのは5行。そこには、一人の発言者が同じ対象について**修正**（期限を動かす）・**判定**（一行の帰結を閉じる）・**採点**（複数行をまとめて閉じる）の三つを使い分けた記録が含まれている。

**読者が持ち帰れるもの**は、行の数ではない。予測を目にしたときに**四つの問いを当てる習慣**である。いつまでか。何についてか。どれくらいか。何が起きたらその通りになったと言えるか。四つとも揃っていれば誰でも答えを確認でき、揃っていなければ、答えを出せるのは発言者本人だけである。

なお本書は、記録できなかったものを終章で列挙する。期限のない予測の当否、非公開の予測、一次資料に日付のない発言、2023年3月22日より前の予測、発言の意図と動機、そして**予測が世界に与えた影響**。**本書が記録するのは、何が言われ、何が起きたかであって、言われたことが起きたことの原因だったかではない。**

---

## 📊 台帳データ

台帳は**日本語版・英語版で1本**である。発言層（逐語引用・直前と直後の一文）は原文の言語のまま両版で同一であり、形式層と帰結層の記述だけが日英の両方の列を持つ。

| ファイル | 位置づけ | 内容 |
| --- | --- | --- |
| [registry.json](./data/registry.json) | **正本** | 列定義と運用規則を先頭に含む。列ラベルは日英の両方を持つ |
| [registry.csv](./data/registry.csv) | 派生 | 表計算ソフトで開ける形式（UTF-8 BOM付き・38列） |

**本文の表と2ファイルは、同じコミットで更新される。** どちらか一方だけが新しい状態は、本書の運用上、存在しない。読者は本文を読まずに `data/registry.csv` だけを開いてもよい。

---

## 📄 ドキュメント

| ファイル | 言語 | 内容 |
| --- | --- | --- |
| [the-ai-forecast-registry_JP.md](./docs/jp/the-ai-forecast-registry_JP.md) | 🇯🇵 日本語 | 本文（日本語版） |
| [the-ai-forecast-registry_EN.md](./docs/en/the-ai-forecast-registry_EN.md) | 🇺🇸 English | 本文（英語版） |

---

## 🔄 更新履歴

本書は**追記専用**のOSS書籍である。一度記録した行は、削除も書き換えもしない。誤りが見つかった場合は、訂正を新しい行として追記し、元の行はそのまま残す。

**本書の改訂周期は、著者の都合ではなく期限の到来に同期する。** 予測は出続け、期限は次々に到来する。台帳は追記され続ける。

**次の検証点は2026年12月31日である。** 第1版の決着前3行のうち最初に期限が来るのが、Global Call for AI Red Linesの「2026年末までの国際合意」である。その日が過ぎたとき、帰結の行が登録とは別のコミットで追記されるかどうか。**それが、本書が台帳であるか、8行の回顧記事であるかを最初に分ける。**

| 版 | 日付 | 内容 |
| --- | --- | --- |
| **v1.0** | 2026-09-14 | 初版公開（8行／決着後5・決着前3／一次7・二次1） |

---

## 📑 目次

- **序章:** 2023年3月22日、6か月が要求された
- **第1章:** 台帳の読み方 ── 三層と四要件
- **第2章:** 起点 ── 帰結まで揃った最初の行
- **第3章:** 決着できる形と、できない形
- **第4章:** 台帳
- **第5章:** 自分を採点した者
- **第6章:** 修正の記録
- **第7章:** 先行する記録 ── Brooks・Marcus・Metaculus
- **第8章:** 読者がこの台帳でできること
- **終章:** 台帳に刻めないもの

---

## 🔗 Related Projects

本書は、以下のOSSプロジェクトと相互に接続されている。

| プロジェクト | 概要 | リンク |
| --- | --- | --- |
| **The China AI Registry**           | 中国のAI産業を当局の登録名簿988件を母集団として読む。名簿シリーズ第1弾 | [GitHub](https://github.com/Leading-AI-IO/the-china-ai-registry)          |
| **The Silence of Intelligence**     | Anthropic CEO ダリオ・アモディの思想を体系化。産業構造の解剖シリーズ第2弾 | [GitHub](https://github.com/Leading-AI-IO/the-silence-of-intelligence)    |
| **US-China AI Competition**         | 米中AI競争の多層構造。決めているのは強さではなく条件である | [GitHub](https://github.com/Leading-AI-IO/us-china-ai-competition)        |
| **Frontier-Grade Open Weights**     | フロンティア級のオープンウェイトモデルは、開かれたのか | [GitHub](https://github.com/Leading-AI-IO/frontier-grade-open-weights)    |
| **The Anatomy of Anthropic**        | Anthropicの戦略・製品・研究・安全性を包括的に解剖 | [GitHub](https://github.com/Leading-AI-IO/anatomy-of-anthropic)           |
| **The Growth Engine of Anthropic**  | Anthropicの1兆ドル到達の構造解剖 | [GitHub](https://github.com/Leading-AI-IO/the-growth-engine-of-anthropic) |
| **The Palantir Impact**             | Palantir Foundryのオントロジー戦略を解剖。産業構造の解剖シリーズ第1弾 | [GitHub](https://github.com/Leading-AI-IO/palantir-ontology-strategy)     |
| **The AI Strategist**               | AIストラテジストという職業を定義し、BTC交差点で戦うための実践的フレームワーク | [GitHub](https://github.com/Leading-AI-IO/the-ai-strategist)              |
| **Depth & Velocity**                | 生成AI時代の新規事業開発方法論 | [GitHub](https://github.com/Leading-AI-IO/depth-and-velocity)             |
| **The 10:80:10 Principle**          | 人とAIの共創黄金比「10:80:10」の法則——AI時代の思考のOS | [GitHub](https://github.com/Leading-AI-IO/the-10-80-10-principle)         |
| **What They Won't Teach You**       | AIに有利な世代が教えない、AIの使い方と"思考のOS" | [GitHub](https://github.com/Leading-AI-IO/what-they-wont-teach-you)       |
| **The Edge of Intelligence**        | AIがあなたのデバイスで動く時代：クラウドの終わりと、エッジの始まり | [GitHub](https://github.com/Leading-AI-IO/edge-ai-intelligence)           |
| **The Redesign of Design Strategy** | デザイン戦略の再定義。IDEO崩壊の構造分析を含む | [GitHub](https://github.com/Leading-AI-IO/design-strategy-in-the-ai-era)  |
| **The Orchestrator**                | AI時代に最も希少な人材像「AIオーケストレーター」を定義 | [GitHub](https://github.com/Leading-AI-IO/the-orchestrator-in-the-ai-era) |
| **Advertising, Redesigned**         | AI時代の広告の未来を、7社の戦略と構造分析から描くOSS書籍 | [GitHub](https://github.com/Leading-AI-IO/advertising-redesigned)         |
| **The AI Organization**             | AI導入が失敗する本質は技術ではなく組織にある。AI時代の組織論 | [GitHub](https://github.com/Leading-AI-IO/the-ai-organization)            |
| **The Structural Shift from SaaS**  | SaaSからService-as-a-Softwareへの構造的転換。Next SaaS ビジネスモデル | [GitHub](https://github.com/Leading-AI-IO/saas-is-dead-the-next-ai-business-model) |
| **A Trillion Dollars and a Firebomb** | 1兆ドルと火炎瓶。AI時代の同時加速する現実 | [GitHub](https://github.com/Leading-AI-IO/a-trillion-and-a-firebomb)      |
| **The End of the Attention Economy** | アテンション・エコノミーの終わり。次世代SNSの在り方とは？ | [GitHub](https://github.com/Leading-AI-IO/the-attention-economy-is-over)  |
| **The Agentic Commerce Economy**    | AIエージェントが購買を代行する時代、広告モデルの構造的変化 | [GitHub](https://github.com/Leading-AI-IO/agentic-commerce-economy)       |
| **Will AI Break the Planet**        | 数十兆円のインフラ投資と、地球温暖化の「不可逆ライン」 | [GitHub](https://github.com/Leading-AI-IO/will-ai-break-the-planet)       |
| **The Forward Deployed Shift**      | 成果実装 ── FDEが示す、AIで「作る」が終わった世界の価値のありか | [GitHub](https://github.com/Leading-AI-IO/the-forward-deployed-shift)     |
| **Earned AI Model Optionality**     | AIモデルは選べる。選べるのは、選べるようにした企業だけだ | [GitHub](https://github.com/Leading-AI-IO/earned-ai-model-optionality)    |

---

## 👤 著者

**Satoshi Yamauchi** (山内 怜史)

* **AI Strategist & Business Designer at Sun Asterisk Inc.**

* **Founder / AI Strategist at [Leading.AI](https://www.leading-ai.io/)**

* 15年以上にわたりBusiness・Technology・Creativeの3領域を越境。フューチャーアーキテクトでITコンサルタントとして40案件のPL/PMを推進後、リクルートで事業戦略・新規事業開発に従事。Sun Asteriskでビジネスデザイナー兼AIストラテジストとして、新規事業×生成AIの方法論「Depth & Velocity」を体系化。

* This project is part of the research by Leading.AI.

* [📒 Read my insights on Note](https://note.com/satoshi_yamauchi)

* [🌐 Visit Leading.AI Official Website](https://www.leading-ai.io/)

---

## 🤝 Contributing

**本書は Pull Request を受け付けない。** 台帳に書くのは著者一人であり、これは本書の設計の一部である。四要件の判定、決着前／後の区分、帰結層に判定を書かないという制約は、書き手が増えるほど揺れる。揺れた台帳は、検証に使えない。**書き手が一人であること、検証者が多いこと。この二つが揃っているとき、台帳は信頼に値する記録になる。**

Issues は歓迎する。受け付けるのは次の二種である。

**① 誤りの指摘。** 逐語引用が一次資料と一致しない。日付が違う。URLが到達しない。四要件の判定が逐語と合っていない。著者は一次資料に照らして確認し、誤りであれば訂正の行を追記する。**元の行は消さない。** 指摘した方の名は、訂正の行の補足欄に記す。

**② 一次資料の所在。** 本書が「未到達」「未取得」「未収載」と記している欄について、一次資料のURLをご存知の方からの情報提供を歓迎する。著者が到達し、確認のうえで行を起こすか欄を埋める。**収載基準を満たすものは例外なく載せる。**

帰結層に判定（「この予測は外れた」等）が書かれたIssueは、その部分を除いて受け付ける。**立場による選別はしない。** 危険を訴えた予測も、安全を訴えた予測も、能力の到来を否定した予測も、同じ基準で扱う。提案者の立場も問わない。

とくに、本書が第1版で一次到達できていない以下について、情報提供を歓迎する。

- AI Futures Project「AI 2027」本体（`ai-2027.com`）およびDaniel Kokotajlo本人による中央値更新の一次投稿
- AI Futures Projectによる2025年6月の定量批判への応答（超人的コーダー到達の中央値・確率質量の更新を含むとされるもの）
- Gary Marcus「Six (or seven) predictions for AI 2026 from a Generative AI realist」（2026年1月）の完全URL
- Gary MarcusのWIRED寄稿（AIバブルが2025年に崩壊すると予測したもの）
- 2023年3月の公開書簡に反対した Yann LeCun・Andrew Ng の対話の一次記録、および Sam Altman の当該発言の一次所在
- Metaculus のAI関連の個別の問い（解決基準の文言と解決済みの結果）
- AI Impacts 研究者調査（2016／2022／2023）の一次ページ

---

## 📝 License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).<br>
© 2026 Satoshi Yamauchi / [Leading AI](https://www.leading-ai.io/) — Licensed under CC BY 4.0
