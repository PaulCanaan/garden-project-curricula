---
type: index
status: active
source_system: Google Drive
imported: 2026-10-05
owner: The Garden Project
---

# Google Drive Import — 2026-10-05

This folder is the **source layer** for Garden Project curriculum material found in Paul's Google Drive that was not already in this repository or in the [Notion import](../Notion_2026-10-05/README.md). It follows the procedure in [AGENTS.md](../../../AGENTS.md): every file here is a **source record**, not canonical content. Nothing was merged into canonical files in `02_Curricula/`, `03_Framework_Library/`, `04_Program_Library/` or `04 Workshop Library/`. Where a canonical counterpart exists, the source file names it in `canonical_counterpart` and lists the differences in `review`. Every file has `source_status: Inbox`.

## How the files were made

- **Google Docs** were exported from Drive as Markdown. Headings, lists and quotes were kept.
- **Google Slides, PowerPoint, PDF and Word files** were read as text. Slide decks are written as `## Slide n` sections. Where the export did not mark slide breaks (PDF and PPTX), the slide headings were added at import and say so. Diagram text is given as "Diagram labels". Image-only slides are noted, not described.
- **Wording was not rewritten.** Formatting was normalized: bold removed from headings, escape characters and invisible direction marks removed, verse lists and tables set as Markdown. Errors that change meaning are kept and marked `[sic]`. Two PDF slides in *The Church* came out scrambled and were reassembled; each carries an import note.
- **Added text** is always marked: import notes in *[italic brackets]*, and the English summary in the Chinese deck is a callout labelled "added at import".
- Each file records `url` (the Drive link), `last_edited` (Drive modified date) and `imported`, so it can be compared with Drive later. `title` is the file's name in Drive.

## Redactions

This repository is public (see CONTRIBUTING). Recorded in each file's `redactions` field:

| File | Redaction |
|---|---|
| `Planted/The Story of Planted (recap slides).md` | About 20 member names on the thank-you slide replaced with `[member names omitted]` |
| `Planted/Planted 2026 Session 0 Introduction - Golden City Church Bible Club (slides).md` | Lyrics of "Tend" (Emmy Rose / Bethel Music) omitted; the song title and CCLI line are kept |
| `Workshops/From Planted to Plant (workshop deck).md` | Speaker introduction slide: family background and parents' ministry removed; the public-ministry introduction is kept |

Slide photographs and background images were not imported. No other file needed redaction; the CKPG leader guide names no participants.

## Folder map and manifest

