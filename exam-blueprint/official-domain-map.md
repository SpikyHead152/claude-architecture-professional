# Official Domain Map: CCAR-P Exam Guide v1.0 (July 2026)

Own-words summary of the objectives in the official guide. The guide is the source of truth; this file is a working index and may lag it. Re-check the guide before exam day, since it can change without notice.

**Exam:** 63 items, 120 min, multiple-choice and multiple-response (each item states how many answers to pick), scaled pass mark 720 of 1,000. Domain percentages are approximate shares of scored items.

**Objective type** shows what the verb in the guide asks for, because that decides what counts as evidence:
- **Build**: produce and run something.
- **Analyze**: examine a design or result and find what is wrong or best.
- **Decide**: choose among options and justify the trade-off.
- **Communicate**: produce documentation or stakeholder material.

| Domain | Weight | ≈ items |
|---|---:|---:|
| 1 Solution Design & Architecture | 17% | 11 |
| 2 Claude Models, Prompting & Context Engineering | 13% | 8 |
| 3 Integration | 19% | 12 |
| 4 Evaluation, Testing & Optimization | 16% | 10 |
| 5 Governance, Safety & Risk Management | 14% | 9 |
| 6 Stakeholder Communication & Lifecycle Management | 14% | 9 |
| 7 Developer Productivity & Operational Enablement | 7% | 4 |

## Domain 1: Solution Design & Architecture (17%)
| ID | Objective (paraphrased) | Type |
|---|---|---|
| 1.1 | Turn a business problem into a Claude-based solution | Decide |
| 1.2 | Design the whole flow: input, processing, output, feedback loop | Build |
| 1.3 | Choose between workflow, agentic and augmented-LLM patterns | Decide |
| 1.4 | Design multi-agent systems and their orchestration | Build |
| 1.5 | Decompose complex problems into tractable parts | Decide |
| 1.6 | Tie the solution to business value (efficiency, transformation, productivity, cost, performance SLAs) | Communicate |

## Domain 2: Claude Models, Prompting & Context Engineering (13%)
| ID | Objective (paraphrased) | Type |
|---|---|---|
| 2.1 | Pick the right Claude model for the trade-offs involved | Decide |
| 2.2 | Design system prompts, templates and guardrails | Build |
| 2.3 | Apply zero-shot, few-shot and chain-of-thought techniques | Build |
| 2.4 | Manage the context window and token spend | Build |
| 2.5 | Reuse prompts via caching, modular prompts and Skills | Build |

## Domain 3: Integration (19%)
| ID | Objective (paraphrased) | Type |
|---|---|---|
| 3.1 | Audit a tool or agent configuration for capability bloat | Analyze |
| 3.2 | Analyze authentication and authorization needs and find security gaps | Analyze |
| 3.3 | Weigh accuracy against latency and justify the configuration | Decide |
| 3.4 | Analyze observability challenges at scale and choose monitoring | Analyze |
| 3.5 | Design a RAG pipeline with suitable chunking and indexing | Build |
| 3.6 | Match retrieval strategy to data shape and query pattern | Decide |
| 3.7 | Choose the integration mechanism: MCP, API/CLI, or agent-to-agent | Decide |
| 3.8 | Compare progressive discovery with loading everything into context | Decide |

## Domain 4: Evaluation, Testing & Optimization (16%)
| ID | Objective (paraphrased) | Type |
|---|---|---|
| 4.1 | Define metrics: accuracy, latency, cost, safety, security | Decide |
| 4.2 | Build evaluation datasets and test frameworks with mixed methods | Build |
| 4.3 | Run A/B tests and iterate on the results | Build |
| 4.4 | Diagnose failures: prompt problems, hallucination, model mismatch | Analyze |
| 4.5 | Optimize tokens, latency and the cost-performance trade-off | Decide |
| 4.6 | Monitor the running system with logging and observability tools | Build |

## Domain 5: Governance, Safety & Risk Management (14%)
| ID | Objective (paraphrased) | Type |
|---|---|---|
| 5.1 | Implement guardrails and safety controls | Build |
| 5.2 | Identify risks, limitations and failure modes of LLM systems | Analyze |
| 5.3 | Apply human-in-the-loop validation | Build |
| 5.4 | Meet regulatory expectations (e.g. GDPR, HIPAA, FedRAMP) | Analyze |
| 5.5 | Address ethical concerns: bias, fairness, transparency | Analyze |

## Domain 6: Stakeholder Communication & Lifecycle Management (14%)
| ID | Objective (paraphrased) | Type |
|---|---|---|
| 6.1 | Run structured discovery and gather requirements | Communicate |
| 6.2 | Explain architectural decisions and their trade-offs | Communicate |
| 6.3 | Manage stakeholder feedback and expectations, including SLAs | Communicate |
| 6.4 | Document architectures and give implementation guidance | Communicate |
| 6.5 | Support every lifecycle phase: discovery, design, handoff, monitoring, iteration | Communicate |

## Domain 7: Developer Productivity & Operational Enablement (7%)
| ID | Objective (paraphrased) | Type |
|---|---|---|
| 7.1 | Configure Claude tools and environments for teams (e.g. Claude Code) | Build |
| 7.2 | Improve developer workflows with AI-assisted tooling | Build |
| 7.3 | Support debugging and operational issue resolution | Analyze |

## What the type split tells us

Of 38 objectives, 14 are Build, 10 are Decide, 8 are Analyze and 6 are Communicate. So 24 of 38 (about 63%) are judgment, diagnosis or communication, not construction. Every Decide, Analyze and Communicate objective needs a written comparison, audit or document in the repo, because a working demo does not show that you can choose, diagnose or explain. The classification is my reading of the verbs and is a planning aid, not part of the official guide.
