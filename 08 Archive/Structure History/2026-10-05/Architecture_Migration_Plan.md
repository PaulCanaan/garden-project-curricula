# Architecture Migration Plan

## Repository Relationship

- Christian Worldview OS: canonical research, theology, philosophy, and formation
- Garden Project Curricula: curriculum architecture, adaptation, facilitation, and delivery

## Current-to-Target Mapping

| Current Path | Target Path |
|---|---|
| `01 Bible Study Curricula/` | `02_Curricula/` |
| `02 Program Library/` | `04_Program_Library/` |
| `03 Framework Library/` | `03_Framework_Library/` |
| `04 Workshop Library/` | review before migration |
| Research notes | `01_Research_Reservoir/` |
| Scripture references | `05_Scripture_Index/` |
| Review standards | `06_Quality_Gates/` |
| Repository scripts | `tools/` |

## Migration Rules

1. Prefer `git mv`.
2. Do not duplicate canonical research.
3. Shared frameworks belong in the Framework Library.
4. Shared activities belong in the Program Library.
5. Migrate in small commits.
