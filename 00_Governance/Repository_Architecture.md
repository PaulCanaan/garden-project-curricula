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
