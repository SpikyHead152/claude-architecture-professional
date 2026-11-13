# Claude Certified Architect – Professional: Architecture Lab

A hands-on workspace for the **Claude Certified Architect – Professional (CCAR-P)** certification. The goal is not only to pass the exam but to be able to architect, build, evaluate and defend enterprise-grade Claude solutions.

> **Status: day zero.** Only the exam blueprint tracking exists so far. Everything marked *(planned)* below does not exist yet. See [`exam-blueprint/objective-tracker.md`](exam-blueprint/objective-tracker.md) for the honest, current status of every exam objective.

## Source of truth

The official **CCAR-P Exam Guide v1.0 (effective July 2026)** from the [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/page/partner-certifications). The PDF is not committed to this repo; [`exam-blueprint/official-domain-map.md`](exam-blueprint/official-domain-map.md) is my own-words summary of its objectives. Re-check the guide before relying on it, because it is subject to change without notice.

Exam facts (v1.0): 63 items, 120 minutes, multiple-choice and multiple-response, scaled pass mark 720 of 1,000, credential valid 12 months.

## Domains and weights

| # | Domain | Weight | Objectives |
|---|---|---:|---:|
| 1 | Solution Design & Architecture | 17% | 6 |
| 2 | Claude Models, Prompting & Context Engineering | 13% | 5 |
| 3 | Integration | 19% | 8 |
| 4 | Evaluation, Testing & Optimization | 16% | 6 |
| 5 | Governance, Safety & Risk Management | 14% | 5 |
| 6 | Stakeholder Communication & Lifecycle Management | 14% | 5 |
| 7 | Developer Productivity & Operational Enablement | 7% | 3 |

## Repository layout

```text
claude-architecture-professional/
├── README.md
├── CLAUDE.md                          # (planned) project instructions for Claude Code
├── exam-blueprint/                    # EXISTS: domain map, objective tracker, notes index
├── docs/
│   ├── adr/                           # EXISTS: architecture decision records
│   ├── architecture/                  # (planned)
│   ├── diagrams/                      # (planned)
│   ├── security/                      # (planned)
│   └── production-evolution/          # (planned)
├── domain-01-solution-architecture/   # (planned)
├── domain-02-models-prompting-context/  # (planned)
├── domain-03-integration/             # (planned)
├── domain-04-evaluation-optimization/ # (planned)
├── domain-05-governance-safety/       # (planned)
├── domain-06-stakeholder-lifecycle/   # (planned)
├── domain-07-developer-productivity/  # (planned)
├── capstone/                          # (planned) Enterprise Knowledge & Operations Assistant
├── shared/  tests/  evals/  scripts/  # (planned)
└── progress/                          # (planned) learning log, status, weak areas
```

## Stack (local-first)

- **Models:** Claude via the official Anthropic SDK; exact model IDs are pinned per experiment from the official docs.
- **Language:** Python by default; TypeScript only where it is the better fit.
- **Storage:** SQLite and local files first. Infrastructure is added only when an experiment shows why it is needed.
- **Integrations:** Model Context Protocol (MCP), Claude Code, Agent Skills.
- **Diagrams:** Mermaid, always describing what is actually implemented.

## Progress

- [x] Repository initialised and connected to the Claude Project
- [x] Exam coverage matrix created (all 38 objectives, none demonstrated yet)
- [ ] Domain 1: Solution Design & Architecture (17%)
- [ ] Domain 2: Claude Models, Prompting & Context Engineering (13%)
- [ ] Domain 3: Integration (19%)
- [ ] Domain 4: Evaluation, Testing & Optimization (16%)
- [ ] Domain 5: Governance, Safety & Risk Management (14%)
- [ ] Domain 6: Stakeholder Communication & Lifecycle Management (14%)
- [ ] Domain 7: Developer Productivity & Operational Enablement (7%)

A domain is only ticked when its objectives are **Demonstrated** in the tracker, meaning code or documentation, a test or measurement, and a self-explanation that holds up without notes.
