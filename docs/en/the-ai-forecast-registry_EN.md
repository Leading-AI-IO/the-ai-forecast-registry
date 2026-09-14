# The AI Forecast Registry

> **"A forecast becomes a record only if it was written down before anyone knew the answer."**

---

# Prologue: On 22 March 2023, six months were demanded

On 22 March 2023, an open letter appeared.

It was written by the Future of Life Institute (FLI), a non-profit organisation based in the United States. Its title was "Pause Giant AI Experiments." Its demand fits in a single sentence.

> Therefore, we call on all AI labs to immediately pause for at least 6 months the training of AI systems more powerful than GPT-4.

GPT-4 had been released eight days before the letter. "Training" is the process of giving an AI its capabilities by having it process vast quantities of text; stop that process and no stronger system comes into being. The letter asked developers everywhere to stop it simultaneously, for six months.

More than thirty thousand people signed. Leading AI researchers, company executives, well-known authors. Newspapers around the world put it in their headlines.

There is one question. **Did those six months come?**

This book does not answer it. The answer was written by FLI itself, exactly one year later, on 22 March 2024.

> Over the last 12 months developers of the most advanced systems have revealed beyond all doubt that their primary commitment is to speed and their own competitive advantage.

The party that made the demand wrote, a year later, in its own words, that the demand had not been met. This is the shape of what this registry records. Someone forecasts something, or demands something; time passes; and **what did that same person say afterwards?** Between those two moments, no verdict of the recorder ever intervenes.

---

## Why this registry exists

Forecasts about AI appear weekly.

"It will surpass humans in 2027." "Half of all jobs will be gone by 2030." "The bubble bursts next year." "This approach is a dead end." The speakers carry weight, the coverage is loud, and within months nobody remembers — because the next forecast has arrived.

That forecasts are forgotten is not itself the problem. The problem is that **when a forecast is forgotten, no record exists of whether it proved right, proved wrong, or was ever in a shape where right and wrong could be determined at all.**

Consider two statements.

- "AI will become a serious danger to humanity."
- "Governments should reach an international agreement on AI by the end of 2026."

The first does not say how long one must wait before calling it right or wrong. The second has a deadline. Once 31 December 2026 has passed, anyone can check whether such an agreement exists.

The difference is not in the quality of the content. It is a difference **of form**. And that difference is decisive when the time comes to look back. A forecast without a deadline can always be met with "it is too early to say." A forecast with a deadline will, eventually, have an answer.

This book is a registry that records forecasts about AI from the standpoint of that form.

## What this book gives the reader

Three things.

**First, rows.** Who said what, and when. The words are recorded in their original language, with the sentence before and the sentence after, and the URL of the source. Translations, where provided, are kept in a separate field and are never treated as quotations.

**Second, form.** Does the forecast carry a deadline? What is it about? What magnitude does it assert? What would have to happen for it to be called correct? These four are described separately from whether the content is right. This book calls them **the Four Requisites**. They are defined in Chapter 1.

**Third, outcome.** But the outcomes this book writes are of two kinds only. **What the forecaster themselves said afterwards about their own forecast.** And **what a primary source states as fact.** A recorder's verdict — "correct," "wrong" — appears nowhere in this book.

That third constraint defines the character of the book.

Of the FLI letter, this book does not write "the pause did not happen." It writes that FLI itself, one year later, stated that developers' primary commitment had been to speed. Of Gary Marcus, a researcher who forecast in March 2024 that no groundbreaking GPT would appear that year, this book does not write "he was right." It writes that Marcus himself wrote, in January 2025: "Last March I predicted that it wouldn't arrive in 2024. It didn't."

The verdict belongs to the reader. This book arranges things so that a verdict is possible.

## How this registry is operated

This book has a property most books do not. **It never finishes.** Forecasts keep appearing; deadlines keep arriving; the registry keeps growing.

For that reason the following rules apply.

**Append-only.** A row, once recorded, is never deleted and never rewritten. When an error is found, the correction is appended as a new row and the original stays where it is.

**Registration and outcome are separate records.** This book is published on GitHub, where every change to a document is recorded as a "commit" that anyone can inspect afterwards. By separating the commit that registers a forecast from the commit that appends its outcome, **the fact that the forecast was recorded before the outcome was known** becomes verifiable by a third party.

**Every commit carries a signature.** A PGP signature establishes, in a form that cannot be forged after the fact, who made each change.

**Every row is marked pre- or post-resolution.** Was the outcome already settled at the moment the row entered this registry, or not? The registry begins in March 2023; the first edition appears in September 2026. Many early rows are therefore recorded after their outcomes were known. **This is not concealed.** Rows written in retrospect are marked "post-resolution"; rows registered after publication and still awaiting their outcome are marked "pre-resolution."

Without that distinction, this book would be indistinguishable from a book written in hindsight. Anyone can write in hindsight. The value of this registry lies in **the accumulation, over time, of rows that were inscribed before the outcome was known.**

**The author is the only person who writes to this registry.** The book is published in the open, but being public and being writable by anyone are different things. Raising a row, appending an outcome, issuing a correction — all are done by the author alone. Every commit carries the author's signature, and unsigned changes never enter the history. What readers can do is verify the registry, report errors, and point to the location of primary sources. Whether and when a source becomes a row is decided by the author after direct verification. **The discipline of this registry is preserved by there being a single writer.**

**It is also published in machine-readable form.** The registry is available as `data/registry.json` (canonical) and `data/registry.csv` (derived) in the same repository. This book's sibling volume, *The China AI Registry*, examined the filing list of generative-AI services published by the Chinese authorities and observed that the list was comprehensive but not machine-readable. This book turns that observation on itself, and publishes in a form readers can recount for themselves.

## What is in scope, and what is not

**In scope: public statements.** Only material whose primary location can be shown — a document, a recorded talk, congressional testimony, a signed article, a post by the speaker. Where third-party reporting is the only location available, the row is recorded and marked secondary.

**In scope: statements about the future state of AI.** Capability, danger, adoption, regulation, economic effect, rate of development — anything unsettled at the moment of speaking.

**No selection by stance.** Forecasts warning of danger, forecasts arguing safety, and forecasts arguing that a capability is nowhere near arriving are all admitted on identical criteria. A registry that admits only one side is an argument. This book is not an argument.

**Out of scope: forecasts made before 22 March 2023.** This is a design choice, and it has a cost. Important forecasts exist before that date. But without an origin the registry cannot begin, and this book chose that letter. The reason: the letter carried **a deadline (six months), a subject (training of systems more powerful than GPT-4), a magnitude (all labs), and a resolution condition (whether training stopped)** — all four requisites. And the party that made it wrote its outcome one year later. As a first row, no better shape exists.

**Out of scope: adjudicating forecasts that have no deadline.** A statement of the form "the probability that AI causes human extinction is 10 to 20 per cent" is recorded. Whether it proved right cannot be determined within the period this registry covers. This book records it as a statement lacking a resolution condition, and writes nothing further.

## On sources

Every row requires three things.

1. **A verbatim quotation**, in the original language. Summaries and paraphrases are not quotations
2. **A date**, to the day. Where the primary source gives no day, that fact is noted and the date from secondary reporting is given alongside
3. **A primary URL**, with the page title or opening line as it stood at the time of retrieval

Figures that change over time — signatory counts, forecasting-market values — are recorded as **the value at the moment of retrieval**, with the retrieval date attached. A later retrieval does not overwrite the row; it adds a new one.

The sentence before and the sentence after each quotation are recorded wherever possible. A single sentence lifted out of context can change meaning.

All sources in this book were reached directly by the author on or before 14 September 2026. Where a source could not be reached, that is stated. **"It does not exist" is never written.**

### References

- Future of Life Institute, "Pause Giant AI Experiments: An Open Letter," 22 March 2023. https://futureoflife.org/open-letter/pause-giant-ai-experiments/
- Future of Life Institute, "The Pause Letter: One year later," 22 March 2024. https://futureoflife.org/ai/the-pause-letter-one-year-later/
- Future of Life Institute, "FAQs about FLI's Open Letter Calling for a Pause on Giant AI Experiments." https://futureoflife.org/ai/faqs-about-flis-open-letter-calling-for-a-pause-on-giant-ai-experiments/
- Gary Marcus, "AGI isn't coming in 2025, and GPT-5 probably isn't either," 9 January 2025. https://garymarcus.substack.com/p/agi-isnt-coming-in-2025-and-gpt-5
- Leading AI LLC, *The China AI Registry*, 2026. https://github.com/Leading-AI-IO/the-china-ai-registry

---

# Chapter 1: How to read the registry — three layers and four requisites

Once you can read a single row, you can read the rest of this book. That is what this chapter is for.

A row holds one forecast. Someone, on some day, said something about the future of AI. The words, the shape of the words, and what happened afterwards — these three sit in separate places within the row.

---

## A row has three layers

**The first layer is the statement itself.** Who, when, where, and in what words. This book records it in the original language, unaltered, with the sentence before and the sentence after. The source URL and the date of retrieval are given. **No word of the recorder enters this layer.** What it contains is the speaker's words and the fact of where those words are.

**The second layer is the form of the statement.** By when? About what? At what magnitude? What would have to happen for it to be called correct? These four are described separately from whether the content is right. The standard used here is called **the Four Requisites**, defined in the next section.

**The third layer is the outcome.** If the forecast carried a deadline, has that deadline passed? And **what did the forecaster say afterwards about their own forecast?** If they said nothing, the layer is empty. **An empty layer stays empty.** The recorder does not fill it on their behalf.

There is one reason for keeping the layers apart. **Mixed together, it becomes impossible to see where the speaker's words end and the recorder's interpretation begins.** Write "X forecast that Y would occur in 2027, but this was over-optimistic," and the first half is a fact while the second is an opinion. The reader has to separate them. This book separates them in advance.

## The Four Requisites

> **The Four Requisites**, proposed by Satoshi Yamauchi (山内 怜史), is a classification standard for AI forecasts by whether they are structurally judgeable: it records the presence or absence of a deadline, a subject, a magnitude, and a resolution condition, independently of whether the forecast proves true.
>
> **予測の四要件とは**、山内 怜史（Satoshi Yamauchi）が提唱している、AIをめぐる予測を判定可能な形式を備えているかで分類する基準である。期限・対象・尺度・決着条件の四つの有無を、予測の真偽とは独立に記述する。
>
> First published: September 2026, commit `4140d2de52ffceb1c1be9c55006cb7b48a35d9fd` of this repository

**Deadline.** By when? "By 2027," "this year," "within six months." A forecast with a deadline gets its answer when the day arrives. A forecast without one can always be deferred.

**Subject.** About what? "Training of systems more powerful than GPT-4," "an AI surpassing human intelligence," "the generative-AI bubble." A clear subject tells you where to look. The "AI" in "AI is dangerous" is too broad to fix what should be observed.

**Magnitude.** How much? "All labs," "with 70 per cent probability," "hundreds of billions of dollars." A magnitude lets you measure whether what occurred reached the size asserted. "A major impact" gives nothing to measure.

**Resolution condition.** What would have to happen for the forecast to be called correct? "Whether training stopped for six months." "Whether an international agreement was reached." Where the condition is explicit, a third party can adjudicate. Where it is absent, adjudication requires the forecaster's own interpretation.

A forecast carrying all four can be settled by anyone. A forecast carrying none cannot be settled by anyone. Between those poles lie many shapes.

### The requisites are not a measure of quality

One misunderstanding must be prevented here.

**A forecast carrying more requisites is not a "better" forecast, and one carrying fewer is not a "worse" one.** The requisites describe form, not worth.

Forecasts without deadlines have value. A researcher's intuition that "this direction is a dead end" carries neither deadline nor magnitude, yet can redirect a field. A statement of the form "the probability of human extinction from AI is 10 to 20 per cent" carries no resolution condition, yet directs attention. This book records them — while also recording, as a matter of form, that their truth cannot be determined within the period covered.

