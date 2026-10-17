# IMAS

## Intelligent Multi-Agent System

### for Time-Series Data Analytics, Decision-Making, Automation & Execution

**A long-term research and engineering effort to develop an intelligent, evidence-driven, governable multi-agent system that can analyze information, make decisions, automate workflows, execute authorized actions, evaluate outcomes, and improve through controlled learning.**

> **Public overview.** This repository presents the mission, system vision, engineering philosophy, current foundations, and long-term roadmap of IMAS. The main implementation and detailed engineering artifacts are maintained privately. The architecture and roadmap described here include both existing foundations and future objectives; they should not be read as a claim that every capability is already operational.

## Project at a Glance — Verified Engineering Snapshot

**Measured 17 October 2026** · Fixed source commit: `efb8723c92ad355f7f288023f1da99214fb29c6d` · **cloc 2.10** · Git-tracked files with documented exclusions.

| **1,278,820** physical lines | **1,088,258** cloc-classified code lines | **7,573** counted files | **255** verified PKR tests |
| :---: | :---: | :---: | :---: |
| Includes code, comments and blanks | Includes Python, JSON, Markdown and configuration | From **7,726** Git-tracked files | Passed on **both Python 3.12 and 3.13** |

> **Reading the numbers correctly:** The 1,088,258 figure is the `cloc code` category **across all recognized file types**, including prose in Markdown and data in JSON. It is **not** 1.09 million lines of executable application code. The 255 tests are the **same scoped `tests/pkr` tests** passing in two Python environments—not 510 distinct tests or evidence of a full-project test-suite pass.

### Language and Content Distribution

Share of the **1,088,258 cloc-classified code lines**:

| Language / content | Counted files | cloc code lines | Share |
| --- | ---: | ---: | ---: |
| **Python** | 2,599 | **784,669** | **72.10%** |
| **JSON** | 4,285 | **209,161** | **19.22%** |
| **Markdown** | 681 | **93,718** | **8.61%** |
| Other (YAML, PowerShell, TOML, Text) | 8 | 710 | 0.07% |
| **Total** | **7,573** | **1,088,258** | **100%** |

~~~text
Python    72.10%  ██████████████████░░░░░░░
JSON      19.22%  █████░░░░░░░░░░░░░░░░░░░░
Markdown   8.61%  ██░░░░░░░░░░░░░░░░░░░░░░░
Other      0.07%  ▏
~~~

### Program Build Snapshot

A phase-level view of the **documented engineering program**. Solid blocks mark a closed **architecture foundation**; shaded blocks indicate an **active transition**; empty blocks indicate **future phases**. Bars are **status markers, not completion percentages**.

~~~text
IMAS — Build Program

Phase 1   — Core Architecture Foundations ......... CLOSED (foundation)    ████████████████████
Phase 1.5 — Integration & Operationalization ...... ACTIVE TRANSITION      ▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒
Phase 2   — Stabilization & Capital Scaling ....... NOT YET ENTERED        ░░░░░░░░░░░░░░░░░░░░
Phase 3   — Advanced Engines & Adaptation ......... FUTURE ROADMAP         ░░░░░░░░░░░░░░░░░░░░
Phase 4   — Platformization & Expansion .......... FUTURE ROADMAP          ░░░░░░░░░░░░░░░░░░░░
~~~

**Phase 1 architecture/foundation closeout is not product completion.** Phase 1.5 is the current operational integration and validation transition; entry into subsequent phases requires separate criteria and authorization.

### Phase 1 — EPIC-by-EPIC Foundation Snapshot

~~~text
EPIC 1 — Market Data & Intelligence .............. FOUNDATION CLOSED     ████████████████████
EPIC 2 — Strategy & Decision Layer ............... FOUNDATION CLOSED     ████████████████████
EPIC 3 — Execution Layer ......................... FOUNDATION CLOSED     ████████████████████
EPIC 4 — Risk & Portfolio Layer .................. FOUNDATION CLOSED     ████████████████████
EPIC 5 — Execution Plane, Evaluation & Live Gate . ARCH. CLOSEOUT 5.24   ████████████████████
~~~

All **five Phase 1 engineering/architecture foundation tracks** have documented closeout or implementation through their defined closeout boundary. This says nothing about the percentage completion of the **entire** IMAS vision.

### MVP Acceptance and Operational Readiness

~~~text
MVP-1 — End-to-End Operational Integration ....... ACCEPTANCE NOT ESTABLISHED
MVP-2 — Economically Validated Operation ......... ACCEPTANCE NOT ESTABLISHED

