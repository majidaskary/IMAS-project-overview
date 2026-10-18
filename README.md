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
| Git-tracked files | **7,726** |
| Files counted by cloc | **7,573** |
| Physical lines (including comments and blank lines) | **1,278,820** |
| cloc-classified code lines | **1,088,258** |
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

## 8. About This Repository and the Author

This is the **public overview of MAAI Project (Multi-Agent AI)**. It shares the purpose, progress, and direction of the work, not the private core source code or operational infrastructure.

**Majid Askary** — software engineering, systems architecture, applied AI research, and data-driven automation.

[LinkedIn](https://www.linkedin.com/in/majidaskary) · [Contact](mailto:m.askary84@yahoo.com)

## Disclaimer

MAAI is an ongoing research and engineering project, **not** an investment advisory service. Its goals and architectural plans are not claims of guaranteed returns, production deployment, autonomous trading readiness, or authorization for live-capital execution.
