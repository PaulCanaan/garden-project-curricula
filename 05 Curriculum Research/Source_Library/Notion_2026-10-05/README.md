---
type: index
status: active
source_system: Notion
imported: 2026-10-05
owner: The Garden Project
---

# Notion Import — 2026-10-05

This folder is the **source layer** for everything in the Notion workspace *Garden Project Curricula* that was not already in this repository. It follows the procedure in [AGENTS.md](../../../AGENTS.md): every file here is a **source record**, not canonical content. Nothing was merged into canonical files in `02_Curricula/`, `03_Framework_Library/` or `04_Program_Library/`. Where a canonical counterpart exists, the source file names it in `canonical_counterpart` and lists the differences in `review`.

The two exceptions are new **draft** workshop pages created from Notion workshop overviews, which had no counterpart in the repository: [Rooted Through the Seasons](../../../04%20Workshop%20Library/Curriculum-Associated%20Workshops/Rooted%20Through%20the%20Seasons.md) and [Every Seed Tells a Story](../../../04%20Workshop%20Library/Curriculum-Associated%20Workshops/Every%20Seed%20Tells%20a%20Story.md). Both are marked `development_status: draft` and `source_status: imported-needs-review`.

Personal material (testimonies) and the private knowledge-base parts of the Notion workspace went to the private Christian Worldview vault, not here.

## How the files were made

- Content was read through the Notion API and converted to Markdown. Headings, lists, tables, callouts and footnotes were kept. Toggles were expanded. Notion database views were turned into tables.
- **Wording was not rewritten.** Source errors that change meaning are kept and marked `[sic]`. Formatting was normalized (heading levels, Markdown tables in place of Notion columns), and a few minor spelling and punctuation slips may have been corrected during conversion. Check the Notion page (`notion_url`) before quoting a source word for word.
- **Redactions**, all recorded in each file's `redactions` field: participant names, home hosts and addresses, leader self-introductions, and participant photos. This repository is public (see CONTRIBUTING).
- **Images** were downloaded only when they are the ministry's own diagrams. Stock photos, cover images and photos of people were left in Notion.
- Each file records `notion_url` and `notion_last_edited` so it can be compared with Notion later.

## Folder map

| Folder | What it holds | Canonical area it serves |
|---|---|---|
| `Frameworks/` | Notion framework pages: Grace–Truth Matrix (full and simplified) and SOAP | `03_Framework_Library/` |
| `Programs/` | Notion program pages: The Grid, Dartboard, Storytelling, Perspective Shift and The Bond | `04_Program_Library/Experiential_Learning/Planted_Programs/` |
| `Session_Notes/` | Notes from running *The Grid* | same as above |
| `Templates/` | Notion page templates and the Planted standard formats | `00_Governance/`; the vault's `90 Templates` |
| `Design_Principles/` | "Designing Principles" (Planted example, BBB, Inhabit the Story, modular Bible study formats) | `00_Governance/Curriculum_DNA.md` |
| `Curricula/Planted/` | Planted overview, storyline, session pages, leader notes, leader resources, resource library and diagrams | `02_Curricula/Planted/` |
| `Curricula/Covenant_Kingdom_People/` | CKPG learning objectives, final project and dashboard summary | `02_Curricula/Covenant_Kingdom_People/` |
| `Planted_Source_Archive/` | Raw Planted sources: 2025 weekly sessions, Vols. 1, 2 and 4, English translations, Chinese originals (耕心), Session 8 draft and the style guide | `02_Curricula/Planted/` and related frameworks |

Related outputs outside this folder:

- [AGENTS.md](../../../AGENTS.md) — the Notion "AGENTS.md" source-layer SOP, unchanged
- [Planted Sources Scripture Index (Notion 2026-08-04)](../../../06%20Scripture%20Index/Planted%20Sources%20Scripture%20Index%20(Notion%202026-08-04).md)

## Notion page manifest

### Curricula workspace

