<div align="center">

# Yusyer | AI Engineering

**Python · Reliable AI-agent evaluation · Reproducible machine learning**

[Explore the evaluator](https://github.com/Yusyer174/Nexus-Agent-Evaluation) · [Try it in 5 minutes](https://github.com/Yusyer174/Nexus-Agent-Evaluation/blob/main/docs/TRY_IT.md) · [Give feedback](https://github.com/Yusyer174/Nexus-Agent-Evaluation/issues/8)

</div>

## What I build

I'm a technology student learning to build **testable, understandable AI systems**. I focus on reproducible experiments, useful failure-path tests, and documentation that explains what a tool *cannot* prove.

### 01 · [NEXUS Agent Evaluation](https://github.com/Yusyer174/Nexus-Agent-Evaluation)

[![Python tests](https://github.com/Yusyer174/Nexus-Agent-Evaluation/actions/workflows/tests.yml/badge.svg)](https://github.com/Yusyer174/Nexus-Agent-Evaluation/actions/workflows/tests.yml)
[![GitHub Action smoke test](https://github.com/Yusyer174/Nexus-Agent-Evaluation/actions/workflows/action-smoke.yml/badge.svg)](https://github.com/Yusyer174/Nexus-Agent-Evaluation/actions/workflows/action-smoke.yml)

A **dependency-free Python evaluator** for structured AI-agent decisions: expected decisions, permitted declared actions, evidence identifiers and critical-case gates.

- Run it locally, install the CLI or include the composite GitHub Action in CI.
- Inspect accepted **and deliberately rejected** synthetic cases with no model API key.
- [Quickstart](https://github.com/Yusyer174/Nexus-Agent-Evaluation#see-the-result) · [Code and tests](https://github.com/Yusyer174/Nexus-Agent-Evaluation/tree/main/tests) · [Contributor roadmap](https://github.com/Yusyer174/Nexus-Agent-Evaluation/blob/main/docs/ROADMAP.md)

**Boundary:** This checks *reported declarations*, not real execution, authority or evidence authenticity. It is a public standalone prototype, not the private NEXUS runtime.

### 02 · [California Housing Price Prediction](https://github.com/Yusyer174/house-prices-prediction-portfolio)

[![Baseline validation](https://github.com/Yusyer174/house-prices-prediction-portfolio/actions/workflows/baseline.yml/badge.svg)](https://github.com/Yusyer174/house-prices-prediction-portfolio/actions/workflows/baseline.yml)

An educational **scikit-learn regression baseline**, with preprocessing fitted on training data only, a reproducible 80/20 split and documented limitations.

| Verified historical holdout (4,128 examples) | Result |
| --- | ---: |
| R² | 0.6161 |
| RMSE | $70,925 |
| MAE | $51,215 |

[Run locally](https://github.com/Yusyer174/house-prices-prediction-portfolio#run-locally) · [Model card](https://github.com/Yusyer174/house-prices-prediction-portfolio/blob/main/MODEL_CARD.md)

## Engineering approach

**Define the expected behavior → build a small baseline → test failure paths → publish reproducible evidence → improve from review.**

Tools and current interests: **Python, Git, GitHub Actions, unittest, pandas, NumPy, scikit-learn, agent evaluation, and software reliability.**

## Open to collaboration

I welcome reproducible bug reports, test cases, documentation fixes and honest feedback on the public evaluator. If you're new to contributing, there is a [small first issue](https://github.com/Yusyer174/Nexus-Agent-Evaluation/issues/9). You can also try the [five-minute trial](https://github.com/Yusyer174/Nexus-Agent-Evaluation/blob/main/docs/TRY_IT.md) and explain what helped—or what didn't.

Please do not post credentials, private prompts, proprietary traces or personal information. Neither the public projects nor their tests claim independent safety certification or broad adoption.