Production / Live-Capital Authorization .......... NOT ESTABLISHED
~~~

- **MVP-1** requires a connected and measured end-to-end operational flow, including authorized non-production execution, factual results and evaluation.
- **MVP-2** requires separate, realistic economic evidence after operational integration; profitable or sustainable performance must not be presumed.
- **Controlled-live / production permissions** require explicit scoped authorization and cannot be inferred from EPIC closeout, CI success or an architecture diagram.

**Status basis:** canonical project-state and Phase 1 → Phase 2 transition planning at the same fixed-commit snapshot used for the engineering measurements above. These indicators are **qualitative milestone states**, not newly calculated progress percentages.

### Quality Evidence and Measurement Scope

The fixed-commit CI record confirms **255 PKR tests passed** on **Python 3.12** and **Python 3.13**, separately. No complete test-suite PASS, all-system integration acceptance, economic edge, production readiness, or live-capital authorization is established by this snapshot.

<details>
<summary>Detailed line counts, historical size reference, and reproducibility method</summary>

**Line categories (cloc 2.10):**

| Category | Lines |
| --- | ---: |
| Nonblank, noncomment (`code`) | 1,088,258 |
| Comments | 17,485 |
| Blank | 173,077 |
| **Total physical lines** | **1,278,820** |

**Major tracked path groups** (the groups below are not exhaustive):

| File area | Counted files | cloc code lines |
| --- | ---: | ---: |
| Application source (`src/**`) | 1,021 | 477,003 |
| Test assets (`tests/**`) | 1,591 | 307,124 |
| Engineering documentation (`docs/**`) | 242 | 63,962 |

Of the source path's classified content, Python represents **476,910** code lines in **1,015** files. Of the test path's classified content, Python represents **304,638** code lines in **1,569** files. These counts are not coverage or numbers of passed tests.

**Historical reference:** An earlier overview reported **968 counted files** and **178,690 cloc code lines**. The fixed snapshot reports **7,573** and **1,088,258** respectively—an arithmetic ratio of **7.82×** files and **6.09×** cloc code lines. The historical snapshot's exact commit, raw cloc report, and tool version were not independently reconstructed, so these are **descriptive size comparisons**, not a controlled growth metric or a measure of maturity.

**Reproducibility:** Measured on Git-tracked files at commit `efb8723c92ad355f7f288023f1da99214fb29c6d` with:

~~~bash
cloc . --vcs=git --exclude-dir=.git,.venv,venv,dist,build,tmp,obsidian,node_modules,.pytest_cache,__pycache__,htmlcov,.mypy_cache --json --out=cloc_tracked.json
~~~

The matching non-VCS `cloc .` run gave identical per-language counts at the same clean checkout. **153 tracked files** were not counted, including the explicitly excluded knowledge-vault directory, zero-byte files, unrecognized/non-code files, and a binary fixture. Counts are a **fixed historical measurement** and should be remeasured on any newer baseline before being described as current.

</details>

---

## 1. What Is IMAS?

**IMAS — Intelligent Multi-Agent System** is the identity of a research and engineering project whose central goal is to **build the system itself**, not merely use multi-agent technology as an accessory to an analytics application.

Its core focus is the complete lifecycle of intelligent, time-sensitive operations:

**Observe and understand data → analyze and reason → decide → apply risk and authority controls → automate and execute → measure outcomes → learn and improve.**

The project's first and most developed application is **a private financial-market engineering implementation**. Its long-term product objective is a dependable, increasingly intelligent automated trading platform that can operate under realistic market constraints, make evidence-backed decisions, execute safely when authorized, and pursue **positive, sustainable, risk-adjusted economic performance**.

That economic performance is an objective to establish through realistic evidence, **not an achieved or guaranteed result**.

Although financial markets are the primary proving ground, the IMAS identity reflects broader research into multi-agent intelligence, time-series data, decision systems, governed automation, and reusable platform architecture. Other applications are possibilities for future investigation, not claims of present implementations or already-approved roadmap commitments.

## 2. Mission and North Star

IMAS aims to bring together capabilities often developed in isolation and make them work as **one coherent, measurable, accountable operational system**.

The intended outcome is a system that can:

1. **Observe:** ingest reliable time-indexed and contextual information, preserving data integrity, timing, identity, and provenance.
2. **Understand:** interpret patterns, trends, anomalies, regimes, uncertainty, and interactions across data sources.
3. **Reason:** combine analytical methods, structured logic, research evidence, and eventually specialized intelligent agents.
4. **Decide:** select or reject strategies and actions with explicit confidence, constraints, and portfolio-level context.
5. **Protect:** evaluate risk, enforce safety boundaries, and distinguish recommendations from actual authorization.
6. **Act:** coordinate workflows and perform approved operations through controlled execution mechanisms.
7. **Evaluate:** determine what actually happened, why it happened, and how credible the result is.
8. **Improve:** diagnose weaknesses, test alternatives, and adapt only through traceable, reproducible, reviewable processes.

The north star is **real operational competence supported by evidence**, rather than the number of models, agents, indicators, or features in the repository.

## 3. The Four Functional Pillars

The subtitle of IMAS describes four connected capabilities. They are not four independent products.

### Analytics — Time-Series Data and Contextual Intelligence

Transform raw observations into trustworthy analytical context. The research direction includes:

- historical and live or representative data ingestion, validation, normalization, and provenance;
- chart and price-action analysis, trends, momentum, volatility, volume, patterns, and market structure;
- multi-timeframe, cross-asset, statistical, quantitative, and regime-aware techniques;
- anomaly detection, feature engineering, and model/indicator comparison;
- the future integration of fundamental, macroeconomic, news, and other contextual information where evidence and data availability justify it.

The objective is not merely to add more indicators, but to understand **when a method is useful, when it fails, and what evidence supports its use**.

### Decision-Making — Evidence, Strategy, and Judgment

Turn analysis into decisions that can be inspected and evaluated:

- strategy generation, selection, combination, and meta-strategy research;
- market-regime-aware reasoning and context-dependent decisions;
- uncertainty and confidence assessment, conflicting-evidence handling, and **no-action / no-trade** outcomes;
- portfolio construction, capital allocation, exposure, concentration, and correlation awareness;
- explicit separation of analytical recommendations, risk decisions, and authorization.

A decision is not correct merely because an agent produced it; its assumptions, constraints, and results must be testable.

### Automation — Coordination and Controlled Workflows

Develop an architecture in which specialized components and, over time, intelligent agents can cooperate without losing accountability:

- orchestrated data, research, analysis, experimentation, and evaluation workflows;
- bounded agent roles with explicit interfaces and ownership;
- reproducible scenario, batch, backtest, replay, and simulation processes;
- automation that is observable, cancellable, recoverable, and subject to governance;
- operator interfaces and human oversight for consequential processes.

**Automation does not imply unlimited autonomy.** Agents and workflows must not silently acquire execution or approval authority.

### Execution — Authorized Real-World Action

Connect decisions to operational outcomes through a controlled execution plane:

- execution requests, planning, context resolution, orchestration, and runtime engines;
- execution intent, orders, fill and state semantics, reconciliation, and failure handling;
- fees, spreads, liquidity, slippage, timing, latency, and partial-fill realities;
- risk, permission, safety, approval, audit, and revocation boundaries;
- factual state, event records, traceability, and independent outcome evaluation.

The objective is to execute **correctly and safely in an explicitly permitted environment**, not to infer live-market permission from the presence of execution code.

## 4. Cross-Cutting Intelligence and Engineering Capabilities

The four pillars describe what the system does. The following capabilities determine **whether its behavior is trustworthy, useful, and sustainable**.

| Capability domain | Long-term objective |
| --- | --- |
| **Technical and quantitative intelligence** | Broader pattern research, market structure, statistical methods, ensembles, and condition-aware analysis |
| **Fundamental and contextual intelligence** | Integrate economic, financial, textual, and relevant external evidence with market observations |
| **Multi-agent reasoning** | Cooperating specialist agents for analysis, research, critique, risk, portfolio, and execution support |
| **Strategy and portfolio intelligence** | Multi-strategy selection, diversification, capital allocation, and risk-adjusted optimization |
| **Risk and safety intelligence** | Pre-action risk, drawdown, liquidity, model and operational risks, emergency controls, and bounded authority |
| **Execution intelligence** | Understand and improve fill quality, timing, costs, market constraints, and operational resilience |
| **Evaluation science** | Realistic backtests, replay, paper and live-shadow evidence, reproducibility, baselines, and out-of-sample testing |
| **Measurement and attribution** | Explain contributions of signals, strategy choices, sizing, risk controls, and execution to actual outcomes |
| **Self-diagnosis and controlled learning** | Detect drift and degradation; propose and validate changes without uncontrolled self-modification |
| **Data, knowledge, and memory** | Provenance, canonical records, experiment/decision history, and durable structured project knowledge |
| **Reliability, explainability, and security** | Recovery, idempotency, observability, evidence-backed explanations, least privilege, and auditability |
| **Platform and product evolution** | Operator dashboards, APIs, extensible services, scalability, and potentially multi-user / multi-account deployment |

