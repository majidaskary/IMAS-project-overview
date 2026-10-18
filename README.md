![MAAI Project cover — multi-agent AI, volatile time-series charts and connected data networks](assets/maai-cover.webp)

<h1 align="center">MAAI Project</h1>

## Multi-Agent AI<br><small>for Time-Series Data Analytics, Decision-Making, Automation &amp; Execution</small>

**I'm building MAAI: a multi-agent AI system that brings data analysis, decision-making, risk controls, automation, and authorized execution into one measurable workflow.**

The first application is **financial-market analysis and automated trading research**. The longer-term goal is a reliable system that can make decisions from evidence, act only within defined permissions, measure real outcomes, and improve through controlled testing.

**Current status:** The main architecture and engineering foundation tracks have reached their defined closeout milestones. The active work is to connect and validate those foundations as an end-to-end system. **A production-ready autonomous trading platform, proven profitability, and live-capital authorization have not been established.**

This repository explains the project publicly; its implementation is maintained in a private repository.

---

## 1. What the System Is Designed to Do

MAAI is intended to connect four capabilities that are often developed separately:

| Capability | What it means in practice |
| --- | --- |
| **Analytics** | Turn time-series data and relevant context into usable insights, such as market trends, volatility, patterns, and changing conditions. |
| **Decision-making** | Compare possible actions, weigh uncertainty, and apply strategy, portfolio, and risk constraints. Choosing **not to act** is also a valid outcome. |
| **Automation** | Coordinate analysis, experiments, validation, and operational workflows with monitoring and human oversight. |
| **Execution** | Carry out explicitly permitted actions, track what actually happened, and account for costs, delays, errors, and other real-world constraints. |

The intended operating cycle is:

~~~text
Data and context
      ↓
Analysis and possible decisions
      ↓
Risk checks and authorization
      ↓
Controlled action (when permitted)
      ↓
Actual results and evaluation
      ↓
Tested improvements → next cycle
~~~

**Why multi-agent AI?** Over time, specialized AI agents could collaborate on tasks such as data quality, analysis, strategy, risk, execution support, and independent evaluation. This is a **design direction**, not a claim that a complete autonomous team of runtime agents is operating today.

## 2. Why Financial Markets First?

Financial markets are the project's first practical testing ground because they combine time-sensitive data, uncertain decisions, financial risk, and measurable outcomes.

The engineering work covers market data, strategies, risk and portfolio logic, execution infrastructure, and evidence-based evaluation. For a trading system to be useful, it must also account for **fees, slippage, liquidity, latency, failures, and market changes**—not just promising backtest results.

The objective is to investigate whether the system can eventually achieve **sustainable, risk-adjusted economic performance**. That outcome is **not yet demonstrated**.

## 3. Where the Project Stands

| Stage | Status | Meaning |
| --- | --- | --- |
| **Phase 1 — Engineering foundations** | **Foundation closeout reached** | The five defined architecture and engineering workstreams have completed their respective foundation milestones; this is not a finished product. |
| **Phase 1.5 — Integration and validation** | **Active** | Connect the components, exercise realistic workflows, and verify end-to-end behavior. |
| **MVP-1 — Operational integration** | **Not yet accepted** | Demonstrate one measured end-to-end flow, including authorized non-production execution and evaluation. |
| **MVP-2 — Economic validation** | **Not yet accepted** | Establish economic results using realistic assumptions and robust evidence, after operational integration. |
| **Phase 2 — Robustness and scaling** | **Not entered** | Future work on resilience, monitoring, and controlled scaling. |
| **Phase 3 — Advanced and adaptive systems** | **Future roadmap** | Further intelligent analysis, research, and controlled adaptation. |
| **Phase 4 — Platform expansion** | **Future roadmap** | Broader platform capabilities and more advanced multi-agent operation. |

The five Phase 1 engineering workstreams are:

| Workstream | Foundation focus |
| --- | --- |
| **EPIC 1** | Market data and intelligence |
| **EPIC 2** | Strategies and decision systems |
| **EPIC 3** | Execution infrastructure |
| **EPIC 4** | Portfolio and risk management |
| **EPIC 5** | Execution orchestration, factual state, evaluation, safety, and permission controls (architecture closeout through 5.24) |

**These are engineering milestones, not percentages of total project completion.** In particular, they do not establish a fully integrated trading system or permission to operate with live capital.

### Project Progress — Visual Snapshot

The bars show **milestone status, not percentage completion**: solid blocks mean a defined architecture foundation has reached closeout, shaded blocks indicate the active integration transition, and empty blocks represent future phases.

**Program phases**

~~~text
MAAI — Build Program

Phase 1   — Core Architecture Foundations ......... CLOSED (foundation)  ████████████████████
Phase 1.5 — Integration & Operationalization ...... ACTIVE TRANSITION    ██████████████▒▒▒▒▒▒
Phase 2   — Stabilization & Capital Scaling ....... NOT YET ENTERED      ░░░░░░░░░░░░░░░░░░░░
Phase 3   — Advanced Engines & Adaptation ......... FUTURE ROADMAP       ░░░░░░░░░░░░░░░░░░░░
Phase 4   — Platformization & Expansion .......... FUTURE ROADMAP        ░░░░░░░░░░░░░░░░░░░░
~~~

**Phase 1 engineering foundations (EPICs)**

~~~text
EPIC 1 — Market Data & Intelligence .............. FOUNDATION CLOSED     ████████████████████
EPIC 2 — Strategy & Decision Layer ............... FOUNDATION CLOSED     ████████████████████
EPIC 3 — Execution Layer ......................... FOUNDATION CLOSED     ████████████████████
EPIC 4 — Risk & Portfolio Layer .................. FOUNDATION CLOSED     ████████████████████
EPIC 5 — Execution Plane, Evaluation & Live Gate . ARCH. CLOSEOUT 5.24   ████████████████████
~~~

**MVP and live-operation readiness**

~~~text
MVP-1 — End-to-End Operational Integration ....... ACCEPTANCE NOT ESTABLISHED
MVP-2 — Economically Validated Operation ......... ACCEPTANCE NOT ESTABLISHED

Production / Live-Capital Authorization .......... NOT ESTABLISHED
~~~

These milestones do **not** mean that the entire platform is complete. Operational integration, economic validation, and permission for live-capital execution each require separate evidence and approval.

## 4. What I'm Working on Now

The immediate priority is **integration before adding more features**:

1. **Connect** market inputs, analytics, decisions, risk and permission checks, execution planning, and evaluation into a coherent workflow.
2. **Exercise and measure** that workflow in authorized, non-production conditions, including realistic failures and trading costs.
3. **Verify the results** against factual records and explicit acceptance criteria before claiming MVP-1 completion.

Only after integration and operational evidence comes the separate question of whether the system has a credible economic advantage (MVP-2). Later phases depend on their own validation and authorization.

## 5. Engineering Snapshot

<small>Measured **17 October 2026** from a fixed internal source snapshot, using **cloc 2.10** on Git-tracked files with documented exclusions. These are historical measurements, not a live repository counter.</small>

| Measure | Verified snapshot |
| --- | ---: |
| Physical lines (including comments and blank lines) | **1,278,820** |
| cloc-classified code lines | **1,088,258** |
| Git-tracked files | **7,726** |
| Files counted by cloc | **7,573** |
| Scoped PKR tests passing on Python 3.12 and 3.13 | **255 distinct tests** |

**How to read these numbers:** The cloc “code” category includes Python, JSON, Markdown, and other recognized content. It does **not** mean 1.09 million lines of executable software. The 255 tests are the same scoped tests passing in **both** Python environments; this does not establish a full-project test-suite pass or end-to-end operational readiness.