| Folder | File | From Drive | Canonical counterpart |
|---|---|---|---|
| `Planted/` | [The Seed and the Soil (Drive 2026-09-10)](Planted/The%20Seed%20and%20the%20Soil%20(Drive%202026-09-10).md) | Google Doc "The Seed and the Soil" — newest full Session 0 manuscript, incl. "A Prayer for the Soil" | `02_Curricula/Planted/01 Introduction - The Parable of Sowing Seeds.md`; Notion S00 source |
| `Planted/` | [Planted 2026 Session 0 Introduction - Golden City Church Bible Club (slides)](Planted/Planted%202026%20Session%200%20Introduction%20-%20Golden%20City%20Church%20Bible%20Club%20(slides).md) | PDF "Planted. 2026 Session 0 (Introduction).pdf" | same as above |
| `Planted/` | [The Story of Planted (recap doc)](Planted/The%20Story%20of%20Planted%20(recap%20doc).md) | Google Doc "The Story of Planted." (Chapters 1–2 recap, 2025) | `02_Curricula/Planted/00 Planted.md` |
| `Planted/` | [The Story of Planted (recap slides)](Planted/The%20Story%20of%20Planted%20(recap%20slides).md) | Google Slides "The Story of Planted." (end-of-run recap, Feb 2025) | same as above |
| `Workshops/` | [Eternity Planted (workshop deck)](Workshops/Eternity%20Planted%20(workshop%20deck).md) | Google Slides "Eternity Planted" (Planted. 2025 Week 12) | `04 Workshop Library/Curriculum-Associated Workshops/Eternity Planted.md` |
| `Workshops/` | [安置永生 (Eternity Planted, Chinese deck)](Workshops/安置永生%20(Eternity%20Planted,%20Chinese%20deck).md) | PPTX "安置永生（传3：11）.pptx" — Chinese kept, English summary added | same as above |
| `Workshops/` | [From Planted to Plant (workshop deck)](Workshops/From%20Planted%20to%20Plant%20(workshop%20deck).md) | Google Slides "Workshop.pptx" (= Evangelism Workshop.pptx) | `04 Workshop Library/Curriculum-Associated Workshops/From Planted to Plant.md` |
| `Workshops/` | [From Planted to Plant (reflection notes 2024-12)](Workshops/From%20Planted%20to%20Plant%20(reflection%20notes%202024-12).md) | Google Doc "From Planted to Plant" | same as above |
| `Workshops/` | [Forming a Reading Culture - Workshop Handout](Workshops/Forming%20a%20Reading%20Culture%20-%20Workshop%20Handout.md) | DOCX "Presentation Notes.docx" | `04 Workshop Library/Standalone Workshops/Forming a Reading Culture.md` |
| `Workshops/` | [The Church (workshop deck)](Workshops/The%20Church%20(workshop%20deck).md) | PDF "The Church.pdf" | `04 Workshop Library/Curriculum-Associated Workshops/The Church Workshop.md` (materially different) |
| `Covenant_Kingdom_People/` | [CKPG Facilitation Note 2025-11-03](Covenant_Kingdom_People/CKPG%20Facilitation%20Note%202025-11-03.md) | Google Doc "Facilitation Note 11/03/25" | `02_Curricula/Covenant_Kingdom_People/01 Week 1 - Universal Covenant.md` (and Week 2) |
| `Covenant_Kingdom_People/` | [CKPG Leader Guide - 15 Lessons (Copy of CKPG, 2025-10)](Covenant_Kingdom_People/CKPG%20Leader%20Guide%20-%2015%20Lessons%20(Copy%20of%20CKPG,%202025-10).md) | Google Doc "Copy of Covenant, Kingdom, and People of God" — **author unconfirmed** | `02_Curricula/Covenant_Kingdom_People/00 Covenant Kingdom and People of God.md` |
| `Frameworks/` | [Train Your Faith Muscle (raw source)](Frameworks/Train%20Your%20Faith%20Muscle%20(raw%20source).md) | Google Doc "Train Your Faith Muscle" | `03_Framework_Library/Formation/Faith_Muscle/Faith Muscle.md` |

## Catalogued, not imported

### Already integrated or duplicate

| Drive file | Drive ID | Reason |
|---|---|---|
| Planted. Summer 2026 (Google Doc) | `1aDs7dcqoBLisAJsgqnwOSVn0QzBgIIfz2njGtMx_Yog` | Already mapped in `02_Curricula/Planted/C Planted Source Integration Map.md` |
| In the Beginning, a Garden (Google Doc) | `173zsFNtP22kg4St-QHy-_-yQqnM6tgZflwa8auGtG44` | Older than the Notion S01 source (`Notion_2026-10-05/Curricula/Planted/S01 In the Beginning, a Garden (Notion).md`) |
| Building a House (Google Doc) | `12TJoSyg1bpsSfePHC1uCHhArIZ5_3qmwXeT1rR4Vjkc` | The canonical program already cites it |
| God with Us, chapter 1 (Google Doc) | `1hUxqA1vzeuPAx2nteyd1OKnEyF4cXR9FeR1fQ1cevJ0` | Published as a Substack essay |
| God with Us, chapter 2 (Google Doc) | `1NXAK0c8SEILJVPHJDLj8VsCLo5oH9etm4IFhBaF8AgA` | Published as a Substack essay |
| Word Study (Google Doc) | `1I-fPLsxkkOjQER90s2p5Mq6oMY-7puYh3l_ozZXArsQ` | Integrated as Bible Word Study Practice; also contains third-party text |
| Covenant Study Workbook.pdf | `1vE4MbFBrGqkY3SW-o9LqvpipDBLL7YSe` | Print edition of the canonical CKPG study |
| Handout (Google Doc) | `1rORWwMVKfMoNTk3NwUy1ij09IEwudf3pSs_rcmcK_lY` | SOAP handout, same as the Notion SOAP source |
| 逆行者.docx | `1v53Ll5Li1GG1go9pdajNhSJ3lqZJSH-_` | Only a title: "Planted Vol. 5 / From Planted to Plant" |
| Evangelism Workshop.pptx | `1S-eDdibihkECxa4gF3Duel5CmmXB_9ZP` | Duplicate of the From Planted to Plant deck (`Workshops/From Planted to Plant (workshop deck).md`) |

