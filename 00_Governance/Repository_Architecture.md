# Repository Architecture

## Status

- Version: 1.0
- Status: Active
- Scope: The Garden Project Curricula repository
- Maintainer: Paul Zhang
- Repository: `garden-project-curricula`

---

## 1. Purpose

The Garden Project Curricula repository is the curriculum-development system
for The Garden Project.

It exists to develop, organize, review, and publish Bible study curricula that
are:

1. biblical-outlined
2. Christ-centered
3. formation-oriented

This repository is not primarily a personal research vault. It is a product
repository for turning biblical-theological research into teachable,
facilitatable, and reusable formation journeys.

---

## 2. Relationship to Christian Worldview OS

The Garden Project Curricula repository is intellectually downstream from the
Christian Worldview OS, but it is independently versioned and maintained.

### Christian Worldview OS owns

- canonical theological research
- biblical theology
- Christian philosophy
- hermeneutics
- doctrine
- formation theology
- book notes
- scholarly synthesis
- long-form writing
- worldview development

### Garden Project Curricula owns

- curriculum architecture
- curriculum-specific research synthesis
- session design
- leader guides
- participant materials
- reusable frameworks
- experiential programs
- workshops
- Scripture indexing
- quality review
- publication-ready curriculum assets

### Governing principle

> Knowledge belongs upstream; curriculum adaptation belongs downstream.

The curricula repository may summarize, adapt, and apply material from the
Christian Worldview OS, but it should not become a duplicate theological
knowledge base.

Whenever practical, curriculum research notes should identify their canonical
upstream source.

Example:

```yaml
canonical_source:
  repository: Christian Worldview OS
  path: Biblical Theology/Temple/Temple Theology.md
adapted_for:
  - God With Us
````

---

## 3. Architectural Principles

### 3.1 Single source of truth

Each substantial idea, framework, program, or research asset should have one
primary home.

Do not maintain parallel copies of the same canonical content in multiple
folders.

### 3.2 Separation of concerns

Research, curricula, frameworks, programs, workshops, indexes, and quality
standards are distinct asset types and should remain structurally separate.

### 3.3 Reuse before duplication

Shared assets should be referenced from the appropriate library rather than
copied into individual curricula.

### 3.4 Product-oriented organization

The repository should be organized around the work required to produce,
facilitate, review, and publish curricula.

### 3.5 Progressive complexity

The curriculum sequence should reflect increasing interpretive and theological
challenge.

### 3.6 Small, reviewable changes

Major restructuring, migrations, and curriculum revisions should be completed
through focused commits and branches.

---

## 4. Top-Level Structure

```text
00_Governance/
01_Research_Reservoir/
02_Curricula/
03_Framework_Library/
04_Program_Library/
05_Workshop_Library/
06_Scripture_Index/
07_Quality_Gates/
tools/
```

---

## 5. Folder Responsibilities

## 5.1 `00_Governance/`

Purpose: Define the identity, boundaries, standards, and operating decisions of
the repository.

Contains:

* Curriculum DNA
* theological boundaries
* source hierarchy
* curriculum progression
* naming conventions
* repository architecture
* decision log
* development policies

Belongs here:

* standards that apply across the entire repository
* accepted architecture decisions
* definitions of repository-wide terms
* source and citation policies

Does not belong here:

* curriculum session content
* general theological research
* facilitator notes for a specific course
* reusable programs or frameworks

Key files:

```text
Curriculum_DNA.md
Curriculum_Progression.md
Theological_Boundaries.md
Source_Hierarchy.md
Naming_Conventions.md
Repository_Architecture.md
Decision_Log.md
```

---

## 5.2 `01_Research_Reservoir/`

Purpose: Hold curated research that directly supports curriculum development.

Suggested structure:

```text
Themes/
Passages/
Scholars/
Historical_Context/
Biblical_Languages/
Bibliographies/
Research_Briefs/
```

Belongs here:

* theme summaries prepared for curriculum use
* passage dossiers
* historical and cultural context
* scholar profiles or position summaries
* bibliographies
* research questions
* curriculum research briefs
* interpretive tensions that require resolution

Does not belong here:

* raw personal notes copied wholesale from Christian Worldview OS
* final session scripts
* general reading notes with no curriculum use
* reusable facilitation activities

Each research note should ideally answer:

1. What is the research question?
2. What are the key passages?
3. What are the major interpretive positions?
4. What is the curriculum-relevant conclusion?
5. What remains uncertain?
6. Which curricula use this material?
7. What is the upstream canonical source?

---

## 5.3 `02_Curricula/`

Purpose: Hold complete multi-session curriculum products.

Current curriculum pathway:

```text
Planted/
Covenant_Kingdom_People/
God_With_Us/
Thus_Says_the_LORD/
```

Curriculum levels:

| Level | Curriculum                           | Primary Emphasis                                              |
| ----- | ------------------------------------ | ------------------------------------------------------------- |
| 100   | Planted.                             | Biblical storyline, gospel foundations, spiritual formation   |
| 200   | Covenant, Kingdom, and People of God | Covenant identity and the people of God                       |
| 300   | God With Us                          | Temple theology and God's dwelling presence                   |
| 400   | Thus Says the LORD                   | Prophetic literature, theological synthesis, embodied witness |

A curriculum folder may contain:

```text
README.md
Overview/
Sessions/
Leader_Guide/
Participant_Materials/
Research/
Appendices/
Assets/
```

Not every curriculum must use all subfolders immediately. Structure should grow
with actual need rather than through empty placeholders.

Each curriculum README should identify:

* curriculum level
* intended audience
* central biblical movement
* learning and formation outcomes
* session structure
* core passages
* shared frameworks
* shared programs
* associated workshops
* current development status

Belongs here:

* curriculum overview
* session manuscripts
* curriculum-specific leader material
* participant handouts
* curriculum-specific appendices
* course-specific research synthesis

Does not belong here:

* canonical versions of shared frameworks
* canonical versions of shared programs
* standalone workshops
* broad research unrelated to the course

---

## 5.4 `03_Framework_Library/`

Purpose: Hold reusable conceptual, interpretive, formation, and facilitation
frameworks.

Suggested categories:

```text
Bible_Study/
Biblical_Theology/
Formation/
Evangelism/
Facilitation/
```

Examples:

* S.O.A.P.
* Grace-Truth Matrix
* Gospel Flow
* Know / Grow / Go
* PLANT
* Already / Not Yet
* Exodus Road
* Five Echoes
* Building a House
* Belonging / Beholding / Becoming

A framework is:

> A reusable lens, model, sequence, or conceptual structure that helps people
> interpret Scripture, understand formation, or organize faithful action.

A framework is not:

* a complete curriculum
* a one-time activity
* a standalone workshop
* a raw research note

Each framework should ideally contain:

```text
README.md
Biblical_Basis.md
Use_Cases.md
Facilitator_Notes.md
Curriculum_References.md
```

Only create these files when needed.

---

## 5.5 `04_Program_Library/`

Purpose: Hold reusable experiential learning and group formation activities.

Suggested categories:

```text
Experiential_Learning/
Discussion/
Prayer/
Worship/
Community_Formation/
```

Examples:

* The Grid
* Dartboard
* Testimony Sharing
* Perspective Shift
* Learning to Handstand in Five Minutes
* The Bond

A program is:

> A facilitated activity, exercise, practice, or group experience designed to
> embody or illuminate a biblical or formation principle.

Each program should identify:

* purpose
* theological or biblical connection
* required materials
* group size
* duration
* setup
* facilitator instructions
* discussion questions
* safety or accessibility considerations
* curriculum uses

Programs should not contain the full theology of a curriculum. They should
reference the relevant framework, passage, or curriculum.

---

## 5.6 `05_Workshop_Library/`

Purpose: Hold focused teaching experiences that are larger than a single
program but smaller and more concentrated than a full curriculum.

Suggested structure:

```text
Curriculum_Associated/
Standalone/
```

Examples:

### Curriculum-associated

* Eternity Planted
* From Planted to Plant
* The Exodus Road Workshop
* The Church Workshop

### Standalone

* Christianity as Counterculture
* Forming a Reading Culture

A workshop is:

> A focused teaching and formation experience that can be delivered in one or
> several concentrated sessions.

Workshops remain structurally independent because they may:

* support an existing curriculum
* introduce a future curriculum
* function as a standalone product
* later develop into a larger course

---

## 5.7 `06_Scripture_Index/`

Purpose: Track how Scripture is used across the curriculum ecosystem.

Suggested contents:

```text
Canonical_Index.md
Theme_Index.md
Curriculum_Crosswalk.md
generated/
```

The Scripture Index should eventually support questions such as:

* Where is Genesis 1 used?
* Which curricula address temple theology?
* Which passages recur across multiple curricula?
* Are certain biblical books overused or neglected?
* Which passages are primary texts versus supporting references?

Generated files should be clearly marked and should not be manually edited
unless explicitly designed for mixed manual and generated maintenance.

---

## 5.8 `07_Quality_Gates/`

Purpose: Define the standards a curriculum asset must meet before release.

Core quality gates:

1. Biblical Outline
2. Christological Coherence
3. Canonical Coherence
4. Formation Outcome
5. Audience and Level Fit
6. Facilitator Usability
7. Scripture Accuracy
8. Source Traceability
9. Reusability and Correct Placement
10. Publication Readiness
11. Accessibility and Safety
12. Link and Metadata Integrity

Quality gates may include:

* checklists
* review rubrics
* release criteria
* peer-review templates
* validation reports

A curriculum should not be considered release-ready merely because all sessions
have been drafted.

---

## 5.9 `tools/`

Purpose: Hold repository-specific scripts and automation.

Current or planned tools:

```text
validate-scripture-refs/
build-scripture-index/
generate-research-brief/
validate-links/
validate-frontmatter/
```

Tooling principles:

* scripts should solve recurring repository problems
* tools should be documented
* generated output should be reproducible
* destructive actions should require explicit confirmation
* validation should fail clearly and explain how to repair issues

Generic tools that later serve multiple repositories may eventually be moved to
a shared tools repository, but project-local tooling is preferred during early
development.

---

## 6. Asset Classification

Use the following questions to decide where an item belongs.

### Is it canonical research or worldview development?

Place it in Christian Worldview OS.

### Is it curated research for a particular curriculum question?

Place it in `01_Research_Reservoir/`.

### Is it a multi-session formation journey?

Place it in `02_Curricula/`.

### Is it a reusable interpretive or formation model?

Place it in `03_Framework_Library/`.

### Is it a facilitated activity or exercise?

Place it in `04_Program_Library/`.

### Is it a concentrated teaching product?

Place it in `05_Workshop_Library/`.

### Is it a Scripture cross-reference or generated index?

Place it in `06_Scripture_Index/`.

### Is it a review standard or release check?

Place it in `07_Quality_Gates/`.

### Is it automation or validation code?

Place it in `tools/`.

---

## 7. Naming Conventions

Detailed naming rules are maintained in `Naming_Conventions.md`.

Repository-wide defaults:

* top-level system folders use numeric prefixes and underscores
* curriculum titles may preserve their public-facing names in content
* folder names should be stable, readable, and shell-safe
* avoid unnecessary punctuation in paths
* use descriptive filenames
* MOC files should not duplicate README responsibilities without a clear reason
* acronyms may remain uppercase when they are official framework names

Examples:

```text
02_Curricula/God_With_Us/
03_Framework_Library/Bible_Study/SOAP/
04_Program_Library/Experiential_Learning/The_Grid/
```

---

## 8. Internal Linking

Preferred practices:

* use Obsidian wiki links for internal knowledge navigation
* use relative Markdown links where GitHub portability is important
* avoid hard-coded absolute local paths
* update links whenever files move
* validate links before merging major refactors

A moved file is not considered fully migrated until its inbound and outbound
links have been reviewed.

---

## 9. Metadata

Important repository assets should progressively adopt consistent front matter.

Suggested baseline:

```yaml
---
type: curriculum
status: active
level: 300
audience:
  - growing believers