These are **long-term capability objectives with varying maturity**, not a checklist of deployed features.

## 5. Multi-Agent System Vision

Multi-agent intelligence is intended to be part of the **system architecture**, not merely a label for the user interface or a collection of chat prompts.

Future specialist roles may include:

| Specialist role | Intended responsibility |
| --- | --- |
| Data and quality analyst | Data integrity, timing, completeness, and provenance |
| Technical analyst | Chart structures, indicators, patterns, and cross-timeframe signals |
| Fundamental and macro analyst | Financial context, events, external information, and macro conditions |
| Market-regime analyst | Regime identification, uncertainty, and changing market conditions |
| Strategy and decision agent | Candidate actions, strategy comparison, and decision rationale |
| Portfolio and risk agents | Allocation, exposure, constraints, and risk assessment |
| Execution specialist | Execution proposals, cost/quality analysis, and operational feedback |
| Critic and evaluator | Challenge assumptions, compare evidence, investigate failures |
| Research and knowledge specialist | Experiments, retrieval of prior findings, and controlled improvement proposals |

**Architecture direction is not a deployment claim.** The current project also uses a structured, role-separated human–AI engineering collaboration model. That development workflow is distinct from a fully integrated, autonomously cooperating **runtime** team of specialist agents, which remains a longer-term architecture objective.

Regardless of agent capabilities, the system must retain explicit ownership of factual state, risk assessment, permissions, and execution authority.

## 6. Target End-to-End Operating Loop

The intended operating model is a closed loop of observation, decision, action, and learning:

~~~text
Real / Representative Data + Contextual Inputs
                      |
                      v
        Data Integrity, Timing & Provenance
                      |
                      v
        Features, Patterns & Market Context
                      |
                      v
       Analytics + Specialist Intelligence
                      |
                      v
       Strategy / Decision + Uncertainty
                      |
                      v
             Portfolio & Risk
                      |
                      v
      Policy, Permission & Safety Gates
                      |
                      v
       Execution Planning & Orchestration
                      |
                      v
        Authorized Operational Action
                      |
                      v
         Actual Outcomes & State Truth
                      |
                      v
      Evidence, Evaluation & Attribution
                      |
                      v
    Research, Diagnosis & Controlled Change
                      |
                      +------> Revalidation / Next Cycle
~~~

This is a **target product workflow**, not a claim that an end-to-end production-live autonomous system has been demonstrated. Real implementation and authorization remain subject to canonical contracts, tests, evidence, and project governance.

## 7. First Concrete Application: Financial-Market Engineering Core

The private **financial-market engineering core** is the primary implementation and validation domain for IMAS. Financial markets provide a demanding environment in which analytical quality, execution behavior, safety, timing, evidence, and economic outcomes can be assessed together.

The documented engineering foundation includes:

- **EPIC 1:** market data and market-intelligence foundations;
- **EPIC 2:** strategy and decision-layer foundations;
- **EPIC 3:** execution-layer foundations;
- **EPIC 4:** risk and portfolio foundations;
- **EPIC 5:** an execution plane with planning, orchestration, canonical state/evidence, evaluation, observability, safety, authority, approval, and controlled-live gate models.

According to the canonical project-state and roadmap records, EPICs 1–4 have completed their foundation tracks and EPIC 5 has progressed through Sub-Epic 5.24. These are **engineering and program milestones**, not proof of a fully integrated operational trading MVP, sustainable profitability, or live-capital authorization.

The immediate engineering priority is therefore **integration before expansion**: connect and validate existing foundations as one observable, reproducible, end-to-end system.

## 8. Delivery and Research Roadmap

The program is intentionally staged. Later capabilities must not be confused with current readiness or introduced at the expense of the working core.

