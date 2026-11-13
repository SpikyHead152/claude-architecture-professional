# ADR 0001: Repository conventions

- **Status:** Accepted
- **Date:** 2026-11-13

## Context
The repo started with a README whose folder names (`01-solution-design/`, …) differed from the project spec (`domain-01-solution-architecture/`, …). No folders existed yet. The official exam guide is Anthropic's document and may change.

## Decisions
1. **Folder naming:** use the descriptive spec style (`domain-NN-<name>/`). Nothing existed to rename, so the cost was zero.
2. **Exam guide:** link to it and keep an own-words summary in `exam-blueprint/official-domain-map.md` rather than committing the PDF.
3. **Evidence standard:** an objective is *Demonstrated* only with an artifact, a test or measurement where applicable, and an unaided explanation (see the tracker).
4. **Planned vs implemented:** anything not yet built is labelled *(planned)* in the README.

## Consequences
- The guide summary can drift from the guide. Mitigation: it states the guide version and says to re-check.
- The README must be updated whenever a folder is actually created.

## Alternatives considered
- Numeric short names, as in the original README: shorter, but opaque to a reader.
- Committing the PDF: self-contained, but redistributes Anthropic's document and goes stale.
