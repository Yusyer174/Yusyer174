<div align="center">

# Yusyer · AI Engineering Portfolio

**Practical Python, reproducible machine learning, and testable AI-agent evaluation**

[Agent Evaluation](https://github.com/Yusyer174/Nexus-Agent-Evaluation) · [Machine Learning](https://github.com/Yusyer174/house-prices-prediction-portfolio) · [Engineering principles](#how-i-work)

</div>

## About

I'm a technology student working toward AI engineering. I build small, inspectable Python projects and document **what the evidence establishes—and what it does not**.

My ongoing private research project, **NEXUS**, explores multi-agent coordination, auditable decisions and human oversight. The public NEXUS evaluator below is a separate educational prototype: it is **not** the private runtime, a security sandbox, or proof of autonomous-agent safety.

## Selected public work

### 1. [NEXUS Agent Evaluation](https://github.com/Yusyer174/Nexus-Agent-Evaluation)

[![Tests](https://github.com/Yusyer174/Nexus-Agent-Evaluation/actions/workflows/tests.yml/badge.svg)](https://github.com/Yusyer174/Nexus-Agent-Evaluation/actions/workflows/tests.yml)
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/Yusyer174/Nexus-Agent-Evaluation/blob/main/LICENSE)

**Problem:** How can a developer check structured agent outputs against explicit expected decisions and declared constraints?

**Implemented:** A dependency-free Python evaluator, installable CLI, synthetic fixtures, automated tests and CI across Python 3.10–3.13. It reports pass rates and blocks acceptance on critical-case failures or unexpected prediction IDs.

**Boundaries:** It checks *reported fields*, not actual runtime execution, permission enforcement, or evidence authenticity.

**Try it:** [5-minute independent trial](https://github.com/Yusyer174/Nexus-Agent-Evaluation/blob/main/docs/TRY_IT.md) · [GitHub Action integration](https://github.com/Yusyer174/Nexus-Agent-Evaluation/blob/main/action.yml) · [Give genuine feedback](https://github.com/Yusyer174/Nexus-Agent-Evaluation/issues/8)

[Read documentation](https://github.com/Yusyer174/Nexus-Agent-Evaluation#readme) · [Browse tests](https://github.com/Yusyer174/Nexus-Agent-Evaluation/tree/main/tests) · [Issues](https://github.com/Yusyer174/Nexus-Agent-Evaluation/issues)

### 2. [California Housing Price Prediction](https://github.com/Yusyer174/house-prices-prediction-portfolio)

[![Baseline validation](https://github.com/Yusyer174/house-prices-prediction-portfolio/actions/workflows/baseline.yml/badge.svg)](https://github.com/Yusyer174/house-prices-prediction-portfolio/actions/workflows/baseline.yml)

**Problem:** Establish an understandable regression baseline on a historical California housing dataset.

**Implemented:** A reproducible scikit-learn pipeline with preprocessing fit on training data only, a fixed holdout split, automated regression checks and a notebook.

| Held-out baseline (4,128 rows) | Result |
| --- | ---: |
| R² | 0.6161 |
| RMSE | $70,925 |
| MAE | $51,215 |

**Boundaries:** One historical random split does not measure performance on new regions, future years or real-world valuations.

[Run the project](https://github.com/Yusyer174/house-prices-prediction-portfolio#run-locally) · [Inspect the training code](https://github.com/Yusyer174/house-prices-prediction-portfolio/blob/main/train.py)

## How I work

1. **Start with a baseline:** Define inputs, expected outputs, and assumptions.
2. **Build reproducibly:** Record dependencies, deterministic seeds where practical, and exact commands.
3. **Test failure paths:** Cover malformed data, edge cases, and critical constraints—not just happy paths.
4. **Publish evidence with scope:** Explain metrics and limits rather than equating tests with production readiness.
5. **Improve through review:** Welcome reproducible bugs, constructive issues and focused pull requests.

## Toolbox

**Python · Git · GitHub Actions · unittest · scikit-learn · pandas · NumPy · Jupyter**

Current learning priorities: independent holdout evaluation, packaging and developer tooling, regression analysis, and reliable AI-agent interfaces.

## Contributing and feedback

The public repositories are small, MIT-licensed learning projects. If you notice a bug or can improve an example, open an issue with reproduction steps or a focused PR. Please **never publish credentials, private datasets, or sensitive security details** in an issue.

---

<sub>Public work is provided for learning and reproducible experimentation. No claims of production deployment, broad adoption, or independent certification.</sub>