| Notion page | Result | Location / reason |
|---|---|---|
| Introduction | Not imported (duplicate) | Same text as the repository README |
| AGENTS.md | Imported | `/AGENTS.md` |
| Designing Principles (+ 5 child pages) | Imported | `Design_Principles/` |
| Curricula Board (Planted., CKPG, God With Us, Thus Says the LORD) | Recorded only | Board pages are blank. Status from the board: Planted = Ready for Review, Beginner; CKPG = Published, Intermediate; God With Us = In Development, Intermediate; Thus Says the LORD = Advanced |
| Curriculum and Curriculum Sessions databases | Template only | No records. Templates in `Templates/Curriculum and Curriculum Session Database Templates (Notion).md` |
| God With Us → Sessions; Thus Says the LORD → Sessions | Not imported (empty) | Databases have no rows |
| Framework Library: Grace–Truth Matrix, Grace–Truth Matrix Simplified, SOAP | Imported | `Frameworks/` |
| Framework Library: Grace–Truth Matrix part 2 | Blank in Notion | Recorded in the part 1 file |
| Framework Library: Gospel Flow, Know·Grow·Go, PLANT | Blank in Notion | — |
| Framework database (collection 3f739243…) and page c01ec739… | Not accessible (404) | Retry later in Notion |
| Program Library: The Grid, Dartboard, Storytelling, Perspective Shift, The Bond | Imported | `Programs/` |
| The Grid — session notes | Imported | `Session_Notes/` |
| Session, Session Leader Notes, Program, Framework, Workshop and Curriculum Overview templates | Imported | `Templates/` |
| Covenant, Kingdom, and People of God: Overview, Learning Objectives, Final Project, Dashboard | Imported | `Curricula/Covenant_Kingdom_People/` |
| CKPG Weeks 1–5 and Appendices 1–3 | Not imported (already integrated) | Same content and date (2026-06-04) as the Google Docs originals integrated on 2026-07-25 |
| Planted.: Overview, More About, Formation Goal, Formation Rhythm, Modular formats | Imported | `Curricula/Planted/Planted Overview (Notion).md` |
| Planted.: Storyline | Imported | `Curricula/Planted/Storyline of Planted (Notion).md` |
| Planted.: All Sessions database (S0, S1, S3 with content; S2, S4–S10, Epilogue with epigraphs only) | Imported | `Curricula/Planted/` session files, `Session Stubs - Epigraphs Only (Notion).md`, `Planted Session Map (Notion databases).md` |
| Planted.: Leader Notes database (S0, S1 with content) | Imported | `Curricula/Planted/S00 Leader Notes (Notion).md`, `S01 Leader Notes (Notion).md` |
| Planted.: Leader Notes S2–S11 | Empty scaffolds | Big Ideas recorded in the session map |
| Planted.: Leader Resources (7 pages) | Imported | `Curricula/Planted/Planted Leader Resources (Notion).md` |
| Planted.: Resource Library (Book Club and 7 diagrams) | Imported | `Curricula/Planted/Planted Resource Library (Notion).md`, `assets/` |
| Planted.: Workshop overviews | Imported as drafts | `04 Workshop Library/Curriculum-Associated Workshops/` |
| CoJourner Program; My Notion AI | Moved to the private vault | Ministry and personal-workflow notes |

### Inbox → Planted. Sources

Notion database *Planted Source Library* (33 rows). "Processing" is the Notion status at import time.