### Repository Content Mix

| Content type | Counted files | cloc code lines |
| --- | ---: | ---: |
| Python | 2,599 | 784,669 |
| JSON | 4,285 | 209,161 |
| Markdown | 681 | 93,718 |
| Other | 8 | 710 |
| **Total** | **7,573** | **1,088,258** |

~~~text
Python    72.10%  ██████████████████░░░░░░░
JSON      19.22%  █████░░░░░░░░░░░░░░░░░░░░
Markdown   8.61%  ██░░░░░░░░░░░░░░░░░░░░░░░
Other      0.07%  ▏
~~~

The full engineering records, measurement provenance, and detailed implementation remain private. The numbers describe the **scale of the engineering work**, not product maturity, test coverage, or financial performance.

## 6. How I Approach the Engineering

- **Evidence before claims:** A design, implementation, successful test, integrated workflow, and proven operational result are different milestones.
- **Safety and permissions:** AI-generated suggestions do not automatically authorize execution. Risk checks, approvals, and the ability to stop operations are essential.
- **Realistic evaluation:** Decisions must be assessed under costs, uncertainty, market constraints, and failure conditions.
- **Traceability and controlled improvement:** Results should be explainable and reproducible; changes must be tested before they are adopted.

## 7. Scope and Future Direction

Financial markets are the primary implementation and validation domain. The underlying ideas—time-series analysis, cooperating specialist agents, decision-making, and governed automation—may eventually be useful in other settings. **No other domain-specific product is claimed to exist today.**

The roadmap is deliberately staged: operational integration first, realistic economic evaluation next, and more advanced intelligence or platform capabilities only when the evidence and conditions justify them.

## 8. Multi-Agent Architecture and Responsibilities

MAAI is designed around **cooperating specialist functions**, not one model making every decision. In the proposed runtime architecture, agents may examine evidence, challenge conclusions, and recommend actions, while the system keeps factual records, risk controls, and execution permissions explicit.

| Specialist function | Intended responsibility |
| --- | --- |
| **Data and market intelligence** | Check input quality and timing; analyze technical patterns, changing market regimes, and contextual evidence. |
| **Strategy and portfolio reasoning** | Compare candidate strategies, estimate uncertainty, and consider exposure, concentration, and correlation. |
| **Risk and policy assessment** | Check constraints, identify unsafe decisions, and distinguish a recommendation from permission to act. |
| **Execution support** | Plan permitted actions, assess costs and operational constraints, and report execution outcomes. |
| **Critique, evaluation, and research** | Challenge assumptions, investigate failures, compare results with baselines, and propose testable improvements. |

An important design rule is that **an agent's suggestion is not a verified fact or an execution authorization**. State, evidence, approvals, and operator controls need their own accountable boundaries.

**Maturity distinction:** The development process already uses structured human–AI collaboration with separated responsibilities. That engineering workflow is different from a fully integrated team of autonomous **runtime** agents; the latter remains an architectural objective.

## 9. Data, Analytics, and Contextual Intelligence

The analytical foundation is intended to connect **time-series observations** with the context needed to interpret them. Good decisions depend on data that can be checked for source, time, completeness, and consistency—not just on sophisticated models.

Research and engineering directions include:

- **Market data foundations:** historical, representative, and eventually appropriate live inputs; validation, normalization, timestamps, and provenance.
- **Technical and quantitative analysis:** price action, volume, trends, volatility, momentum, patterns, statistics, and multi-timeframe or cross-asset comparisons.
- **Condition-aware research:** market regimes, anomalies, uncertainty, and testing when an indicator or strategy works and when it breaks down.
- **Fundamental and macro context:** possible integration of financial, economic, news, and other external evidence where data quality and research justify it.
- **Reliable knowledge:** traceable features, experiment history, and records that help compare new results with earlier findings.

These describe the engineering foundation and research scope, **not a claim that all data sources, indicators, or intelligent analytical components are already integrated or operational**.

