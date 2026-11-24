# Yus-Builds (@Yusyer174)

Technology student building practical, testable software while learning Python, machine learning and AI-agent evaluation.

[**Try NEXUS in five minutes**](https://github.com/Yusyer174/Nexus-Agent-Evaluation/blob/main/docs/TRY_IT.md) · [View projects](#selected-projects) · [Open-source contributions](#open-source-collaboration)

## Selected projects

### [NEXUS Agent Evaluation](https://github.com/Yusyer174/Nexus-Agent-Evaluation)

[![Python tests](https://github.com/Yusyer174/Nexus-Agent-Evaluation/actions/workflows/tests.yml/badge.svg?branch=main)](https://github.com/Yusyer174/Nexus-Agent-Evaluation/actions/workflows/tests.yml)
[![Action smoke test](https://github.com/Yusyer174/Nexus-Agent-Evaluation/actions/workflows/action-smoke.yml/badge.svg?branch=main)](https://github.com/Yusyer174/Nexus-Agent-Evaluation/actions/workflows/action-smoke.yml)

An open-source, dependency-free Python tool that checks structured AI-agent outputs against explicit test cases. It evaluates declared decisions, allowed actions, required evidence identifiers and critical-case acceptance rules.

- Python 3.10+ · CLI · GitHub Action · synthetic examples with no API key.
- Reproducible passing and failing cases, automated tests, and installation checks.
- [Quickstart](https://github.com/Yusyer174/Nexus-Agent-Evaluation#see-the-result) · [Consumer demonstration](https://github.com/Yusyer174/Nexus-Agent-Evaluation/blob/main/docs/CONSUMER_TRIAL.md) · [Input/output contract](https://github.com/Yusyer174/Nexus-Agent-Evaluation/blob/main/docs/INTEGRATION.md).

**Scope:** This is an early standalone evaluator of reported outputs, not a runtime security sandbox. It does not verify actual execution, evidence authenticity or real-world agent safety.

### [California Housing Price Prediction](https://github.com/Yusyer174/house-prices-prediction-portfolio)

[![Baseline validation](https://github.com/Yusyer174/house-prices-prediction-portfolio/actions/workflows/baseline.yml/badge.svg?branch=main)](https://github.com/Yusyer174/house-prices-prediction-portfolio/actions/workflows/baseline.yml)

Educational scikit-learn regression project with a reproducible train/test split and preprocessing fitted on training data only.

| Historical holdout (4,128 examples) | Result |
| --- | ---: |
| R² | 0.6161 |
| RMSE | $70,925 |
| MAE | $51,215 |

[Reproduce the baseline](https://github.com/Yusyer174/house-prices-prediction-portfolio#run-locally) · [Model card and limitations](https://github.com/Yusyer174/house-prices-prediction-portfolio/blob/main/MODEL_CARD.md) · [Validation run](https://github.com/Yusyer174/house-prices-prediction-portfolio/actions/runs/43220651075).

The historical holdout is a single evaluation split, not evidence of generalization to new regions or current house prices.

## Open-source collaboration

- [AI-Research-Agent — PR #2](https://github.com/hemanthkumar1012/AI-Research-Agent/pull/2): submitted a focused citation-source isolation regression test following the maintainer's guidance. See the PR for its current review and CI status.
- [NEXUS — issue #9 and PR #16](https://github.com/Yusyer174/Nexus-Agent-Evaluation/pull/16): an external contributor submitted a duplicate-JSON-key regression test; I reviewed the contribution. See the PR for its current checks and merge status.
- [Independent feedback — issue #8](https://github.com/Yusyer174/Nexus-Agent-Evaluation/issues/8): open invitation to try the public evaluator and report what works, what fails and what is unclear.

These contributions are evidence of collaboration, not proof of external product adoption.

## What I am learning

Python · Git · GitHub Actions · unittest · pandas · NumPy · scikit-learn · agent evaluation · reproducible experiments.

My approach: define expected behavior, test failure paths, publish reproducible evidence, and improve based on review. I use AI-assisted development tools while working to understand, test and explain the resulting code.

## Contribute or give feedback

[Try the evaluator](https://github.com/Yusyer174/Nexus-Agent-Evaluation/blob/main/docs/TRY_IT.md) · [Open issues](https://github.com/Yusyer174/Nexus-Agent-Evaluation/issues?q=is%3Aissue+is%3Aopen) · [Contributor guide](https://github.com/Yusyer174/Nexus-Agent-Evaluation/blob/main/CONTRIBUTING.md).

Focused bug reports, regression tests and documentation improvements are welcome. Please use synthetic or non-sensitive examples; never publish credentials or private agent data.