### Image-only Canva exports (need a text export from Canva)

| Drive file | Drive ID | Canonical note it would serve |
|---|---|---|
| The Exodus Way Workshop.pdf | `17ahX31xOV9X2i1-bOd_rlbWCfmWGtKZ0` | `04 Workshop Library/Curriculum-Associated Workshops/The Exodus Road Workshop.md` |
| Christianity As Counterculture (PDF) | `18H1vbI3lIIA-5UmDIFNfvidpmEbB96ch` | `04 Workshop Library/Standalone Workshops/Christianity as Counterculture.md` |
| CKPG Introduction Presentation.pdf | `1Ltlf_lS-OPKG25qjyMrcaJkqh0FD7r-J` | `02_Curricula/Covenant_Kingdom_People/` |

### Third-party material (not ours to republish)

- **PLANT-All-Lessons-2022** — Bridges International. Already excluded from the Notion import for the same reason. Link to the PLANT site instead.
- **cojourners-training-leaders-guide.pdf** — Cru.
- **Kline Kingdom Chart** — Lee Irons / Meredith Kline.
- **LL Scripture Field Guide** and **LL Norms Article** — Lifelines.

### Ministry admin with member names

Not imported because they name members and leaders: **Co-journers.pptx** (2025-05-18 leaders meeting), **Group Leader Policies** (draft), **Pastoral Approval Brief**, **Fall 2026 Group Profile Cards**.

## Decisions for human review

The SOP reserves canonical decisions for a person. These came up during this import:

1. **CKPG leader guide authorship.** The 15-lesson guide has no byline and may be AI-drafted or a co-leader's work. Confirm who wrote it, and whether it was used, before reusing any of it. Its 15-lesson structure is not the canonical five-week structure.
2. **The Church workshop.** The Drive deck (Five Axes, Theological Pyramid, church history) is a general ecclesiology workshop; the canonical note is the temple-storyline capstone of God With Us. Decide whether they are one workshop or two.
3. **The Grid as taught in 2026.** The Golden City Church slides still use burpees and required continuous eating, which the manuscript and canonical Introduction softened. This adds to decision 5 in the Notion README.
4. **Five chapters vs twelve sessions.** The 2026 slides say "five chapters and five recurring frameworks" but list the ten-step journey of the 12-session map. This adds evidence to Notion README decision 1.
5. **Attribution in the CKPG facilitation note.** Several lines paraphrase O. Palmer Robertson, *The Christ of the Covenants*, without credit. Attribute and rephrase before any canonical use.
6. **Faith Muscle.** Decide whether any raw lines not carried into the canonical framework (for example "faith +", the Planet Fitness line, endorphins vs dopamine) should come back.
7. **Recovered decks.** The canonical Eternity Planted and From Planted to Plant notes are marked `recovery-needed`. The decks are now here as sources; reconciling them is the next step on those notes' checklists.
