# The AI Forecast Registry

"A forecast becomes a record only if it was written down before anyone knew the answer."

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Language](https://img.shields.io/badge/Language-Japanese%20%7C%20English-blue)](docs/)
[![Rows](https://img.shields.io/badge/Rows-8-informational)](data/registry.csv)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--09--14-brightgreen)](https://github.com/Leading-AI-IO/the-ai-forecast-registry/releases)

<p align="left">
  <img src="./assets/ogp_design.png" width="80%">
</p>

*Read this in other languages: [日本語](README.md)*

---

> **Definition**
>
> **This registry**, by Satoshi Yamauchi (山内怜史), AI Strategist, records
> public forecasts about AI with verbatim text, dates and primary URLs, and
> fills their outcomes using only the forecaster's own later words. It begins on
> 22 March 2023 with the Future of Life Institute's open letter "Pause Giant AI
> Experiments." Each row separates three layers. The **statement layer** holds
> the words in their original language, with the sentence before and after. The
> **form layer** describes the presence or absence of a deadline, a subject, a
> magnitude and a resolution condition — independently of whether the forecast
> proves true. The **outcome layer** holds only two things: what the forecaster
> said afterwards about their own forecast, and what a primary source states as
> fact. **No verdict by the recorder — "correct," "wrong" — appears anywhere in
> this book.** Registration and outcome are recorded as separate signed commits,
> so that **a third party can verify a forecast was recorded before its outcome
> was known.** Forecasts warning of danger, forecasts arguing safety, and
> forecasts denying that a capability is near are all admitted on identical
> criteria. Its central claim: **a forecast becomes a record that can be
> consulted later only if it was in a shape that could be settled, and was
> inscribed before it was.**
>
> **Governance**: The author is the sole writer. Being published in the open and
> being writable by anyone are different things. Raising a row, appending an
> outcome and issuing a correction are all done by the author, and every commit
> carries the author's signature. What readers do is verify the registry, report
> errors, and point to the location of primary sources. **Anything meeting the
> admission criteria is admitted without exception. There is no editorial
> discretion in admission — only an order of verification.**
>
> *Author & full catalog: [github.com/Leading-AI-IO](https://github.com/Leading-AI-IO)*

---

## 📖 Overview

Forecasts about AI appear weekly. "It will surpass humans in 2027." "Half of all jobs will be gone by 2030." "The bubble bursts next year." "This approach is a dead end." The speakers carry weight, the coverage is loud, and within months nobody remembers.

**Being forgotten is not the problem. The problem is that when a forecast is forgotten, no record exists of whether it proved right, proved wrong, or was ever in a shape where right and wrong could be determined at all.**

Compare two statements. "AI will become a serious danger to humanity." And: "Governments should reach an international agreement on AI by the end of 2026." The first never says how long one must wait for an answer. The second has a deadline: once 31 December 2026 has passed, anyone can check. **The difference is not in the quality of the content. It is a difference of form.**

This book is a registry that records forecasts about AI from the standpoint of that form.

### Three layers

**The statement layer** holds who said what, when and where — in the original language, unaltered, with the sentence before and after, the primary URL and the date of retrieval. **No word of the recorder enters it.**

**The form layer** holds the presence or absence of the Four Requisites: deadline, subject, magnitude, resolution condition. **The requisites are not a measure of quality.** An intuition without a deadline can still be valuable. What they describe is **who, afterwards, can produce an answer.**

**The outcome layer** holds only two things: **what the forecaster said afterwards about their own forecast**, and **what a primary source states as fact**. If the forecaster said nothing, the layer is empty. **An empty layer stays empty.**

Of the Future of Life Institute letter, this book does not write "the pause did not happen." It writes that FLI itself, one year later, wrote: `Over the last 12 months developers of the most advanced systems have revealed beyond all doubt that their primary commitment is to speed and their own competitive advantage.` **The verdict belongs to the reader. This book arranges things so that a verdict is possible.**

### Pre-resolution recording

Each row carries one further field: **at the moment the row entered this registry, had the outcome already been settled?**

Anyone can write, after the fact, that a forecast failed. Writing produced after the answer is known has no forecasting value. **What has value is a record written before the answer arrived** — "this forecast is here; its deadline is here; the outcome will be appended when it comes."

To that end, **registration and outcome are separate commits, and every commit carries a PGP signature.** That the registration commit is dated September 2026 and the outcome commit January 2027 or later is something anyone can verify on GitHub.

**Of the eight rows in the first edition, only three are pre-resolution.** The registry begins in March 2023 and the first edition appears in September 2026; the other five were registered after their outcomes were known, and are marked "post-resolution." **This is not concealed. Concealed, the book would be a work of hindsight.**

### What the first eight rows show

Two rows state all four requisites explicitly, and **both are demands rather than forecasts** (pause; reach an agreement). A demand must state what, by when, by whom and on what terms it is satisfied, or it is not a demand — so the requisites assemble themselves. **Of the six rows written as forecasts, none states all four.** That is not a verdict by the recorder; it is the result of counting marks in a table.

It follows that **only two rows can be settled by a third party when their deadlines pass. The outcomes of the other six depend on what their authors say.**

Five rows carry an assessment by their author. Among them is a record of one forecaster using three different treatments on the same subject: **revision** (moving a deadline), **adjudication** (closing one row), and **scoring** (closing several at once).

**What a reader carries away** is not a number of rows. It is the habit of applying **four questions** to any forecast they meet. By when? About what? How much? What would have to happen for it to be called correct? With all four, anyone can check. Without them, only the speaker can answer.

The epilogue lists what could not be recorded: the truth of forecasts without deadlines, forecasts never made public, statements whose primary source carries no date, forecasts made before 22 March 2023, intent and motive, and **the effect a forecast had on the world**. **What this book records is what was said and what happened — not whether what was said caused what happened.**

---

## 📊 Registry data

**There is one registry, shared by the Japanese and English editions.** The statement layer — verbatim quotation and the sentences before and after — is held in the original language and is identical in both. Only the form and outcome layers carry separate Japanese and English columns.

| File | Status | Contents |
| --- | --- | --- |
| [registry.json](./data/registry.json) | **Canonical** | Column definitions and operating rules precede the rows. Every column label carries both a Japanese and an English form |
| [registry.csv](./data/registry.csv) | Derived | Openable in a spreadsheet (UTF-8 with BOM, 38 columns) |

**The prose tables and the two files are updated in the same commit.** A state in which one is newer than the other does not exist under this book's operating rules. A reader may open `data/registry.csv` without reading the prose at all.

---

## 📄 Documents

| File | Language | Contents |
| --- | --- | --- |
| [the-ai-forecast-registry_JP.md](./docs/jp/the-ai-forecast-registry_JP.md) | 🇯🇵 Japanese | Full text (Japanese edition) |
| [the-ai-forecast-registry_EN.md](./docs/en/the-ai-forecast-registry_EN.md) | 🇺🇸 English | Full text (English edition) |

---

## 🔄 Revision history

This is an **append-only** open-source book. A row, once recorded, is never deleted and never rewritten. When an error is found, the correction is appended as a new row and the original stays where it is.

**The revision cycle is set by the arrival of deadlines, not by the author's convenience.** Forecasts keep appearing; deadlines keep arriving; the registry keeps growing.

**The next test is 31 December 2026.** Of the three pre-resolution rows in the first edition, the first deadline to arrive is the Global Call for AI Red Lines' "international agreement by the end of 2026." When that day has passed, will an outcome row be appended in a commit separate from the registration? **That is the first thing that will separate this book as a registry from this book as eight rows of hindsight.**

| Version | Date | Contents |
| --- | --- | --- |
| **v1.0** | 2026-09-14 | First edition (8 rows / 5 post-resolution, 3 pre-resolution / 7 primary, 1 secondary) |

---

## 📑 Table of contents

- **Prologue:** On 22 March 2023, six months were demanded
- **Chapter 1:** How to read the registry — three layers and four requisites
- **Chapter 2:** The origin — the first row with every layer filled
- **Chapter 3:** Shapes that can be settled, and shapes that cannot
- **Chapter 4:** The registry
- **Chapter 5:** Those who scored themselves
- **Chapter 6:** The record of revisions
- **Chapter 7:** Records that came before — Brooks, Marcus, Metaculus
- **Chapter 8:** What a reader can do with this registry
- **Epilogue:** What cannot be inscribed

---

## 🔗 Related Projects

This book is cross-connected with the following open-source projects.

| Project | Summary | Link |
| --- | --- | --- |
| **The China AI Registry**           | Reading China's AI industry from the authorities' filing registry of 988 services. First in the registry series | [GitHub](https://github.com/Leading-AI-IO/the-china-ai-registry)          |
| **The Silence of Intelligence**     | A systematisation of the thinking of Anthropic CEO Dario Amodei | [GitHub](https://github.com/Leading-AI-IO/the-silence-of-intelligence)    |
| **US-China AI Competition**         | The layered structure of US-China AI competition: conditions decide it, not strength | [GitHub](https://github.com/Leading-AI-IO/us-china-ai-competition)        |
| **Frontier-Grade Open Weights**     | Frontier-grade open-weight models: were they really opened? | [GitHub](https://github.com/Leading-AI-IO/frontier-grade-open-weights)    |
| **The Anatomy of Anthropic**        | A comprehensive dissection of Anthropic's strategy, products, research and safety | [GitHub](https://github.com/Leading-AI-IO/anatomy-of-anthropic)           |
| **The Growth Engine of Anthropic**  | The structure behind Anthropic's path to a trillion dollars | [GitHub](https://github.com/Leading-AI-IO/the-growth-engine-of-anthropic) |
| **The Palantir Impact**             | A dissection of Palantir Foundry's ontology strategy | [GitHub](https://github.com/Leading-AI-IO/palantir-ontology-strategy)     |
| **The AI Strategist**               | Defining the AI Strategist as a profession, and a practical framework for the BTC intersection | [GitHub](https://github.com/Leading-AI-IO/the-ai-strategist)              |
| **Depth & Velocity**                | A methodology for new business development in the generative-AI era | [GitHub](https://github.com/Leading-AI-IO/depth-and-velocity)             |
| **The 10:80:10 Principle**          | The golden ratio of human-AI collaboration: an operating system for thinking | [GitHub](https://github.com/Leading-AI-IO/the-10-80-10-principle)         |
| **What They Won't Teach You**       | What the AI-advantaged generation won't teach you about using AI | [GitHub](https://github.com/Leading-AI-IO/what-they-wont-teach-you)       |
| **The Edge of Intelligence**        | When AI runs on your device: the end of cloud and the beginning of edge | [GitHub](https://github.com/Leading-AI-IO/edge-ai-intelligence)           |
| **The Redesign of Design Strategy** | Redefining design strategy, including a structural analysis of IDEO's collapse | [GitHub](https://github.com/Leading-AI-IO/design-strategy-in-the-ai-era)  |
| **The Orchestrator**                | Defining the scarcest role of the AI era: the AI orchestrator | [GitHub](https://github.com/Leading-AI-IO/the-orchestrator-in-the-ai-era) |
| **Advertising, Redesigned**         | The future of advertising in the AI era, drawn from seven companies' strategies | [GitHub](https://github.com/Leading-AI-IO/advertising-redesigned)         |
| **The AI Organization**             | AI adoption fails for organisational, not technical, reasons | [GitHub](https://github.com/Leading-AI-IO/the-ai-organization)            |
| **The Structural Shift from SaaS**  | From SaaS to Service-as-a-Software: the next AI business model | [GitHub](https://github.com/Leading-AI-IO/saas-is-dead-the-next-ai-business-model) |
| **A Trillion Dollars and a Firebomb** | A trillion dollars and a firebomb: realities accelerating in parallel | [GitHub](https://github.com/Leading-AI-IO/a-trillion-and-a-firebomb)      |
| **The End of the Attention Economy** | The end of the attention economy, and what comes after | [GitHub](https://github.com/Leading-AI-IO/the-attention-economy-is-over)  |
| **The Agentic Commerce Economy**    | When AI agents buy on your behalf: the structural change in advertising | [GitHub](https://github.com/Leading-AI-IO/agentic-commerce-economy)       |
| **Will AI Break the Planet**        | Tens of trillions in infrastructure investment and the irreversible line | [GitHub](https://github.com/Leading-AI-IO/will-ai-break-the-planet)       |
| **The Forward Deployed Shift**      | Where value sits once AI has finished "building" | [GitHub](https://github.com/Leading-AI-IO/the-forward-deployed-shift)     |
| **Earned AI Model Optionality**     | You can choose your AI model — if you built the ability to choose | [GitHub](https://github.com/Leading-AI-IO/earned-ai-model-optionality)    |

---

## 👤 Author

**Satoshi Yamauchi** (山内 怜史)

* **AI Strategist & Business Designer at Sun Asterisk Inc.**

* **Founder / AI Strategist at [Leading.AI](https://www.leading-ai.io/)**

* More than fifteen years working across Business, Technology and Creative. After leading forty engagements as PL/PM as an IT consultant at Future Architect, he worked on business strategy and new business development at Recruit. At Sun Asterisk, as a business designer and AI strategist, he systematised "Depth & Velocity," a methodology for new business development with generative AI.

* This project is part of the research by Leading.AI.

* [📒 Read my insights on Note](https://note.com/satoshi_yamauchi)

* [🌐 Visit Leading.AI Official Website](https://www.leading-ai.io/)

---

## 🤝 Contributing

**This book does not accept Pull Requests.** The author is the sole writer, and that is part of the design. The judgement of the four requisites, the pre- and post-resolution marking, and the prohibition on verdicts in the outcome layer all waver as writers multiply. A wavering registry cannot be used for verification. **One writer, and many verifiers. When those two hold together, a registry becomes a record worth trusting.**

Issues are welcome. Two kinds are accepted.

**1. Reports of error.** A quotation that does not match the primary source. A wrong date. A URL that does not resolve. A requisite marking inconsistent with the quoted text. The author checks against the primary source and, if it is an error, appends a correcting row. **The original row is not deleted.** The name of the reporter is recorded in the notes field of the correcting row.

**2. The location of a primary source.** For fields marked "not reached," "not retrieved" or "not yet recorded," information from anyone who knows the URL of a primary source is welcome. The author reaches it, verifies it, and raises a row or fills the field. **Anything meeting the admission criteria is admitted without exception.**

An Issue containing a verdict in the outcome layer ("this forecast was wrong," and the like) is accepted with that part set aside. **No selection by stance.** Forecasts warning of danger, arguing safety, and denying that a capability is near are treated on identical criteria, and the stance of the person reporting is not asked either.

In particular, information is welcome on the following, which this book has not reached in primary form as of the first edition.

- The AI Futures Project's "AI 2027" itself (`ai-2027.com`), and Daniel Kokotajlo's own post updating his median
- The AI Futures Project's response to the quantitative critique of June 2025, reported to include updated medians and probability mass for the arrival of the superhuman coder
- The complete URL of Gary Marcus, "Six (or seven) predictions for AI 2026 from a Generative AI realist" (January 2026)
- Gary Marcus's WIRED essay forecasting that the AI bubble would collapse in 2025
- The primary record of the Yann LeCun / Andrew Ng conversation opposing the March 2023 open letter, and the primary location of Sam Altman's remarks on it
- Individual Metaculus questions on AI (the wording of their resolution criteria and their resolved outcomes)
- The primary pages of the AI Impacts expert surveys (2016 / 2022 / 2023)

---

## 📝 License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).<br>
© 2026 Satoshi Yamauchi / [Leading AI](https://www.leading-ai.io/) — Licensed under CC BY 4.0