What the requisites describe is **whether a forecast was placed in a shape that can withstand later verification.** That is a separate matter from the forecaster's sincerity, and from the quality of the forecast.

### Reading three examples

Three statements, read through the requisites. All three appear in this registry.

**First.** 22 March 2023, Future of Life Institute.

> we call on all AI labs to immediately pause for at least 6 months the training of AI systems more powerful than GPT-4

Deadline — six months. Subject — training of AI systems more powerful than GPT-4. Magnitude — all AI labs. Resolution — whether training stopped. **All four present.** Six months later, anyone could check.

**Second.** 22 September 2025, Global Call for AI Red Lines.

> We urge governments to reach an international agreement on red lines for AI — ensuring they are operational, with robust enforcement mechanisms — by the end of 2026.

Deadline — end of 2026. Subject — an international agreement on red lines for AI. Magnitude — operational, with robust enforcement. Resolution — whether the agreement is reached. **All four present.** At the time this first edition is published, in September 2026, that deadline has not yet arrived.

**Third.** 31 March 2024, Gary Marcus.

> But will we see a mindblowing GPT this year? I doubt it.

Deadline — this year (2024). Subject — GPT, OpenAI's language model. Magnitude — "mindblowing." Resolution — **not stated.** What would have to appear to count as mindblowing is not written down.

This third row matters to the book. Deadline and subject are present; the magnitude is subjective and the resolution condition is absent. **No third party can therefore adjudicate this forecast.** Only Marcus can. And on 9 January 2025, he did.

> Last March I predicted that it wouldn't arrive in 2024. It didn't.

This book records that self-adjudication in the outcome layer. The recorder adjudicates nothing. **Forecasts short of the four requisites wait for their author.** That is why the outcome layer of this book is built around the forecaster's own later assessment.

## Pre-resolution and post-resolution

Each row carries one further field. **At the moment the row entered this registry, had the outcome already been settled?**

> **Pre-Resolution Recording**, proposed by Satoshi Yamauchi (山内 怜史), is the principle of registering a forecast with a tamper-evident timestamp before its outcome is settled, keeping the registration and the outcome as separate records so that entries written after the fact are structurally distinguishable.
>
> **決着前記録とは**、山内 怜史（Satoshi Yamauchi）が提唱している、予測を帰結が確定する前に改竄不能な時刻証明とともに登録する原則である。登録と帰結の追記を別の記録単位とし、事後に書かれた記録と構造的に区別する。
>
> First published: September 2026, commit `4140d2de52ffceb1c1be9c55006cb7b48a35d9fd` of this repository

Why the distinction is needed.

Anyone can write, after the fact, that a forecast failed. Writing produced after the answer is known has no forecasting value. **What has value is a record written before the answer arrived: "this forecast is here; its deadline is here; the outcome will be appended when it comes."** Such a record can afterwards serve as evidence of who said what.

The first edition of this book appears in September 2026; the registry begins in March 2023. Many of its rows are therefore registered after their outcomes were known. The outcome of the FLI letter was known more than two years before registration. This book marks that row "post-resolution." **It is not hidden.** Hidden, the book would be a work of hindsight.

The deadline of the Global Call for AI Red Lines, by contrast, is the end of 2026. At the time of the first edition it has not arrived. That row is marked "pre-resolution." When the deadline passes and the matter is settled, the fact will be appended to the outcome layer — **in a commit separate from the registration.** That the registration commit is dated September 2026 and the outcome commit January 2027 or later is something anyone can verify on GitHub.

As time passes, pre-resolution rows accumulate. Every forecast that appears after publication is registered before its resolution. **The value of this book is produced by that accumulation.** In the first edition, only three of eight rows are pre-resolution. That is what an honest beginning looks like; it is not a defect.

## What the recorder does not write

The outcome layer never contains:

- verdicts by the recorder — "correct," "wrong," "broadly right," "over-optimistic"
- assessments of importance by the recorder — "this forecast was influential," "this one was ignored"
- inferences about motive by the recorder — "at this point he presumably believed that…"

It contains only:

- whether the deadline has passed (a comparison of dates)
- what the forecaster said afterwards about their own forecast (verbatim, dated, sourced)
- what a primary source states about the subject of the forecast (verbatim, dated, sourced)

The constraint makes the book restrictive. There will be moments where something is plainly wrong and cannot be written as wrong. But relax the constraint once and the book stops being a registry and becomes an opinion. **An opinion is not read by those who hold a different one. A registry is used by them.** This book chooses the latter.

## The columns

| Layer | Column | Content |
|---|---|---|
| Identity | ID | Sequential number |
| Identity | Row name | Formal name. Fixed as "Speaker / subject and content of the forecast / date of statement," joined by slashes. The text refers to rows by ID and formal name together |
| Statement | Speaker | Individual or organisation, with affiliation |
| Statement | Date of statement | To the day. Where the primary source gives no day, that fact plus the date from secondary reporting |
| Statement | Medium | Document / talk / testimony / interview / the speaker's own post |
| Statement | Verbatim quotation | In the original language |
| Statement | Preceding and following sentence | For preservation of context |
| Statement | Primary URL and retrieval evidence | URL, plus the page title or opening line at retrieval, plus the retrieval date |
| Form | Deadline | Present / absent; if present, the date |
| Form | Subject | Present / absent; if present, what |
| Form | Magnitude | Present / absent; if present, what |
| Form | Resolution condition | Present / absent; if present, what |
| Outcome | Deadline status | Elapsed / not yet elapsed / no deadline |
| Outcome | Forecaster's own later assessment | Verbatim, dated, sourced. Empty if none |
| Outcome | Facts stated in primary sources | Verbatim, dated, sourced. Empty if none |
| Record | Pre- / post-resolution | Whether the outcome was settled at registration |
| Record | Registration commit | Hash of the commit that registered the row |

**Figures that change over time** are recorded with their retrieval date. A later retrieval adds a row rather than overwriting one.

These columns match `data/registry.json` and `data/registry.csv` exactly. The prose tables and the machine-readable files are updated in the same commit.

### References

- Future of Life Institute, "Pause Giant AI Experiments: An Open Letter," 22 March 2023. https://futureoflife.org/open-letter/pause-giant-ai-experiments/
- Global Call for AI Red Lines, launched September 2025. https://red-lines.ai/
- Gary Marcus, "When will the GenAI bubble burst?," 31 March 2024. https://garymarcus.substack.com/p/when-will-the-genai-bubble-burst
- Gary Marcus, "AGI isn't coming in 2025, and GPT-5 probably isn't either," 9 January 2025. https://garymarcus.substack.com/p/agi-isnt-coming-in-2025-and-gpt-5

---

# Chapter 2: The origin — the first row with every layer filled

Chapter 1 explained how to read a row. This chapter opens one.

The row is the first in the registry: the open letter of the Future of Life Institute, 22 March 2023. The prologue gave the reason for the choice. All four requisites are present, the deadline has passed, and the party that made the demand wrote the outcome. All three layers are full. As a worked example, no better row exists.

What follows opens the layers one at a time. When reading Chapter 4, the reader should know that every row there can be expanded into this shape.

---

## The statement layer

**Speaker.** Future of Life Institute (FLI), a non-profit organisation based in Massachusetts, United States.

**Date.** 22 March 2023. FLI itself cites the date in a later document as "Mar. 22, 2023."

**Medium.** An open letter, published on a website in a form that allowed anyone to add a signature.

**Verbatim quotation.**

> Therefore, we call on all AI labs to immediately pause for at least 6 months the training of AI systems more powerful than GPT-4.

**Preceding sentence.**

> We agree. That point is now.

What "We agree" agrees with lies in the sentence before that. The letter quotes a passage written by OpenAI itself — to the effect that at some point it may become important to seek independent review before beginning to train future systems — and agrees with it, adding that the point is now. **The letter's demand rests on words the demanded party had previously written about itself.**

**Following sentence.**

> This pause should be public and verifiable, and include all key actors.

The letter continues that the pause should be public, verifiable, and inclusive of all key actors, and that if such a pause cannot be enacted quickly, governments should step in and institute a moratorium.

**Signatories.** More than thirty thousand. This is FLI's own wording: its May 2023 newsletter refers to "over 30,000 other concerned individuals," and its one-year retrospective of March 2024 to "more than 30,000 individuals." This book records the figure as **FLI's own wording as retrieved on 14 September 2026.** Some third-party articles give a specific figure of 33,708; this book uses FLI's.

**Primary URL.** `https://futureoflife.org/open-letter/pause-giant-ai-experiments/`
**Retrieval evidence.** Page title "Pause Giant AI Experiments: An Open Letter - Future of Life Institute." Accessed 14 September 2026.

### The speaker's own narrowing of scope

After publication, FLI set up a separate page of frequently asked questions, narrowing the scope of the demand in its own words.

> We're calling for a pause on the training of models larger than GPT-4 for 6 months. This does not imply a pause or ban on all AI research and development or the use of systems that have already been placed in the market.

The same page states that the call addresses "a very small pool of actors who possess this capability." The demand was therefore directed not at AI development in general but at the few organisations then capable of training models beyond GPT-4.

This book records that narrowing as part of the statement layer. **When a speaker later clarifies the scope of their own statement, the clarification is part of the statement.** The recorder does not widen or narrow it on their behalf.

## The form layer

**Deadline.** Present. "At least 6 months." Counted from the letter's date, the earliest deadline is 22 September 2023.

**Subject.** Present. "The training of AI systems more powerful than GPT-4," further narrowed in the FAQ to "models larger than GPT-4."

**Magnitude.** Present. "All AI labs," which the FAQ supplements as "a very small pool of actors" — in practice a handful of organisations.

**Resolution condition.** Present. Whether training stopped. The letter itself asks for a pause that is "public and verifiable," making verifiability part of the demand.

**All four requisites present.** Few rows in this registry meet that description.

## The outcome layer

**Deadline status.** Elapsed, 22 September 2023.

**The forecaster's own later assessment.** Present. On 22 March 2024, FLI published "The Pause Letter: One year later."

> Over the last 12 months developers of the most advanced systems have revealed beyond all doubt that their primary commitment is to speed and their own competitive advantage.

The same piece contains this sentence:

> Even AI companies that take safety seriously have adopted the approach of aggressively experimenting until their experiments become manifestly dangerous, and only then considering a pause.

It closes by stating that safety and responsibility will have to be imposed from outside.

**Facts stated in primary sources.** As of the first edition, no primary source other than FLI's own piece has been admitted to this row's outcome layer. Official records from individual laboratories on whether training stopped will be appended after this book has reached them directly.

**Pre- / post-resolution.** **Post-resolution.** Registration occurred in September 2026; the deadline (September 2023) and the self-assessment (March 2024) both precede it.

**Registration commit.** To be filled at publication.

## What this row demonstrates

Nowhere above did the recorder write "the pause did not happen."

There was no need. **The party that demanded it wrote, one year later, in its own words,** that developers' primary commitment had been to speed. This book placed that sentence. The reader can read it and decide for themselves whether the pause occurred.

Had this book written "the pause was not realised," that would be a verdict by the recorder. FLI's sentence and such a verdict might point at the same thing. But **one is the speaker's word and the other is the recorder's.** The registry carries only the former. Blur that line and the reader must once again separate, within each row, what is fact and what is this book's opinion.

What the row demonstrates is one pattern by which a forecast carrying all four requisites reaches resolution. A deadline arrives. The author looks back. That looking-back becomes the record of the outcome. **The recorder has no part to play.**

## The other side becomes its own row

The letter drew objections from the moment it appeared. The researchers Yann LeCun and Andrew Ng published a conversation arguing that a six-month pause was a bad idea. Sam Altman, chief executive of OpenAI, was reported to have said the letter lacked technical nuance about where a pause was needed.