## 10. Strategy, Portfolio, and Decision Intelligence

The goal is to move beyond isolated trading signals toward **inspectable decisions**. A proposed action needs more than a model prediction: it needs assumptions, supporting evidence, confidence or uncertainty, and an explanation of the relevant constraints.

The intended decision layer supports strategy comparison and selection, combinations of approaches, and responses to changing market regimes. Portfolio reasoning brings in position sizing, capital allocation, risk budgets, diversification, concentration, and correlation.

A proposed decision can lead to different outcomes:

1. **Proceed to review:** the idea has enough evidence to be evaluated against risk and policy constraints.
2. **Revise or investigate:** uncertainty, conflicting information, or portfolio effects require more work.
3. **Do nothing:** choosing **no trade** is a deliberate outcome when conditions do not justify action.

**Decision, risk clearance, approval, and execution are separate steps.** A strong backtest or an AI recommendation alone does not establish permission to place a real order.

## 11. Execution Engineering, Safety, and Operational Truth

Execution means more than sending an order. The target execution plane connects approved intent to observable results through planning, orchestration, permissions, runtime behavior, and reconciliation.

A controlled execution flow must distinguish:

- **Requested action** from policy checks, approval, and actual authorization.
- **Execution intent and order state** from fills, partial fills, rejection, cancellation, and failure handling.
- **Expected performance** from realized costs such as spreads, fees, slippage, liquidity, and latency.
- **Internal assumptions** from factual events, records, and measured outcomes.

The architecture includes risk and authority boundaries, revocation, observability, recovery, and auditability. Its purpose is to make consequential actions **bounded, traceable, and interruptible**, with human oversight where required.

The project's fifth engineering workstream covers execution planning, orchestration, canonical state and evidence, evaluation, and controlled-live gate models, with architecture closeout through Sub-Epic 5.24. **That foundation does not prove end-to-end operational acceptance, production readiness, or authorization for live-capital trading.**

## 12. Evaluation, Reliability, and Controlled Learning

MAAI treats **what actually happened** as distinct from what a simulation, model, or agent expected. The evaluation program therefore emphasizes reproducible experiments, independent records, and realistic constraints.

| Evidence area | What needs to be established |
| --- | --- |
| **Testing and replay** | Repeatable behavior, correct state transitions, and handling of realistic scenarios and failures. |
| **Simulation and backtesting** | Assumptions, transaction costs, market limitations, and comparisons with appropriate baselines. |
| **Non-production operation** | Connected data-to-action-to-evaluation workflows with factual outcomes, without implying permission to trade live capital. |
| **Economic evaluation** | Robustness, out-of-sample evidence, risk-adjusted results, and an honest account of uncertainty. |
| **Change control** | Explainable, versioned, reviewable, reversible improvements; detection of drift or degraded performance. |

Reliability also involves recovery, reconciliation, idempotent processing, least-privilege access, and operator control. A system should be able to explain **which data, decision, configuration, constraint, and execution event** contributed to an outcome.

The acceptance gates remain distinct: **MVP-1** requires verified end-to-end operational integration; **MVP-2** requires separate economic validation. Neither has been accepted in the public snapshot, and neither can be inferred merely from architecture closeout or scoped CI tests.

## 13. About This Repository and the Author

This is the **public overview of MAAI Project (Multi-Agent AI)**. It shares the purpose, progress, and direction of the work, not the private core source code or operational infrastructure.

**Majid Askary** — software engineering, systems architecture, applied AI research, and data-driven automation.

[LinkedIn](https://www.linkedin.com/in/majidaskary) · [Contact](mailto:m.askary84@yahoo.com)

## Disclaimer

MAAI is an ongoing research and engineering project, **not** an investment advisory service. Its goals and architectural plans are not claims of guaranteed returns, production deployment, autonomous trading readiness, or authorization for live-capital execution.