| Stage | Intended result | Status interpretation |
| --- | --- | --- |
| **Foundation and execution-plane engineering** | Canonical data, strategies, execution, risk, evidence, governance, and control contracts | Significant documented and implemented foundations; does not prove live operation |
| **MVP-1 — Operational integration** | One end-to-end flow from market input to decision, authorized non-production execution, factual results, and evaluation | Core product-level integration objective requiring evidence |
| **MVP-2 — Economic validation** | Test whether a realistic, sufficiently robust, positive risk-adjusted edge actually exists | Research and validation objective; not an established performance claim |
| **Phase 2 — Robustness and capital scaling** | Stress resilience, recovery, monitoring, risk validation, and controlled allocation/portfolio optimization | Conditional future phase |
| **Phase 3 — Advanced engines and adaptive optimization** | Cross-venue research, machine learning, regime-aware optimization, and controlled adaptation | Conditional future phase |
| **Phase 4 — Platform and advanced agent intelligence** | Multi-user / multi-account platform capabilities, richer reasoning, agentic intelligence, and operator-facing tooling | Conditional future phase |

Across these stages, the research program also develops technical and fundamental intelligence, knowledge preservation, adversarial evaluation, benchmarking, explainability, and trustworthy automation.

**Future phases have activation conditions.** A roadmap entry is not evidence that a capability is operational or that work on it has been authorized.

## 9. Evidence, Safety, and Operational Truth

IMAS follows a strict engineering distinction:

~~~text
Designed != Implemented
Implemented != Integrated
Integrated != Exercised
Exercised != Realistic
Realistic != Measured
Measured != Economically Validated
Profitable != Safe
Safe != Authorized
~~~

In practice:

- **Evidence over assertions.** Tests, measured behavior, reproducible artifacts, and realistic assumptions matter more than completion percentages.
- **Reality-first evaluation.** Fees, latency, slippage, liquidity, market regimes, failures, and uncertainty must be represented before interpreting financial results.
- **Explicit authority.** Analysis, recommendation, permission, risk clearance, approval, and live authorization are different responsibilities.
- **No mandatory action.** When evidence is inadequate, declining to act may be the correct outcome.
- **Controlled adaptation.** Any learning-driven change must be observable, versioned, testable, reviewable, and reversible.
- **Traceable decisions.** Meaningful outcomes should be attributable to data, code, configuration, strategy/model version, relevant constraints, and execution evidence.
- **Reliability as correctness.** Recovery, reconciliation, failure semantics, security, and operator control are part of the system—not optional finishing work.

**No live-capital or unrestricted autonomous trading authorization is implied by this public overview.**

## 10. Beyond the First Application

IMAS is named around **time-series data and a multi-agent operating model**, not around one exchange, trading strategy, or product interface.

The currently defined primary product remains the financial-market implementation. In the longer term, parts of the architecture might also inform other time-dependent decision environments—for example, operational monitoring or business/industrial analytics—**if separately researched, justified, governed, and added to an approved roadmap**.

This is a possible expansion direction, not an assertion that those domain-specific products exist today.

## 11. Public Overview, Implementation, and Metrics

This repository is the **public-facing description of IMAS**. It does not contain the private core implementation, confidential engineering artifacts, credentials, or operational infrastructure.

- **IMAS** is the official abbreviated identity of **Intelligent Multi-Agent System**.
- **IMAS Project** may be used as a natural reference to the research and engineering effort; the word *Project* is not part of the formal name.
- **The existing private financial-market core** remains the first concrete implementation. Its internal repository identity and naming may evolve independently of this public overview.
- Current work, tests, architecture, and maturity are governed by the private repository's canonical sources and evidence, not by public marketing claims.

### Metrics and progress reporting

The **Project at a Glance** section near the top of this README contains a reproducible, fixed-commit engineering scale measurement (17 October 2026, cloc 2.10), plus scoped CI evidence and documented milestone statuses. Its counts are **not** software maturity, test coverage, project completion percentages, economic validation, or operational/live readiness. The old overview's line counts and progress percentages are retained in Git history as historical reference only. Future updates must explicitly name the source commit and evidence scope.

## 12. About the Author

**Majid Askary** — systems architecture, software engineering, data-driven systems, governed automation, and applied multi-agent research.

- [LinkedIn](https://www.linkedin.com/in/majidaskary)
- [Contact](mailto:m.askary84@yahoo.com)

## Disclaimer

IMAS is an ongoing research and engineering project. It is not an investment advisory service or a source of guaranteed trading signals or returns. Research objectives, architecture concepts, and planned capabilities are not claims of deployment, financial success, production readiness, or authorization to execute live-capital operations.

---

**IMAS in one sentence:** Building an intelligent multi-agent system that turns trustworthy time-series and contextual data into evidence-based decisions, governed automation, authorized execution, and measurable continuous improvement—beginning with a rigorously engineered financial-market application.