These are reactions to the letter and, at the same time, statements about the future of AI in their own right. Behind "we should not pause" lies a forecast: that no danger will arise without a pause, or that a pause would have no effect.

This book records such statements **as independent rows, not as annotations to this one.** As of the first edition they are not included, because the book has not reached their primary sources — the recording of the conversation, the speakers' own posts. Rows are not raised on third-party reporting alone.

If the registry appears at any moment to carry only one side, the cause is the order in which primary sources were reached, not the position of the recorder. That order is not concealed either.

## The row in full

| Column | Content |
|---|---|
| ID | 001 |
| Row name | Future of Life Institute / Call to pause training of AI systems more powerful than GPT-4 for six months / 2023-03-22 |
| Speaker | Future of Life Institute |
| Date of statement | 2023-03-22 |
| Medium | Open letter |
| Verbatim quotation | Therefore, we call on all AI labs to immediately pause for at least 6 months the training of AI systems more powerful than GPT-4. |
| Preceding sentence | We agree. That point is now. |
| Following sentence | This pause should be public and verifiable, and include all key actors. |
| Primary URL | https://futureoflife.org/open-letter/pause-giant-ai-experiments/ |
| Retrieval evidence | Pause Giant AI Experiments: An Open Letter - Future of Life Institute (accessed 2026-09-14) |
| Deadline | Yes (6 months / 2023-09-22) |
| Subject | Yes (training of AI systems more powerful than GPT-4) |
| Magnitude | Yes (all AI labs) |
| Resolution condition | Yes (whether training was paused) |
| Deadline status | Elapsed |
| Forecaster's own later assessment | 2024-03-22 "Over the last 12 months developers of the most advanced systems have revealed beyond all doubt that their primary commitment is to speed and their own competitive advantage." https://futureoflife.org/ai/the-pause-letter-one-year-later/ |
| Facts stated in primary sources | (not yet recorded as of the first edition) |
| Pre- / post-resolution | Post-resolution |
| Registration commit | `313532b884c57be431528c8aab84605739fbdf5b` |
| Notes | Signatories: more than 30,000 (FLI's wording, retrieved 2026-09-14) / scope narrowed by FLI's FAQ |

Every row in Chapter 4 carries these same columns. Columns omitted from the prose for space can be found in `data/registry.csv`.

**On row numbers and row names.** Each row carries a sequential number and a row name. The row opened in this chapter is **001 "Future of Life Institute / Call to pause training of AI systems more powerful than GPT-4 for six months / 2023-03-22."**

The row name is not a nickname assigned by this book. **It is the formal name of the row, fixed in the following shape:**

```
Speaker / subject and content of the forecast / date of statement
```

The shape is required so that **the name, lifted out and placed elsewhere, still identifies its object uniquely.** Rows are quoted in reporting, cited by other documents, extracted from machine-readable files. An abbreviation such as "the six-month pause" loses who said it and when. Once lost, the row cannot be used for verification.

The text of this book therefore refers to a row **by number and formal name together.** A number alone leaves the reader unable to recall what the row was about without returning to a table. A name alone leaves them unable to find the corresponding line in the machine-readable file. Both together let reader and machine reach the same row.

The form has a second effect. **A row whose formal name cannot be written cannot enter the registry.** If the speaker cannot be identified, it cannot be written. If the subject and content cannot be compressed into one phrase, it cannot be written. If the date is unsettled, it cannot be written. **Assembling the formal name is itself the test of the admission criteria.**

### Notation in the text — two tiers

The formal name is long. Referring to the same row repeatedly makes prose unreadable. The text therefore uses two tiers.

| Tier | Form | Where used |
|---|---|---|
| Full | `number "Speaker / subject and content / date"` | First mention in each chapter. The registry, the machine-readable files, and any citation outside this book |
| In-chapter | `number "Speaker / subject and content"` | Second and later mentions within the same chapter |

**Only the date may be dropped.** The speaker and the subject are never omitted, however many times the row appears. Lose those and the reader loses the object.

**A new chapter returns to the full form.** A reader who begins mid-book still meets the complete name once within that chapter.

The registry itself, `data/registry.json`, `data/registry.csv`, and any citation outside this book always use the full form. **The in-chapter form is a convenience of prose, not an identifier.**

### Listing several rows

**Where two or more rows are shown together, they are set as a list, not run together in prose.**

A formal name contains slashes and is long in itself. Strung together with commas, the boundary between one row and the next disappears. In a list, the start of each line marks the boundary.

- 001 "Future of Life Institute / Call to pause training of AI systems more powerful than GPT-4 for six months / 2023-03-22"
- 007 "Global Call for AI Red Lines / Call for an international agreement on AI red lines by the end of 2026 / 2025-09-22"

The rule applies at two rows as well. Two names run together still place four slashes in one sentence.

**The same applies to narrative passages touching several rows.** "He revised A into B and wrote C, adjudicated D as E" appears to convey a sequence of events while in fact asking the reader to hunt for the boundaries of each name. Such passages are recast as lists headed by dates or by order.

### References

- Future of Life Institute, "Pause Giant AI Experiments: An Open Letter," 22 March 2023. https://futureoflife.org/open-letter/pause-giant-ai-experiments/
- Future of Life Institute, "FAQs about FLI's Open Letter Calling for a Pause on Giant AI Experiments." https://futureoflife.org/ai/faqs-about-flis-open-letter-calling-for-a-pause-on-giant-ai-experiments/
- Future of Life Institute, "Future of Life Institute Newsletter: Pause Giant AI Experiments!," May 2023. https://futureoflife.org/newsletter/future-of-life-institute-newsletter-pause-giant-ai-experiments/
- Future of Life Institute, "The Pause Letter: One year later," 22 March 2024. https://futureoflife.org/ai/the-pause-letter-one-year-later/
- Future of Life Institute, "Policymaking In The Pause." https://futureoflife.org/document/policymaking-in-the-pause/

---

# Chapter 3: Shapes that can be settled, and shapes that cannot

Chapter 2 opened one row. This chapter sets all eight rows of the first edition side by side and reads them through the four requisites.

One thing first. This chapter does not say which forecasts proved correct. It says **which forecasts are in a shape that someone — and whom — can settle.** That is visible from the form alone, before the content is read.

---

## The eight rows

| ID | Row name (formal) | Deadline | Subject | Magnitude | Resolution | At registration |
|---|---|---|---|---|---|---|
| 001 | Future of Life Institute / Call to pause training of AI systems more powerful than GPT-4 for six months / 2023-03-22 | ○ | ○ | ○ | ○ | Post |
| 002 | Gary Marcus / No mindblowing GPT within 2024 / 2024-03-31 | ○ | ○ | △ | × | Post |
| 003 | Gary Marcus / Timing of the start of the generative-AI bubble collapse / 2024-03-31 | ○ | ○ | × | × | Post |
| 004 | Gary Marcus / Revision of the timing of the generative-AI bubble collapse / 2024-08-03 | ○ | ○ | × | × | Post |
| 005 | Gary Marcus / No AGI within 2025 / 2025-01-09 | ○ | △ | × | × | Post |
| 006 | AI Futures Project / Superhuman coder reached in March 2027 / 2025-04-03 | ○ | ○ | ○ | △ | Pre |
| 007 | Global Call for AI Red Lines / Call for an international agreement on AI red lines by the end of 2026 / 2025-09-22 | ○ | ○ | ○ | ○ | Pre |
| 008 | Dario Amodei / Capability of an agent swarm to take over the entire internet within 6-12 months / 2026-09 | ○ | ○ | ○ | △ | Pre |

○ = explicitly present　△ = present but requiring interpretation　× = not stated

Quotations and sources for each row appear in Chapter 4. This chapter reads form only.

## Rows with all four — two

Two rows carry all four requisites explicitly.

- **001 "Future of Life Institute / Call to pause training of AI systems more powerful than GPT-4 for six months / 2023-03-22"**
- **007 "Global Call for AI Red Lines / Call for an international agreement on AI red lines by the end of 2026 / 2025-09-22"**

The former was opened in Chapter 2. Consider the latter, issued in September 2025.

> We urge governments to reach an international agreement on red lines for AI — ensuring they are operational, with robust enforcement mechanisms — by the end of 2026.

Deadline: the end of 2026. Subject: an international agreement on red lines for AI. Magnitude: operational, with robust enforcement. Resolution: whether such an agreement is reached. On 1 January 2027, anyone other than the authors can check.

One feature of form stands out. **Both rows with all four requisites are demands, not forecasts.** They say what should be done, not what will happen. A demand, by its nature, must state what, by when, by whom, and on what terms it is satisfied — or it is not a demand. The four requisites therefore assemble themselves.

A forecast is different. A forecast is complete once it says what will happen. By when, at what magnitude, on what condition it counts as correct — none of that is needed for it to pass as a forecast. Among the eight rows, **none of the six written as forecasts states all four requisites explicitly.** That is not a verdict by the recorder. It is the result of counting the marks in the table.

## Rows with a deadline but no resolution condition — four

- **002 "Gary Marcus / No mindblowing GPT within 2024 / 2024-03-31"**
- **003 "Gary Marcus / Timing of the start of the generative-AI bubble collapse / 2024-03-31"**
- **004 "Gary Marcus / Revision of the timing of the generative-AI bubble collapse / 2024-08-03"**
- **005 "Gary Marcus / No AGI within 2025 / 2025-01-09"**

All four are statements by Gary Marcus, a cognitive scientist who has argued from a sceptical position about the capabilities of AI.

All four carry deadlines: "this year" (2024), "by this time next year" (around March 2025), "days or weeks," 2025. All four carry subjects: GPT, the generative-AI bubble, AGI.

None carries a resolution condition.

- In 002 "Gary Marcus / No mindblowing GPT within 2024," **mindblowing** is never defined — nothing says what would have to appear to qualify
- In 003 "Gary Marcus / Timing of the start of the generative-AI bubble collapse," **the bubble may start to pop** never says what would count as the bubble starting to pop. The sentence is also preceded by a condition — that nobody releases a true quantum leap by the end of 2024 — whose satisfaction itself requires interpretation
- In 004 "Gary Marcus / Revision of the timing of the generative-AI bubble collapse," **collapse** is undefined: share prices, investment volume, user numbers, and by what proportion, are not stated
- In 005 "Gary Marcus / No AGI within 2025," **AGI** is a term on which the field does not agree

These four rows therefore **cannot be settled by a third party once their deadlines pass.** Only the person who knows what "mindblowing," "pop," "collapse" and "AGI" were meant to denote can settle them.

And that person has settled them. Marcus has processed his own forecasts three times.

- August 2024 — revised the timing in 003 "Gary Marcus / Timing of the start of the generative-AI bubble collapse" and wrote 004 "Gary Marcus / Revision of the timing of the generative-AI bubble collapse"
- January 2025 — adjudicated 002 "Gary Marcus / No mindblowing GPT within 2024" himself
- January 2026 — published a piece scoring seventeen of his own 2025 forecasts

**The outcome layer of a forecast short of the four requisites is filled by its author's words.** That is the subject of Chapter 5.

## Rows with deadline, subject and magnitude but an interpretable resolution — two

- **006 "AI Futures Project / Superhuman coder reached in March 2027 / 2025-04-03"**
- **008 "Dario Amodei / Capability of an agent swarm to take over the entire internet within 6-12 months / 2026-09"**

The first belongs to "AI 2027," a 71-page scenario document published in April 2025 by Daniel Kokotajlo, a former OpenAI researcher, and colleagues. It forecasts the arrival of a "superhuman coder" in March 2027. The term is defined in an appendix.

> A superhuman coder (SC): an AI system that can do any coding tasks that the best AGI company engineer does.

The definition is the row's strength. Deadline (March 2027), subject (an AI performing coding tasks) and magnitude ("any" task the best engineer performs) are all present. But interpretation remains in the resolution. Who is "the best AGI company engineer," and how is the complete set of tasks that person performs to be established? The definition indicates a direction; it is not an adjudication procedure.

The second, written in September 2026 by Dario Amodei, chief executive of Anthropic, has a still more distinctive shape.

> Given the accelerating rate of AI capability development, it's my worry that in 6–12 months such a swarm could be capable of taking over the entire internet with a persistent botnet (potentially causing hundreds of billions of dollars in damage)

Deadline (6–12 months), subject (takeover of the internet by a swarm of AI agents) and magnitude (hundreds of billions of dollars) are present. But the predicate is "could be capable of." **It does not say the thing will happen; it says a capability for it could exist.** Should it happen, the sentence is confirmed. Should it not happen, the sentence is not refuted: one can say the capability existed and was not exercised.

This book describes that as a resolution condition present **on one side only.** Correctness is confirmable; incorrectness is not. No third party can, in principle, call such a forecast wrong within the period of record.

This is not a criticism of 008 "Dario Amodei / Capability of an agent swarm to take over the entire internet within 6-12 months." Amodei writes "it's my worry that," placing the statement as a concern rather than an assertion. This book describes that shape as it is.

## Counting

**Rows a third party can settle when the deadline passes — 2**

- 001 "Future of Life Institute / Call to pause training of AI systems more powerful than GPT-4 for six months"
- 007 "Global Call for AI Red Lines / Call for an international agreement on AI red lines by the end of 2026"

**Rows awaiting their author's adjudication — 4**

- 002 "Gary Marcus / No mindblowing GPT within 2024"
- 003 "Gary Marcus / Timing of the start of the generative-AI bubble collapse"
- 004 "Gary Marcus / Revision of the timing of the generative-AI bubble collapse"
- 005 "Gary Marcus / No AGI within 2025"

**Rows where a definition or predicate leaves interpretation — 2**

- 006 "AI Futures Project / Superhuman coder reached in March 2027"
- 008 "Dario Amodei / Capability of an agent swarm to take over the entire internet within 6-12 months"

Of eight rows, only two can be confirmed as answered by recorder and reader alike, and both are demands. **The outcomes of the other six depend on what their authors say.**

This distribution may be particular to the eight rows chosen for the first edition. It may change as rows accumulate. This book updates the table each time rows are added. What the numbers do is answered by the registry.

## What form shows

The table in this chapter does not show the quality of forecasts. It shows **who can answer them.**

A statement with all four requisites can be answered by anyone. The answer therefore comes quickly and does not move. The FLI letter was answered six months later, and its author wrote about it a year later.

A statement missing requisites can be answered only by its author. The answer comes when the author looks back. If they never look back, no answer comes. And the answer moves with the manner of looking back. On the timing of the generative-AI bubble collapse, Marcus moved the deadline within five months.

- 003 "Gary Marcus / Timing of the start of the generative-AI bubble collapse" — around March 2025
- 004 "Gary Marcus / Revision of the timing of the generative-AI bubble collapse" — days or weeks away

**The same person, on the same subject, moved the deadline.** This book records each instance as its own row. That is the work of a registry.

## On a row not reached in primary form

For 006 "AI Futures Project / Superhuman coder reached in March 2027," this book has not, as of 14 September 2026, reached `ai-2027.com` directly. The definition quoted above is taken from a third-party site quoting the document's appendix. Kokotajlo's reported statement that his median moved from 2028 to 2029 likewise comes by way of an article by the co-authoring organisation FutureSearch.

By this book's criteria, that is **secondary.** In the registry of Chapter 4, the source tier of 006 "AI Futures Project / Superhuman coder reached in March 2027" is marked secondary, and a row will be appended once the primary source is reached. **A row not reached in primary form is never written as though it had been.** Of the eight rows in the first edition, this is the only one in that condition.

### References

- Future of Life Institute, "Pause Giant AI Experiments: An Open Letter," 22 March 2023. https://futureoflife.org/open-letter/pause-giant-ai-experiments/
- Gary Marcus, "When will the GenAI bubble burst?," 31 March 2024. https://garymarcus.substack.com/p/when-will-the-genai-bubble-burst
- Gary Marcus, "Why the collapse of the Generative AI bubble may be imminent," 3 August 2024. https://garymarcus.substack.com/p/why-the-collapse-of-the-generative
- Gary Marcus, "AGI isn't coming in 2025, and GPT-5 probably isn't either," 9 January 2025. https://garymarcus.substack.com/p/agi-isnt-coming-in-2025-and-gpt-5
- AI Futures Project, "AI 2027," 3 April 2025. https://ai-2027.com/ (not reached directly as of 14 September 2026)
- AI 2027 Tracker, "Superhuman coder emerges." https://ai2027-tracker.com/predictions/superhuman-coder/
- FutureSearch, "AI 2027 Six Months Later: Karpathy, Kokotajlo, and Shifting AGI Timelines." https://futuresearch.ai/blog/ai-2027-6-months-later/
- Global Call for AI Red Lines, launched September 2025. https://red-lines.ai/
- Dario Amodei, "We Must Pace the Frontier," September 2026. https://darioamodei.com/post/we-must-pace-the-frontier

---

# Chapter 4: The registry

This chapter is the body of the book.

Everything from the prologue to Chapter 3 was preparation for reading it. Chapter 1 gave the meaning of the columns, Chapter 2 the way a row is opened, Chapter 3 the way form is read. Here stand the results of applying them.

**This chapter alone grows over time.** The other chapters update their references when rows are added. This one takes the rows themselves.

---

## How to read the registry

Every row carries all the columns defined in Chapter 1. In the prose, each row is shown as one table. The order of columns matches `data/registry.csv`.

Rows are referred to by number and formal name together, the formal name taking the shape "Speaker / subject and content of the forecast / date of statement."

**Empty fields are left empty.** A field reading "not retrieved as of the first edition," "not reached," or "not yet recorded" means the book has not got there. Nothing is filled in by conjecture. When it is reached, a new row filling that field is appended, and the original remains.

**Rows whose source tier reads "secondary" have not been reached in primary form.** One row in the first edition is in that condition.

## The eight rows of the first edition

| ID | Row name (formal) | Source | At registration |
|---|---|---|---|
| 001 | Future of Life Institute / Call to pause training of AI systems more powerful than GPT-4 for six months / 2023-03-22 | primary | Post-resolution |
| 002 | Gary Marcus / No mindblowing GPT within 2024 / 2024-03-31 | primary | Post-resolution |
| 003 | Gary Marcus / Timing of the start of the generative-AI bubble collapse / 2024-03-31 | primary | Post-resolution |
| 004 | Gary Marcus / Revision of the timing of the generative-AI bubble collapse / 2024-08-03 | primary | Post-resolution |
| 005 | Gary Marcus / No AGI within 2025 / 2025-01-09 | primary | Post-resolution |
| 006 | AI Futures Project / Superhuman coder reached in March 2027 / 2025-04-03 | secondary | Pre-resolution |
| 007 | Global Call for AI Red Lines / Call for an international agreement on AI red lines by the end of 2026 / 2025-09-22 | primary | Pre-resolution |
| 008 | Dario Amodei / Capability of an agent swarm to take over the entire internet within 6-12 months / 2026-09 | primary | Pre-resolution |

Post-resolution 5, pre-resolution 3. Primary 7, secondary 1.

---

## The rows

### 001 "Future of Life Institute / Call to pause training of AI systems more powerful than GPT-4 for six months / 2023-03-22"

| Column | Content |
|---|---|
| ID | 001 |
| Row name (formal) | Future of Life Institute / Call to pause training of AI systems more powerful than GPT-4 for six months / 2023-03-22 |
| Speaker | Future of Life Institute (non-profit organisation, United States) |
| Date of statement | 2023-03-22 |
| Note on date |  |
| Medium | Open letter |
| Verbatim quotation | Therefore, we call on all AI labs to immediately pause for at least 6 months the training of AI systems more powerful than GPT-4. |
| Preceding sentence | We agree. That point is now. |
| Following sentence | This pause should be public and verifiable, and include all key actors. |
| Primary URL | https://futureoflife.org/open-letter/pause-giant-ai-experiments/ |
| Retrieval evidence | Pause Giant AI Experiments: An Open Letter - Future of Life Institute (retrieved 2023-03-22 page, accessed 2026-09-14) |
| Source tier | primary |
| Deadline | Yes (6 months / 2023-09-22) |
| Subject | Yes (training of AI systems more powerful than GPT-4) |
| Magnitude | Yes (all AI labs) |
| Resolution condition | Yes (whether training was paused) |
| Deadline status | Elapsed |
| Forecaster's own later assessment | 2024-03-22 ｜ Over the last 12 months developers of the most advanced systems have revealed beyond all doubt that their primary commitment is to speed and their own competitive advantage. ｜ https://futureoflife.org/ai/the-pause-letter-one-year-later/ |
| Facts stated in primary sources | (not yet recorded as of the first edition) |
| Pre- / post-resolution | Post-resolution |
| Registration commit | `313532b884c57be431528c8aab84605739fbdf5b` |
| Notes | Signatories: more than 30,000 (FLI's own wording, retrieved 2026-09-14) / FLI's FAQ narrows the scope to "models larger than GPT-4" and "a very small pool of actors who possess this capability" |

### 002 "Gary Marcus / No mindblowing GPT within 2024 / 2024-03-31"

| Column | Content |
|---|---|
| ID | 002 |
| Row name (formal) | Gary Marcus / No mindblowing GPT within 2024 / 2024-03-31 |
| Speaker | Gary Marcus (cognitive scientist; Professor Emeritus, New York University) |
| Date of statement | 2024-03-31 |
| Note on date |  |
| Medium | Author's Substack post, "When will the GenAI bubble burst?" |
| Verbatim quotation | But will we see a mindblowing GPT this year? I doubt it. |
| Preceding sentence | GenAI will, in that case, live for another day, perhaps imploding only later when people realize there is no killer app to justify the increasingly high costs. |
| Following sentence | Altman himself has hinted in his recent Lex Fridman interview that nothing quite worthy of the GPT-5 name will drop this year. |
| Primary URL | https://garymarcus.substack.com/p/when-will-the-genai-bubble-burst |
| Retrieval evidence | Passage match confirmed via search (2026-09-14). Full text not directly retrieved |
| Source tier | primary |
| Deadline | Yes (within 2024) |
| Subject | Yes (a new GPT-series model from OpenAI) |
| Magnitude | Partial ("mindblowing" is subjective) |
| Resolution condition | No |
| Deadline status | Elapsed |
| Forecaster's own later assessment | 2025-01-09 ｜ Last March I predicted that it wouldn't arrive in 2024. It didn't. ｜ https://garymarcus.substack.com/p/agi-isnt-coming-in-2025-and-gpt-5 |
| Facts stated in primary sources | (not yet recorded as of the first edition) |
| Pre- / post-resolution | Post-resolution |
| Registration commit | `313532b884c57be431528c8aab84605739fbdf5b` |
| Notes | The same post also contains the forecast recorded as row 003 |

### 003 "Gary Marcus / Timing of the start of the generative-AI bubble collapse / 2024-03-31"

| Column | Content |
|---|---|
| ID | 003 |
| Row name (formal) | Gary Marcus / Timing of the start of the generative-AI bubble collapse / 2024-03-31 |
| Speaker | Gary Marcus (cognitive scientist; Professor Emeritus, New York University) |
| Date of statement | 2024-03-31 |
| Note on date |  |
| Medium | Author's Substack post, "When will the GenAI bubble burst?" |
| Verbatim quotation | If nobody (OpenAI, Google, or anyone else) releases a true quantum leap by the end of 2024, substantially addressing key issues around reliability, hallucination, data leakage, and security, the bubble may start to pop by this time next year. |
| Preceding sentence | (not retrieved as of the first edition) |
| Following sentence | (not retrieved as of the first edition) |
| Primary URL | https://garymarcus.substack.com/p/when-will-the-genai-bubble-burst |
| Retrieval evidence | Passage match confirmed via search (2026-09-14). Full text not directly retrieved |
| Source tier | primary |
| Deadline | Yes (around March 2025) |
| Subject | Yes (the generative-AI bubble) |
| Magnitude | No |
| Resolution condition | No ("may start to pop"; preceded by a conditional clause) |
| Deadline status | Elapsed |
| Forecaster's own later assessment | 2024-08-03 ｜ I just wrote a hard-hitting essay for WIRED predicting that the AI bubble will collapse in 2025 - and now I wish I hadn't. Clearly, I got the year wrong. ｜ https://garymarcus.substack.com/p/why-the-collapse-of-the-generative |
| Facts stated in primary sources | (not yet recorded as of the first edition) |
| Pre- / post-resolution | Post-resolution |
| Registration commit | `313532b884c57be431528c8aab84605739fbdf5b` |
| Notes | Revised by the author on 2024-08-03. The revised forecast is recorded separately as row 004 |

### 004 "Gary Marcus / Revision of the timing of the generative-AI bubble collapse / 2024-08-03"

| Column | Content |
|---|---|
| ID | 004 |
| Row name (formal) | Gary Marcus / Revision of the timing of the generative-AI bubble collapse / 2024-08-03 |
| Speaker | Gary Marcus (cognitive scientist; Professor Emeritus, New York University) |
| Date of statement | 2024-08-03 |
| Note on date |  |
| Medium | Author's Substack post, "Why the collapse of the Generative AI bubble may be imminent" |
| Verbatim quotation | It's going to be days or weeks from now, not months. |
| Preceding sentence | Clearly, I got the year wrong. |
| Following sentence | (not retrieved as of the first edition) |
| Primary URL | https://garymarcus.substack.com/p/why-the-collapse-of-the-generative |
| Retrieval evidence | Passage match confirmed via search (2026-09-14). Full text not directly retrieved |
| Source tier | primary |
| Deadline | Yes (days to weeks / August-September 2024) |
| Subject | Yes (collapse of the AI bubble) |
| Magnitude | No |
| Resolution condition | No ("collapse" undefined) |
| Deadline status | Elapsed |
| Forecaster's own later assessment | (as of the first edition, no statement in which the author directly revisits this particular forecast has been reached) |
| Facts stated in primary sources | (not yet recorded as of the first edition) |
| Pre- / post-resolution | Post-resolution |
| Registration commit | `313532b884c57be431528c8aab84605739fbdf5b` |
| Notes | In the same post the author assesses his March forecasts: "In March of this year, I made a series of seven predictions about how this year would go. Every one of them has held firm" |

### 005 "Gary Marcus / No AGI within 2025 / 2025-01-09"

| Column | Content |
|---|---|
| ID | 005 |
| Row name (formal) | Gary Marcus / No AGI within 2025 / 2025-01-09 |
| Speaker | Gary Marcus (cognitive scientist; Professor Emeritus, New York University) |
| Date of statement | 2025-01-09 |
| Note on date | Metadata modified_time: 2025-01-09T17:06:03Z |
| Medium | Author's Substack post, "AGI isn't coming in 2025, and GPT-5 probably isn't either" |
| Verbatim quotation | I will stand by my own predictions that we won't see AGI in 2025, and I won't be at all surprised if don't even see anything worthy of the GPT-5 name |
| Preceding sentence | Given that Musk is right in the middle of building what many think will be the largest language model to date, Grok 3, and that he has probably seen earlier returns on Grok 3, this is a notable retreat from his earlier predictions. |
| Following sentence | Gary Marcus wishes the media would hold those who make unrealistic promises to account. (author's note at the end of the post) |
| Primary URL | https://garymarcus.substack.com/p/agi-isnt-coming-in-2025-and-gpt-5 |
| Retrieval evidence | AGI isn't coming in 2025, and GPT-5 probably isn't either - by Gary Marcus (accessed 2026-09-14, full text retrieved) |
| Source tier | primary |
| Deadline | Yes (within 2025) |
| Subject | Partial ("AGI" has no agreed definition across the field) |
| Magnitude | No |
| Resolution condition | No |
| Deadline status | Elapsed |
| Forecaster's own later assessment | 2026-01 (month only) ｜ Overall, by my count, sixteen of my seventeen "high confidence" predictions about 2025 proved to be correct. ｜ Author's Substack post "Six (or seven) predictions for AI 2026 from a Generative AI realist" (full URL not yet recorded as of the first edition) |
| Facts stated in primary sources | (not yet recorded as of the first edition) |
| Pre- / post-resolution | Post-resolution |
| Registration commit | `313532b884c57be431528c8aab84605739fbdf5b` |
| Notes | The same post juxtaposes Musk's April 2024 statement with his January 2025 remarks at CES |

### 006 "AI Futures Project / Superhuman coder reached in March 2027 / 2025-04-03"

| Column | Content |
|---|---|
| ID | 006 |
| Row name (formal) | AI Futures Project / Superhuman coder reached in March 2027 / 2025-04-03 |
| Speaker | AI Futures Project (Daniel Kokotajlo, Scott Alexander, Thomas Larsen, Eli Lifland, Romeo Dean) |
| Date of statement | 2025-04-03 |
| Note on date | Multiple third-party articles agree on this date |
| Medium | Scenario document "AI 2027" (web and PDF, 71 pages) |
| Verbatim quotation | A superhuman coder (SC): an AI system that can do any coding tasks that the best AGI company engineer does. |
| Preceding sentence | (not retrieved as of the first edition) |
| Following sentence | (not retrieved as of the first edition) |
| Primary URL | https://ai-2027.com/ |
| Retrieval evidence | Not reached (as of 2026-09-14). The definition above is quoted by the third-party site ai2027-tracker.com from Appendix G (p.50) of the document |
| Source tier | secondary |
| Deadline | Yes (March 2027) |
| Subject | Yes (an AI system able to perform any coding task) |
| Magnitude | Yes (any task the best AGI-company engineer performs) |
| Resolution condition | Partial (a definition exists, but no procedure for identifying "the best engineer" or verifying "any task") |
| Deadline status | Not yet elapsed |
| Forecaster's own later assessment | c. 2025-10 ｜ When AI 2027 was published my median was 2028, now it's slipped to 2029 as a result of improved timelines models & slightly slower than expected progress in general (Daniel Kokotajlo) ｜ https://futuresearch.ai/blog/ai-2027-6-months-later/ (via co-authoring organisation FutureSearch; secondary) |
| Facts stated in primary sources | (not yet recorded as of the first edition) |
| Pre- / post-resolution | Pre-resolution |
| Registration commit | `313532b884c57be431528c8aab84605739fbdf5b` |
| Notes | This registry has not reached the primary source. A row will be appended once it is reached. The document is accompanied by five research supplements (Compute / Timelines / Takeoff / AI Goals / Security) |

### 007 "Global Call for AI Red Lines / Call for an international agreement on AI red lines by the end of 2026 / 2025-09-22"

| Column | Content |
|---|---|
| ID | 007 |
| Row name (formal) | Global Call for AI Red Lines / Call for an international agreement on AI red lines by the end of 2026 / 2025-09-22 |
| Speaker | Global Call for AI Red Lines (signatory coalition; secretariat: CeSIA, The Future Society, UC Berkeley CHAI) |
| Date of statement | 2025-09-22 |
| Note on date | No date stated on the primary site ("Launched during the 80th session of the United Nations General Assembly"). Date taken from secondary reporting (NBC News) |
| Medium | Public statement (red-lines.ai) |
| Verbatim quotation | We urge governments to reach an international agreement on red lines for AI — ensuring they are operational, with robust enforcement mechanisms — by the end of 2026. |
| Preceding sentence | These red lines should build upon and enforce existing global frameworks and voluntary corporate commitments, ensuring that all advanced AI providers are accountable to shared thresholds. |
| Following sentence | (none; this is the final sentence of the statement itself) |
| Primary URL | https://red-lines.ai/ |
| Retrieval evidence | Call for red lines to prevent unacceptable AI risks (accessed 2026-09-14, full text retrieved) |
| Source tier | primary |
| Deadline | Yes (2026-12-31) |
| Subject | Yes (an international agreement on red lines for AI) |
| Magnitude | Yes (operational, with robust enforcement mechanisms) |
| Resolution condition | Yes (whether such an agreement is reached) |
| Deadline status | Not yet elapsed |
| Forecaster's own later assessment | (none; deadline not yet elapsed) |
| Facts stated in primary sources | The statement's FAQ names the route to resolution: France's G7 presidency running until 2026-12-31, the UN Global Dialogue convening in Geneva in July 2026, and the UN General Assembly in September 2026 |
| Pre- / post-resolution | Pre-resolution |
| Registration commit | `313532b884c57be431528c8aab84605739fbdf5b` |
| Notes | Signatories: 300+ prominent figures / 11 former heads of state and ministers / 90+ organisations / 15 Nobel Prize and Turing Award recipients (retrieved 2026-09-14). Signatories include Gary Marcus and Daniel Kokotajlo |

### 008 "Dario Amodei / Capability of an agent swarm to take over the entire internet within 6-12 months / 2026-09"

| Column | Content |
|---|---|
| ID | 008 |
| Row name (formal) | Dario Amodei / Capability of an agent swarm to take over the entire internet within 6-12 months / 2026-09 |
| Speaker | Dario Amodei (Chief Executive Officer, Anthropic) |
| Date of statement | 2026-09 |
| Note on date | The primary site shows "September 2026" with no day. Secondary reporting gives 2026-09-12 |
| Medium | Essay on the author's website, "We Must Pace the Frontier" |
| Verbatim quotation | Given the accelerating rate of AI capability development, it's my worry that in 6–12 months such a swarm could be capable of taking over the entire internet with a persistent botnet (potentially causing hundreds of billions of dollars in damage), and that the scale of damage would continue to increase from there if AI becomes more powerful without the necessary guardrails. |
| Preceding sentence | It's easy to dismiss this incident because no one was hurt and the economic damage was minimal, but in my opinion, a swarm that possessed greater capabilities but a similar level of misalignment could have caused catastrophic damage. |
| Following sentence | It's also easy to dismiss OAI-HF as the failure of one company, but I believe that would be a mistake. |
| Primary URL | https://darioamodei.com/post/we-must-pace-the-frontier |
| Retrieval evidence | Dario Amodei - We Must Pace the Frontier (accessed 2026-09-14, full text retrieved) |
| Source tier | primary |
| Deadline | Yes (6-12 months / March-September 2027) |
| Subject | Yes (takeover of the entire internet by a swarm of AI agents) |
| Magnitude | Yes (hundreds of billions of dollars in damage) |
| Resolution condition | Partial ("could be capable of": confirmable if it occurs, but not falsifiable if it does not) |
| Deadline status | Not yet elapsed |
| Forecaster's own later assessment | (none; deadline not yet elapsed) |
| Facts stated in primary sources | (not yet recorded as of the first edition) |
| Pre- / post-resolution | Pre-resolution |
| Registration commit | `313532b884c57be431528c8aab84605739fbdf5b` |
| Notes | The same essay contains other dated statements (US lead widening "over the next 3-5 years" if measures are executed well; interpretability making "profound progress in 1-2 years"). Only this row is included in the first edition |

---

## The machine-readable files

The eight rows of this chapter are emitted, from the same data, into two further files.

- `data/registry.json` — **the canonical registry.** For reading from a program. Column definitions and operating rules precede the rows, and every column label carries both a Japanese and an English form
- `data/registry.csv` — openable in a spreadsheet. Generated from the canonical file. First line column names, subsequent lines the rows. Encoded UTF-8 with BOM

**There is one registry, shared by the Japanese and English editions.** The statement layer — verbatim quotation and the sentences before and after — is held in the original language and is identical in both. Only the form and outcome layers carry separate Japanese and English columns. A reader arriving from either edition opens the same file and cites the same row.

The prose tables and the two files **are updated in the same commit.** A state in which one is newer than the other does not exist under this book's operating rules. A reader may open `data/registry.csv` without reading the prose at all.

## The procedure for appending

When a row is added, the author works in this order.

1. Assemble the formal name. Without all three of speaker, subject and content, and date, no row can be raised
2. Fill the statement layer from the primary source: verbatim text, the sentence before and after, URL, retrieval evidence
3. Fill the form layer by looking only at the verbatim text: presence or absence of deadline, subject, magnitude, resolution condition
4. Leave the outcome layer empty at registration, as a rule. Empty if the deadline has not passed. Empty also if the deadline has passed but the author's later assessment has not been reached
5. Mark pre- or post-resolution
6. Update `data/registry.json`, regenerate `data/registry.csv` from it, and update the prose tables in both editions together, recording them as the **registration commit**, signed
7. When the outcome becomes known, append a row filling the outcome layer, recorded separately as the **outcome commit**

The separation of steps 4 and 7 is the implementation of pre-resolution recording.

### References

Primary URLs for the eight rows appear in each row's table. Listed here are sources consulted outside the rows.

- Future of Life Institute, "FAQs about FLI's Open Letter Calling for a Pause on Giant AI Experiments." https://futureoflife.org/ai/faqs-about-flis-open-letter-calling-for-a-pause-on-giant-ai-experiments/
- Future of Life Institute, "Future of Life Institute Newsletter: Pause Giant AI Experiments!," May 2023. https://futureoflife.org/newsletter/future-of-life-institute-newsletter-pause-giant-ai-experiments/
- AI 2027 Tracker, "Superhuman coder emerges." https://ai2027-tracker.com/predictions/superhuman-coder/ (source of the definition quoted in row 006)
- FutureSearch, "AI 2027 Six Months Later: Karpathy, Kokotajlo, and Shifting AGI Timelines." https://futuresearch.ai/blog/ai-2027-6-months-later/
- Gary Marcus, "Why the collapse of the Generative AI bubble may be imminent," 3 August 2024. https://garymarcus.substack.com/p/why-the-collapse-of-the-generative

---

# Chapter 5: Those who scored themselves

The outcome layer of this book carries no verdict by the recorder. It carries what the forecaster said afterwards about their own forecast.

Who, then, said something? Of the eight rows in the first edition, five carry an assessment by their author. This chapter sets those five side by side, by speaker, and records **how each treated their own forecast** — in their own words.

One thing first. This chapter does not praise those who scored themselves, and does not reproach those who did not. It sets down **who said what, and when.**

---

## Rows carrying the author's later assessment

- 001 "Future of Life Institute / Call to pause training of AI systems more powerful than GPT-4 for six months / 2023-03-22"
- 002 "Gary Marcus / No mindblowing GPT within 2024 / 2024-03-31"
- 003 "Gary Marcus / Timing of the start of the generative-AI bubble collapse / 2024-03-31"
- 005 "Gary Marcus / No AGI within 2025 / 2025-01-09"
- 006 "AI Futures Project / Superhuman coder reached in March 2027 / 2025-04-03"

Three speakers: the Future of Life Institute, Gary Marcus, and the AI Futures Project.

## Rows carrying none

- 004 "Gary Marcus / Revision of the timing of the generative-AI bubble collapse / 2024-08-03" — the deadline has passed. This book has not reached a statement in which the author revisits this particular forecast
- 007 "Global Call for AI Red Lines / Call for an international agreement on AI red lines by the end of 2026 / 2025-09-22" — deadline not yet elapsed
- 008 "Dario Amodei / Capability of an agent swarm to take over the entire internet within 6-12 months / 2026-09" — deadline not yet elapsed

That two rows whose deadlines have not arrived carry no assessment is unremarkable. For 004 "Gary Marcus / Revision of the timing of the generative-AI bubble collapse," the book has merely failed to reach one. It does not write that none exists.

---

## Future of Life Institute — an organisation writing one year on

The body that demanded a six-month pause on 22 March 2023 published, exactly one year later on 22 March 2024, a piece titled "The Pause Letter: One year later."

> Over the last 12 months developers of the most advanced systems have revealed beyond all doubt that their primary commitment is to speed and their own competitive advantage.

The same piece notes that even companies taking safety seriously experiment aggressively until the experiments become manifestly dangerous, and closes by stating that safety and responsibility will have to be imposed from outside.

Three facts are recorded here. **The party that made the demand looked back one year after the deadline.** **That looking-back states, in its own words, that the demand was not met.** **The subject looking back is an organisation, not an individual.**

The third differs from the other rows. For an organisation to publish the outcome of its own demand requires internal agreement. FLI reached it and published.

## Gary Marcus — one person, three times

Marcus holds four rows in this registry. Three of them he has written about afterwards. And the manner differs each time.

### First — moving the date (3 August 2024)

In 003 "Gary Marcus / Timing of the start of the generative-AI bubble collapse," Marcus wrote that the bubble might start to pop by this time next year — around March 2025. Five months later he wrote:

> I just wrote a hard-hitting essay for WIRED predicting that the AI bubble will collapse in 2025 — and now I wish I hadn't. Clearly, I got the year wrong. It's going to be days or weeks from now, not months.

He wrote that he got the year wrong. The direction of the error, by his own account, was that he had been too late: in his view the collapse would come sooner. This book registers the revised forecast separately as 004 "Gary Marcus / Revision of the timing of the generative-AI bubble collapse."

In the same piece, Marcus makes a second assessment.

> In March of this year, I made a series of seven predictions about how this year would go. Every one of them has held firm

Of seven forecasts from March, he states that every one has held. **Within a single piece sit both "I got the year wrong" and "every one of them has held firm."** This book records both: the first in the outcome layer of 003 "Gary Marcus / Timing of the start of the generative-AI bubble collapse," the second in the notes field of 004 "Gary Marcus / Revision of the timing of the generative-AI bubble collapse."

### Second — adjudicating (9 January 2025)

On 002 "Gary Marcus / No mindblowing GPT within 2024," nine months later, he wrote:

> Last March I predicted that it wouldn't arrive in 2024. It didn't.

Two sentences. The fact of having forecast, and the result. Those two sentences fill the outcome layer of that row.

As Chapter 3 showed, the forecast carried no resolution condition. What a "mindblowing" GPT would be was never written down. No third party can settle it. **The person who settled it was its author.** This book placed that settlement as it stands.

### Third — counting and scoring (January 2026)

In January 2026, Marcus published a tally of the forecasts he had made for 2025.

> Overall, by my count, sixteen of my seventeen "high confidence" predictions about 2025 proved to be correct.

"By my count," he writes. The counting and the judgement of correctness are both his.

The format matches Rodney Brooks's annual scorecard, treated in Chapter 7: a forecaster lists their own forecasts, scores them, and publishes the result. This book places the piece in the outcome layer of 005 "Gary Marcus / No AGI within 2025." The complete URL of that piece has not been recorded as of the first edition, and will be appended once reached.

### The three differ

The same person handled his own forecasts three times, in three ways.

- August 2024 — **revision.** He moved a deadline and issued a new forecast
- January 2025 — **adjudication.** Of one forecast, he wrote that it had not arrived
- January 2026 — **scoring.** He counted several forecasts and stated how many of how many

This book records these as three types of the author's later assessment. A revision does not close an outcome; it produces the next forecast. An adjudication closes one row. A scoring closes several at once. Of the three, only adjudication and scoring fill an outcome layer without the recorder intervening. A revision produces a new row, and so returns to the statement layer.

## AI Futures Project — a median that moved

Daniel Kokotajlo, lead author of 006 "AI Futures Project / Superhuman coder reached in March 2027," stated roughly six months after publication that his own estimate had shifted.

> When AI 2027 was published my median was 2028, now it's slipped to 2029 as a result of improved timelines models & slightly slower than expected progress in general

The word "median" is his. Kokotajlo holds the timing of an event not as a single year but as a probability distribution, and says the midpoint of that distribution moved by a year. "Slipped" is also his word.

This book attaches two reservations to the statement.

First: the book records it not from Kokotajlo's own post but by way of an article from the co-authoring organisation FutureSearch. **The source tier is secondary.**

Second: the "median" referred to may not be the same thing as the deadline in 006 "AI Futures Project / Superhuman coder reached in March 2027" — the superhuman coder of March 2027 — but a broader estimate. The FutureSearch article itself notes that these quotations do not specifically concern the arrival of superhuman coding. This book places the statement in that row's outcome layer while recording the note alongside it.

---

## What this chapter shows

Of the five rows carrying a later assessment, **four record the author saying that they revised, that it did not arrive, or that the estimate slipped; one records the author saying it was correct.** That is a count over the eight rows of the first edition, and it may change as rows accumulate.

One further observation. Chapter 3 counted two rows carrying all four requisites. Of those two, only the FLI row has passed its deadline, and FLI wrote an assessment. Of the four rows missing requisites whose deadlines have passed, three carry an assessment by Marcus.

In other words, **authors look back on well-formed and ill-formed forecasts alike.** Whether someone looks back is not determined by the form of the forecast. It is determined by who made it. This is an observation confined to the eight rows of the first edition.

The reason for this chapter is to show the reader how the outcome layer comes to be filled. As the registry grows and deadlines arrive in succession, whether outcome layers fill depends on whether the names in this chapter multiply.

### References

- Future of Life Institute, "The Pause Letter: One year later," 22 March 2024. https://futureoflife.org/ai/the-pause-letter-one-year-later/
- Gary Marcus, "Why the collapse of the Generative AI bubble may be imminent," 3 August 2024. https://garymarcus.substack.com/p/why-the-collapse-of-the-generative
- Gary Marcus, "AGI isn't coming in 2025, and GPT-5 probably isn't either," 9 January 2025. https://garymarcus.substack.com/p/agi-isnt-coming-in-2025-and-gpt-5
- Gary Marcus, "Six (or seven) predictions for AI 2026 from a Generative AI realist," January 2026. (complete URL not recorded as of the first edition)
- FutureSearch, "AI 2027 Six Months Later: Karpathy, Kokotajlo, and Shifting AGI Timelines." https://futuresearch.ai/blog/ai-2027-6-months-later/

---

# Chapter 6: The record of revisions

A forecast can change after it is issued.

The same person, on the same subject, moves a deadline. Changes a figure. Adds a condition. This book calls that a revision, and holds the state before and the state after as separate rows. This chapter sets those pairs side by side.

It sets them side by side and no more. **This book does not write in prose which direction a revision moved.** Place the dates and figures next to each other and the reader sees it. To put what is visible into words would make the book a commentary rather than a record.

---

## What counts as a revision

This book records as a revision anything meeting all three conditions.

1. **The same speaker**
2. **on the same subject**
3. later **changed** the deadline, the magnitude, or the resolution condition of an earlier forecast

Lacking any one, it is not a revision.

## What does not count

Three things are easily confused with revision.

**An adjudication is not a revision.** "Last March I predicted that it wouldn't arrive in 2024. It didn't." — that closes the outcome of 002 "Gary Marcus / No mindblowing GPT within 2024"; it does not change the forecast. Chapter 5 treated it.

**A scoring is not a revision.** "Sixteen of seventeen proved correct" closes several forecasts at once; none of them changed. Chapter 5 treated it too.

**A new forecast in the same direction is not a revision.** In 005 "Gary Marcus / No AGI within 2025," Marcus wrote that AGI would not arrive in 2025; in January 2026 he wrote that it would not arrive in 2026 (or 2027) either. That does not alter the earlier forecast; it sets a new deadline after the old one passed. This book treats it not as a revision but as a **continuation**, registered as a separate row. The first edition does not include the later one.

The difference lies in **whether the change was made while the earlier forecast was still live, or whether a new one was issued after the deadline had passed.** The former withdraws and replaces. The latter leaves the earlier forecast standing and adds. In the registry, the former marks the earlier row "revised by the author"; the latter does not.

---

## Revisions recorded in the first edition — two

### Timing of the generative-AI bubble collapse — Gary Marcus

- **Before**: 003 "Gary Marcus / Timing of the start of the generative-AI bubble collapse / 2024-03-31"
- **After**: 004 "Gary Marcus / Revision of the timing of the generative-AI bubble collapse / 2024-08-03"

| | Before | After |
|---|---|---|
| Date of statement | 31 March 2024 | 3 August 2024 |
| Deadline | around March 2025 (by this time next year) | days or weeks from now |
| Approximate date | March 2025 | August–September 2024 |
| Condition | present (if no true quantum leap by end of 2024) | none |
| Magnitude | none | none |
| Resolution condition | none | none |

The interval between them is 125 days.

**The reason the author attached to the revision:**

> Clearly, I got the year wrong.

This book records that sentence as the reason for the revision. It was the author who wrote "got wrong," and the author who specified what was wrong — the year. The recorder writes nothing further.

The conditional clause attached to the earlier row — that nobody release a true quantum leap by the end of 2024 — is absent from the later one. The revision dropped the condition. That too is visible in the "condition" line of the table, and this book does not write what it means.

### Median for the arrival of superhuman AI — Daniel Kokotajlo

- **Before**: Kokotajlo's median at the time of publication of 006 "AI Futures Project / Superhuman coder reached in March 2027 / 2025-04-03"
- **After**: Kokotajlo's statement of around October 2025

| | Before | After |
|---|---|---|
| Date of statement | 3 April 2025 (publication of the document) | around October 2025 |
| Median | 2028 | 2029 |
| Source tier | secondary (primary document not reached) | secondary (via co-authoring organisation FutureSearch) |

The interval is roughly six months.

**The reason the author attached to the revision:**

> as a result of improved timelines models & slightly slower than expected progress in general

Two reasons are given. That the models used for forecasting improved. That progress was slightly slower than expected. **The author places the cause of the revision both on the side of his own method and on the side of the world.** This book records the sentence as it stands.

The two reservations set out in Chapter 5 apply here unchanged. The source is secondary. Whether the "median" refers to the same event as the deadline in 006 "AI Futures Project / Superhuman coder reached in March 2027" cannot be confirmed; FutureSearch itself notes that the quotations do not specifically concern the arrival of superhuman coding. This book therefore records the pair not as "a revision of 006" but as **"a revision, by the lead author of 006, of a related median."** It sits in that row's outcome layer, with the distinction stated in the notes.

---

## What it takes for a revision to survive in the record

For a revision to enter the registry, **the earlier forecast must have been recorded before it was revised.**

That sounds obvious, but most forecasts do not meet the condition. When a forecast is issued, nobody records it. When it is revised, the earlier text is deleted, or overwritten, or forgotten. What remains is the later text, which then becomes what was "always said."

Both revisions in the first edition occurred before this book began recording. The earlier texts survive because **both authors wrote in the open and did not remove them afterwards.** Marcus's March 2024 piece remains at the same URL in September 2026. Kokotajlo's median of 2028 is preserved inside a co-author's article.

Revisions occurring after this book's publication do not depend on that. If the earlier row is registered here as pre-resolution, the record of the earlier state survives even if the original text disappears. **This is what pre-resolution recording, set out in Chapter 1, means for revisions.**

## What is not recorded

Candidate revisions the book has not reached, and therefore does not record, in the first edition. It does not write that they do not exist; it writes that they have not been reached.

- **The AI Futures Project's response to criticism.** A quantitative critique of their model was published on LessWrong in June 2025, and the AI Futures Project is reported to have published a response updating the median and probability mass for the arrival of the superhuman coder. This book has not reached the primary source of that response. Once reached, it may be recordable, with dates and figures, as a revision of 006 "AI Futures Project / Superhuman coder reached in March 2027"
- **Gary Marcus's WIRED piece.** In 004 "Gary Marcus / Revision of the timing of the generative-AI bubble collapse," the author states that he wrote an essay for WIRED predicting the AI bubble would collapse in 2025. This book has not reached that essay. Once reached, a further row would sit between 003 and 004

---

## What this chapter shows

What the two revisions share is that **the author wrote the reason in a single sentence.** "I got the year wrong." "Improved models and slightly slower progress." The reasons differ; the act of giving one does not.

In both cases, too, the earlier text was not deleted. The later text refers to the earlier. "I got the year wrong" presupposes that the reader can check which year. "My median was 2028" presupposes that the figure 2028 survives in the record.

A revision reads as a revision only while the thing revised is still there. Without it, the later text is simply a forecast. That is why this chapter exists.

### References

- Gary Marcus, "When will the GenAI bubble burst?," 31 March 2024. https://garymarcus.substack.com/p/when-will-the-genai-bubble-burst
- Gary Marcus, "Why the collapse of the Generative AI bubble may be imminent," 3 August 2024. https://garymarcus.substack.com/p/why-the-collapse-of-the-generative
- Gary Marcus, "AGI isn't coming in 2025, and GPT-5 probably isn't either," 9 January 2025. https://garymarcus.substack.com/p/agi-isnt-coming-in-2025-and-gpt-5
- FutureSearch, "AI 2027 Six Months Later: Karpathy, Kokotajlo, and Shifting AGI Timelines." https://futuresearch.ai/blog/ai-2027-6-months-later/

---


# Chapter 7: Records that came before — Brooks, Marcus, Metaculus

Writing forecasts down and checking them later is not something this book invented.

This chapter sets out the existing efforts that pair AI forecasts with their outcomes, **as descriptions of their mechanisms**. What is covered, whose forecasts, who decides admission, who adjudicates outcomes. No evaluation. The mechanism.

It then fixes where this book stands.

---

## Four types

The efforts that came before fall into four types.

| Type | Examples | Whose forecasts | Who adjudicates the outcome |
|---|---|---|---|
| Self-scoring | Rodney Brooks, Gary Marcus | The author's own | The author |
| Market | Metaculus | An aggregate of participants | The operator, by pre-stated resolution criteria |
| Survey | AI Impacts | A population of respondents | Nobody (outcomes are not tracked) |
| Third-party record | This book | Other people's | The forecaster, or a primary source |

## Self-scoring — Rodney Brooks

On 1 January 2018, the roboticist Rodney Brooks published dated forecasts in three areas: self-driving cars, robotics and AI, and human space travel. The deadlines extend to 1 January 2050. And he promised **to review his own forecasts every year on 1 January.** Thirty-two years.

The eighth annual update was published on 1 January 2026.

**The way forecasts are written** is fixed in three forms.

- **BY year** — it will happen by that year
- **NET year** — No Earlier Than. It will not happen before that year
- **NIML** — Not In My Lifetime. Not before 2050

**The way judgements are written** is fixed as well. As years pass, each forecast is coloured as accurate, too pessimistic, or too optimistic. From 2025 a fourth category, "hemming and hawing," was added — for cases where something that was said to take much longer appears to have happened, but the underlying achievement is not what was expected or delivered, typically because undisclosed humans remain in the loop.

And one sentence bears most directly on this book.

> I have not changed any of the text of the first three columns of the prediction tables since their publication on the first day of 2018.

The text of the forecasts does not change. Only the judgement columns are added each year. **This is the same practice this book called append-only in Chapter 1.** Before this book adopted it, one researcher had been applying it to his own forecasts for eight years.

The mechanism differs from this book's in two respects. **The forecasts are his own.** **The judgements are his own too.** He scores himself. In the 2026 update he summarises:

> The summary is that my predictions held up pretty well, though overall I was a little too optimistic.

"Pretty well" and "a little too optimistic" are both the judge's own words.

## Self-scoring — Gary Marcus

As Chapter 5 showed, Marcus scored seventeen of his own 2025 forecasts in January 2026 and reported sixteen correct.

The difference from Brooks lies in **the span of the forecasts and the fixity of the judgement.** Brooks issued thirty-two years of forecasts on day one and fixed three colours for judgement. Marcus issues forecasts annually and tallies them the following year, prefacing the count with "by my count."

What they share is that forecaster and judge are the same person.

## Market — Metaculus

Metaculus is a forecasting platform on which participants submit probabilities. The operator poses the questions, and each question carries a resolution criterion — what must happen for it to resolve yes — written in advance. Participants submit probabilities, and the aggregate is displayed as the question's current forecast. When the deadline arrives, the operator resolves it against the criterion.

**Where it overlaps with this book**: the resolution condition is written in advance, as part of the question. Of the four requisites in Chapter 1, a Metaculus question structurally always carries a deadline and a resolution condition.

**Where it differs**, in three respects. The forecasts are an aggregate of participants, not a named speaker. The adjudicator is the operator, not the forecaster. And **the questions are posed by the operator**, so a statement someone made to the world does not automatically become a question. Many of the statements in this registry — "pause for six months," "days or weeks from now" — could not stand as Metaculus questions in their given form.

This book has not, as of the first edition, reached individual Metaculus questions directly. That multiple AI-related questions exist, resolved and unresolved, is confirmed from third-party records; the wording and figures of specific questions will be registered as rows once reached.

## Survey — AI Impacts

AI Impacts has surveyed machine-learning researchers on when AI will reach certain milestones, in 2016, 2022 and 2023. Responses are aggregated as probability distributions — for example, the median year by which the probability of machines performing all human tasks reaches fifty per cent.

**Where it overlaps**: forecasts are collected and published.

**Where it differs**: **outcomes are not tracked.** A survey records the estimate of a population of researchers at a point in time. Whether that estimate later proved right is not the survey's object. A shift in the median between surveys is visible, but it is not a record of a revision; it is a different set of respondents answering separately.

This book has not registered the survey results in the first edition. Discrepancies have been reported between the figures on the primary page and those in a subsequent paper; the rows will be registered after direct verification.

---

## Where this book stands

**This book records the forecasts of others.** The author's own forecasts do not enter the registry. Unlike Brooks and Marcus.

**This book does not adjudicate.** The outcome layer holds only the forecaster's own later assessment and facts stated in primary sources. Unlike Brooks, Marcus and Metaculus. The Metaculus operator adjudicates against a criterion; this book takes on no such role. If the forecaster does not write it, the outcome layer stays empty.

**This book tracks outcomes.** Unlike AI Impacts.

**This book proves the moment of registration by signature.** The pre-resolution recording of Chapter 1. Brooks's declaration that he has not changed the first three columns must be trusted as his word; the rows here carry commit hashes that a third party can inspect on GitHub.

None of the four types combines **a third party recording other people's forecasts, filling outcomes only with the forecaster's words, and proving the moment of registration in verifiable form.** That is where this book sits.

## What it inherits from its predecessors

Standing in a different position does not mean owing nothing.

**Append-only** is what Brooks has practised for eight years. This book has only changed the guarantee from a personal declaration to a signed commit history.

**Writing the resolution condition first** comes from the structure of Metaculus questions. This book uses it not as a requirement on the person posing a question, but as an observation made about a statement — the fourth of the four requisites.

**The "hemming and hawing" category** — where something appears to have happened but is not what was promised — is Brooks's addition of 2025. This book does not adopt it: it does not adjudicate, and so holds no categories of adjudication. But the "triangle (requires interpretation)" marking in the resolution-condition field is an attempt to describe, from the side of form, the same situation that made Brooks reach for that category.

Without these predecessors, this book's design would not exist. This chapter is also the record of that.

### References

- Rodney Brooks, "Predictions Scorecard, 2026 January 01." https://rodneybrooks.com/predictions-scorecard-2026-january-01/
- Rodney Brooks, "Predictions Scorecard, 2025 January 01." https://rodneybrooks.com/predictions-scorecard-2025-january-01/
- Rodney Brooks, "Predictions Scorecard, 2021 January 01." https://rodneybrooks.com/predictions-scorecard-2021-january-01/
- Rodney Brooks, "Category: Dated Predictions." https://rodneybrooks.com/category/dated-predictions/
- Gary Marcus, "Six (or seven) predictions for AI 2026 from a Generative AI realist," January 2026. (complete URL not recorded as of the first edition)
- Metaculus. https://www.metaculus.com/ (individual questions not reached directly as of the first edition)
- AI Impacts, Expert Surveys on Progress in AI, 2016 / 2022 / 2023. (primary pages not reached directly as of the first edition)

---

# Chapter 8: What a reader can do with this registry

Anyone who has read this far holds eight rows and the tools for reading them.

This chapter takes those tools outside the book. The registry begins at eight rows and grows. But what a reader carries away is not a number of rows. It is **one habit for reading forecasts.**

---

## One habit — apply four questions

Tomorrow, somewhere, you will meet a forecast about AI. In a headline, a talk, a post. When you do, apply four questions.

1. **By when?** A year, a month, a day. If not stated, "none"
2. **About what?** A specific model, an industry, "AI" in general. The narrower, the easier to check
3. **How much?** A number, a proportion, a sum. "Major" and "dramatic" are not magnitudes
4. **What would have to happen for it to be called correct?** If not stated, the only person who can adjudicate it is the speaker

A forecast carrying all four can be checked by anyone once the deadline arrives. One that does not has no answer until its author looks back.

The four are not a measure of quality. As Chapter 1 stated, an intuition without a deadline can still be valuable. What the four measure is **who, afterwards, can produce an answer.** Reading with that knowledge differs from reading without it.

Readers need not send the results of applying the four to this book. Applying them privately is enough. If the habit stays, this book has done its work.

## Verify the registry

This book is built so that it can be used by a reader who does not trust it.

**Check the content of a row.** Every row carries a primary URL and the page title or opening line as it stood at retrieval. Open the URL and see whether the verbatim quotation is there. If it is not, the book is in error.

**Check the moment of registration.** Every row carries the hash of its registration commit. Open that hash in the repository on GitHub and the date the row entered the registry is visible as a record outside the author's hands. The commit carries an electronic signature, so it can also be confirmed that no one rewrote it afterwards.

**Check that outcomes were appended in separate commits.** When a row registered as pre-resolution later receives its outcome, that appending is a commit distinct from the registration. Comparing the dates of the two commits shows that the forecast was recorded before its outcome.

None of this requires reading the book. `data/registry.csv` and the GitHub history suffice. **The prose of this book explains how to read the registry; it is not the basis of the registry's reliability.** The basis is the history.

## Report errors

This book is published in the open, but **the author is the only person who writes to the registry.** Readers cannot alter it directly. Raising a row, appending an outcome, issuing a correction — all are done by the author, and every commit carries the author's signature.

This is not because the book distrusts its readers. It is because **the discipline of a registry is preserved by there being a single writer.** The judgement of the four requisites, the pre- and post-resolution marking, the prohibition on verdicts in the outcome layer — all of these waver as writers multiply. A wavering registry cannot be used for verification.

What readers can do is two things.

**Report an error.** A quotation that does not match the primary source. A wrong date. A URL that does not resolve. A requisite marking inconsistent with the quoted text. A reader who finds such an error can report it as an Issue in the repository. The author checks it against the primary source and, if it is an error, appends a correcting row. The original row is not deleted. The name of the reader who reported it is recorded in the notes field of the correcting row.

**Point to the location of a primary source.** For fields marked "not reached," "not retrieved," or "not yet recorded," a reader who knows the URL of a primary source can report it as an Issue. The author reaches it, verifies it, and raises a row or fills the field. **Anything meeting the admission criteria is admitted without exception.** There is no discretion in admission, only an order of verification. Anything not meeting the criteria is not admitted, and in that case the criterion it fails is stated in the Issue before closing.

In neither case does the reader write to the registry. **The reader reads the registry and informs the author. The author writes.**

## Keep your own forecasts

This book does not record the author's own forecasts. But the means for a reader to keep their own lies outside it.

The method of Rodney Brooks, seen in Chapter 7, is available to anyone. Fix a date. Write it in the open. Do not change what you wrote. When the deadline arrives, write the result in the same place. That is all.

The essential part is **not changing what you wrote.** If you want to revise, leave the original and add a new line. As Chapter 6 showed, a revision reads as a revision only while the thing revised is still there.

A forecast placed in the open with a date attached may be registered as a row by the author, if it can be reached as a primary source. Whether it is registered is decided by the admission criteria alone, and **the criteria do not ask who the speaker is.** Prominence is not among the conditions.

## On language

This book is published in Japanese and in English. The two are not a translation of one another.

**The statement layer is in the original language in both editions.** A statement made in English is recorded in English; one made in Japanese, in Japanese. Translations sit in a separate field and are not treated as quotations. **The registry itself is a single file shared by both editions**: `data/registry.json` and `data/registry.csv` are not split by language, and the form and outcome layers carry both Japanese and English columns.

**The form and outcome layers are written in parallel, not in translation.** The judgement of the four requisites, the pre- and post-resolution marking, and the location of the author's later assessment carry the same content in either language.

Whatever language a reader reads in, the rows are the same and the way of reading them is the same. What this book gives a reader — the habit of applying four questions, the procedure for checking the history, the route for reporting an error — does not depend on language.

## What this chapter shows

The registry is maintained by the author. But the **value** of the book is not in the author's hands.

The value lies in readers coming to apply four questions when they read a forecast, coming to check the history when they check a row, and coming to leave their own words unchanged when they write down a forecast. These happen outside the book. The book has only set out the tools for them to happen.

The registry grows. Rows accumulate, deadlines arrive, outcomes fill. Writing that down remains the work of one person, and that does not change. The reader's part is to verify what has been written and report what is wrong. **One writer, and many verifiers.** When those two hold together, a registry becomes a record worth trusting. That is why this book is published in the open.

---

# Epilogue: What cannot be inscribed

This book recorded what could be recorded.

The epilogue lists what could not. It is not a catalogue of the book's defects. It is a description of **how far the form of a registry reaches, and where it stops.** Without stating where it does not reach, a reader cannot trust where it does.

---

## What cannot be inscribed

**The truth of forecasts without deadlines.** A statement of the form "the probability that AI causes human extinction is 10 to 20 per cent" can be recorded. But whether it proves right will never be settled. This book keeps it as a statement lacking a resolution condition, and the field for truth remains permanently empty. The emptiness is not negligence; it was determined by the shape of the forecast.

**Forecasts not made public.** Views expressed inside companies, statements in closed meetings, documents never released. They may have existed, but where no primary source can be reached, this book does not record them. **The possibility that the most consequential forecast in the world appears nowhere in this registry is permanent.** This book cannot rule it out.

**Statements whose primary source carries no date.** Two of the eight rows in the first edition — 007 "Global Call for AI Red Lines / Call for an international agreement on AI red lines by the end of 2026 / 2025-09-22" and 008 "Dario Amodei / Capability of an agent swarm to take over the entire internet within 6-12 months / 2026-09" — carry no date in the speaker's own primary source. This book records the date from secondary reporting alongside, but that is not primary. Where the speaker did not write a date, this book cannot fix one.

**Forecasts made before 22 March 2023.** This book chose that day as its origin. Many public forecasts about the future of AI precede it, and none of them enters this registry. Without an origin the registry cannot begin; with an origin, what lies before it is severed. This book accepted the cost.

**The outcomes of forecasts their authors never revisited.** The deadline of 004 "Gary Marcus / Revision of the timing of the generative-AI bubble collapse / 2024-08-03" has passed, but this book has not reached any statement in which the author directly revisits it. If the author does not look back, the outcome layer stays empty. **This book does not write in the author's place.** However many years the emptiness lasts, that does not change.

**The intent and motive behind a statement.** Why the forecast was made. To whom it was addressed. What it was meant to achieve. This book does not record these. The words, the date and the source can be recorded; what lay behind them cannot be established by anyone but the speaker.

**The effect a forecast had on the world.** How the demand for a six-month pause bore on subsequent regulatory debate. How a forecast of a bursting bubble bore on investment decisions. This book cannot measure these. Effect is buried among countless factors between forecast and outcome, and cannot be extracted as a primary source. **What this book records is what was said and what happened — not whether what was said caused what happened.**

## What becomes possible because this registry exists

What follows is not a forecast by this book that these things will occur. It is a description of **what becomes possible that would not have been possible had the registry not existed** — no more than that. Whether what becomes possible actually occurs depends on whether the registry is used, and this book does not forecast that.

**For those who forecast.** In an environment where a third party records before resolution, whether a forecast carries a deadline becomes part of the record. A forecast with a deadline eventually has its "deadline status" field change to "elapsed." One without a deadline remains "none" forever. Which was chosen stays attached to the forecaster's name. Rodney Brooks stated that he attached dates to his forecasts in order to inject some reality into what he saw as irrational exuberance. Attaching a date is a choice, and this registry adds one more environment in which that choice is recorded.

**For those who read.** The past rows of the same speaker can be set side by side. The four rows of Gary Marcus show, in date order, one person moving a deadline on the same subject, adjudicating, and scoring. Meeting a new forecast, a reader whose speaker has rows here can open them. Without the registry, a reader would have to find that speaker's past forecasts themselves, and establish the wording and dates themselves.

**For reporting and research.** A table in which verbatim text, dates and primary URLs are assembled, and the moment of registration is attested by signature, is available in machine-readable form. An article quoting a forecast can cite it. A researcher studying forecasting accuracy can begin from it. While the table holds eight rows, that use is limited. As rows accumulate, it widens.

**For the forecasters themselves.** Their forecast is recorded in their own words, with no verdict attached. If they later look back, those words enter the outcome layer. If they do not, an emptiness remains. **How a forecaster treated their own forecast becomes, itself, the record.** That may work to their advantage or against it. This book says neither.

## This book is a test case for its own proposition

The core proposition of this book was placed in the prologue.

> A forecast becomes a record only if it was written down before anyone knew the answer.

Apply it to the book itself.

The first edition carries eight rows, three of them pre-resolution. The first deadline to arrive is that of 007 "Global Call for AI Red Lines / Call for an international agreement on AI red lines by the end of 2026," on 31 December 2026. When that day has passed, will an outcome row be appended in a commit separate from the registration? That is the first thing that will separate this book as a registry from this book as eight rows of hindsight.

In other words, **this book has not yet proved its own proposition.** Proof occurs row by row, in the course of pre-resolution rows acquiring their outcomes. What the first edition can show is only that the registry is placed in a shape where that course is possible.

This is the same position as the forecasters recorded in it. They wrote deadlines; the deadlines came; and they divided into those who looked back and those who did not. This book has also written a deadline: 31 December 2026. How it then looks back will remain in the history.

## Position

The position of this book was fixed in Chapter 7. A third party recording other people's forecasts, filling outcomes only with the forecaster's words, and proving the moment of registration in verifiable form. No predecessor combined those.

That the position was vacant does not mean the position has value. Whether it has value is decided by whether the registry is consulted. Whether it is consulted is decided by whether it continues. Whether it continues depends, because there is a single writer, on one person.

This book does not conceal that dependence. If the registry stops, the pre-resolution rows stop with their outcomes empty, and that becomes the final record. **That possibility, too, remains in the history.**

---

The registry grows from here. One writer; verifiers, anyone.

Rows accumulate. Deadlines arrive. Outcomes fill if the author writes them and stay empty if the author does not. This book records either, as it stands.

On 22 March 2023, six months were demanded. Whether those six months came, this book did not write. The party that made the demand wrote it, one year later. This book placed that.

Every row after it is placed the same way.

---