themes:
  - temple
  - presence
  - new creation
upstream_sources:
  - Christian Worldview OS
---
```

Metadata should support actual search, validation, indexing, or publishing. Do
not add fields that are never used.

---

## 10. Curriculum Development Workflow

The standard development flow is:

```text
Research Reservoir
        ↓
Curriculum Proposal
        ↓
Biblical and Theological Outline
        ↓
Session Architecture
        ↓
Session Drafts
        ↓
Framework Integration
        ↓
Program Integration
        ↓
Leader Guide
        ↓
Participant Materials
        ↓
Quality Gates
        ↓
Pilot
        ↓
Revision
        ↓
Release
```

### Stage 1 — Research

Clarify the central biblical question, major passages, theological movement,
historical context, and scholarly tensions.

### Stage 2 — Proposal

Define:

* audience
* level
* purpose
* biblical movement
* formation outcomes
* scope
* estimated number of sessions

### Stage 3 — Architecture

Develop the course outline from Scripture rather than from a merely topical
sequence.

### Stage 4 — Drafting

Draft sessions, transitions, questions, practices, and leader notes.

### Stage 5 — Integration

Reference or develop the frameworks, programs, and workshops that support the
curriculum.

### Stage 6 — Review

Run the relevant quality gates.

### Stage 7 — Pilot

Test the curriculum with real participants and facilitators.

### Stage 8 — Revision

Record feedback, revise content, and document major decisions.

### Stage 9 — Release

Prepare the approved formats and assign a release version.

---

## 11. Git Workflow

### Main branch

`main` should remain stable and usable.

### Feature and refactor branches

Use focused branches for substantial work.

Examples:

```text
feat/god-with-us-leader-guide
research/temple-presence
refactor/scripture-index
fix/broken-wiki-links
```

### Commit principles

Commits should be:

* focused
* reviewable
* descriptive
* reversible

Examples:

```text
feat(curriculum): add God With Us session architecture
research(temple): add Ezekiel temple dossier
refactor(programs): classify Planted activities
fix(links): repair framework references
docs(governance): clarify source hierarchy
```

### Major architecture changes

Major changes should:

1. be documented in the Decision Log
2. use a branch
3. preserve history with `git mv` where practical
4. include link validation
5. be reviewed before merging to `main`

---

## 12. Decision Records

Architecture decisions that affect multiple folders or future development
should be recorded in `Decision_Log.md`.

Examples:

* relationship to Christian Worldview OS
* separation of workshops and programs
* curriculum level system
* metadata schema
* release process
* generated Scripture index policy

Small editorial choices do not require formal decision records.

---

## 13. Definition of Done

A new repository asset is not complete merely because a file exists.

### A framework is done when

* its purpose is clear
* its biblical basis is stated
* its use cases are documented
* its curriculum references are known

### A program is done when

* a facilitator can run it without the author present
* materials and timing are clear
* discussion questions are included
* safety and accessibility concerns are addressed

### A curriculum session is done when

* the primary text is clear
* the session serves the curriculum movement
* Christological integration is coherent
* formation outcomes are explicit
* leader instructions are usable
* Scripture and sources are traceable

### A curriculum is release-ready when

* its architecture is complete
* all required sessions and guides exist
* quality gates are passed
* pilot feedback has been reviewed
* broken links and metadata errors are resolved
* publication formats are prepared

---

## 14. Architecture Change Policy

This architecture is stable but not immutable.

A change is justified when it:

* removes recurring friction
* clarifies ownership
* improves reuse
* improves publishing
* improves validation
* supports collaboration
* reflects an actual new asset type

A change is not justified merely because a different folder structure appears
more elegant.

Before changing the top-level architecture:

1. identify the recurring problem
2. document the proposed solution
3. assess migration cost
4. record the decision
5. implement through a branch
6. validate links and repository integrity
7. update this document

---

## 15. Current Architecture

The approved version 1 structure is:

```text
00_Governance/
01_Research_Reservoir/
02_Curricula/
03_Framework_Library/
04_Program_Library/
05_Workshop_Library/
06_Scripture_Index/
07_Quality_Gates/
tools/
```

This structure represents the movement from governance and research toward
curriculum products, reusable assets, validation, and publication.