| Source (Notion title) | Notion processing | Result |
|---|---|---|
| Planted. 2025 Week 1 | Inbox | `Planted_Source_Archive/Planted 2025 Week 1.md` |
| Planted. 2025 Week 2 | Inbox | `Planted 2025 Week 2.md` |
| Planted. 2025 Week 3 | Inbox | `Planted 2025 Week 3.md` |
| Planted. 2025 Week 4 Program | Inbox | `Planted 2025 Week 4 Program.md` |
| Planted. 2025 Week 5 | Inbox | `Planted 2025 Week 5.md` |
| Planted. 2025 Week 6 | Inbox | `Planted 2025 Week 6.md` (participant names and host redacted) |
| Planted. 2025 Week 7 | Inbox | `Planted 2025 Week 7.md` |
| Planted. 2025 Week 8 | Inbox | `Planted 2025 Week 8.md` |
| Planted. 2025 Week 9 | Inbox | `Planted 2025 Week 9.md` |
| Planted. 2025 Week 12 | Extracted | `Planted 2025 Week 12.md` (leader self-introduction redacted) |
| Planted. 2025 Week 13 Program | Inbox | `Planted 2025 Week 13 Program.md` (participant photo left out) |
| Week 13 Program Facilitator copy | Inbox | Covered by the Week 13 file, with the differences noted there |
| There Is A Garden Named Delight_ (Vol. 1) | Inbox | `Planted Vol 1 - There Is A Garden Named Delight.md` |
| Devil Not Today (Vol. 2) and Devil Not Today(1) | Inbox | `Planted Vol 2 - Devil Not Today.md` (the (1) copy is a duplicate) |
| See The Other Side (Vol. 4) | Extracted | `Planted Vol 4 - See The Other Side.md` (stock image left out) |
| S. O. A. P. Framework | Inbox | `SOAP Framework (source note).md` |
| Replacement Reaction (EN) | Inbox | `Replacement Reaction (EN translation).md` |
| Devil Not Today (EN) | Inbox | `Devil Not Today - Say No to the Enemy (EN translation, 2023).md` |
| Already / Not Yet (EN) | Extracted | `Already - Not Yet (EN translation).md` |
| Planted. Chinese version — 耕心: 向仇敌说不, 永生角度的已然、未然, 置换反应 | Inbox | `Planted_Source_Archive/Chinese_耕心/` |
| Planted. Chinese version — 耕心: 逆行者 | Inbox | Not imported: stub page with no text and no English translation |
| Session 8 — Eternity Planted (Leader Notes v1 — Draft for Human Review) | Draft | `Session 8 - Eternity Planted (Leader Notes v1 - Draft for Human Review).md` (includes decision HR-001) |
| Planted — Writing & Formatting Style Guide | Reviewed | `Planted - Writing and Formatting Style Guide.md` |
| Planted — Weekly Session / Framework / Program (Standard Format) | Reviewed | `Templates/Planted - … (Notion).md` |
| Planted — Scripture Index | Inbox | `05_Scripture_Index/Planted Sources Scripture Index (Notion 2026-08-04).md` |
| Planted — Weeks 1–13 (Rewritten) | Inbox | **Not imported:** [Notion](https://app.notion.com/p/fda26a9575a846b690ad1fe465c474b2). Notion AI rewrites of the sources above, marked "not canonical" in Notion |
| Planted — Frameworks (Rewritten) | Inbox | **Not imported:** [Notion](https://app.notion.com/p/5ed61057e14b40719657587e983c976a). Notion AI rewrite |
| Planted — Programs (Rewritten) | Inbox | **Not imported:** [Notion](https://app.notion.com/p/9b97a91718064179a709f0ad0175b1d3). Notion AI rewrite |
| Evangelism Workshop → PLANT-All-Lessons-2022 | Inbox | **Not imported (copyright):** © 2021 Bridges International. Not ours to republish |
| Graves into Gardens lyrics (Planted.zip attachment) | — | **Not imported (copyright):** song lyrics; the session map still names the song |
| My Testimony; Testimony Essay | Inbox | **Moved to the private vault** (`05 Writing/03 Drafts/`): personal and family history |
| Planted.zip folders: Planted. 2024, Planted. 2025, Planted. 2026, Designing Elements; page "Planted. Summer 2026" | — | **Deleted in Notion** (404). The surviving child pages are listed above |

### Not imported anywhere

- **Attachments left in Notion:** the Planted cover tree image, the CKPG Overview photo, PowerPoint decks attached to weekly pages, and stock photos.
- **Synced and linked blocks** the connector could not expand, on the Planted Overview, Leader Resources and Resource Library pages. Each affected file says so in its `review` field.

## Decisions for human review

The SOP reserves canonical decisions for a person. These came up during the import:

1. **Planted structure.** Notion maps 12 sessions (S0 Introduction to S11, plus an Epilogue). `02_Curricula/Planted/` uses an Introduction and five chapters. The Notion storyline and both new workshop drafts follow the 12-session map. Decide which structure is canonical. See `Curricula/Planted/Storyline of Planted (Notion).md`.
2. **Session numbering.** Notion's *All Sessions* list and the SOP count the Introduction as S0. The 2025 weekly sources count it as Week 1.
3. **Perspective Shift vs. "Learning to Handstand in 5 Minutes."** Same program under two names. Choose one.
4. **Grace–Truth Matrix part 2** is blank in Notion. The Week 13 diagram adds *Growth = (Grace + Truth) × Time*, which is not in the canonical framework. Decide whether to add it.
5. **The Grid and Perspective Shift safety.** The Notion version of The Grid keeps burpees, required continuous eating, snack-tossing and rejecting phrases that the canonical program softened for safety and accessibility. It also places the quadrants and timing differently. The Perspective Shift headstand step needs a safety review. See the files in `Programs/`.
6. **Modular formats.** Notion describes 5-week, 12-week and 5-month formats plus Family Dinners. The canonical overview describes adjustable depth only.
7. **Leader Notes.** Notion has full Leader Notes for S0 and S1 and a draft for S8. `02_Curricula/Planted/` has no Leader Guide yet. Decide whether to adopt them.
8. **CKPG final project and learning objectives.** These are not in `02_Curricula/Covenant_Kingdom_People/`. Decide whether to add them.
9. **"Co-journer" wording.** The Planted Overview calls leaders "co-journers"; Designing Principles and the ministry use "CoJourner". Pick one spelling for curriculum text.

Decision HR-001 (Session 8 leader notes, approved 2026-08-04) is copied into [Decision_Log.md](../../../00%20Governance/Decision_Log.md) from the Session 8 draft.

## Path reconciliation — 2026-10-05

The import narrative retains its original folder references as history. Current canonical homes are `01 Bible Study Curricula/`, `02 Program Library/`, `03 Framework Library/`, and `00 Governance/`. The source library now lives under `05 Curriculum Research/Source_Library/`; link destinations and counterpart metadata follow the current paths. Source teaching text and review-needed distinctions remain unchanged.
