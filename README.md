<div align="center">

# Yusyer | AI Engineering Portfolio

**Building reliable AI agents and reproducible machine learning systems**

[Agent Evaluation](https://github.com/Yusyer174/Nexus-Agent-Evaluation) · [Machine Learning](https://github.com/Yusyer174/house-prices-prediction-portfolio) · [About my work](#engineering-approach)

</div>

## About

I'm a technology student working toward a career in AI engineering. I build practical Python projects with a focus on clear evaluation criteria, reproducibility, and software reliability.

My main research interest is **NEXUS**, an independent multi-agent AI project exploring coordination, auditable decisions, and human oversight. The public evaluation tool below is a standalone prototype inspired by that work; the full system is not published.

## Featured projects

### 01 / NEXUS Agent Evaluation

[![Tests](https://github.com/Yusyer174/Nexus-Agent-Evaluation/actions/workflows/tests.yml/badge.svg)](https://github.com/Yusyer174/Nexus-Agent-Evaluation/actions/workflows/tests.yml)

A lightweight, dependency-free Python evaluator for structured AI-agent outputs.

- Checks expected decisions, declared actions, and evidence identifiers.
- Rejects critical-case failures and unexpected prediction IDs.
- Produces reproducible JSON reports and supports a configurable acceptance threshold.
- Installable command-line tool (v0.2.0); **19 automated tests** validated on Python 3.10–3.13.

[Source code and documentation](https://github.com/Yusyer174/Nexus-Agent-Evaluation) · [Verified CI run](https://github.com/Yusyer174/Nexus-Agent-Evaluation/actions/runs/43222260328)

> Scope: evaluates structured declarations against explicit test cases, not real-world agent safety or actual runtime permissions.

### 02 / California Housing Price Prediction

[![Baseline validation](https://github.com/Yusyer174/house-prices-prediction-portfolio/actions/workflows/baseline.yml/badge.svg)](https://github.com/Yusyer174/house-prices-prediction-portfolio/actions/workflows/baseline.yml)

An educational regression project with a reproducible training pipeline and a held-out test set.

| Test metric | Verified baseline |
| --- | ---: |
| R² | 0.6161 |
| RMSE | $70,925 |
| MAE | $51,215 |

- Uses scikit-learn pipelines for imputation, encoding, and linear regression.
- Fits preprocessing on training data only.
- Evaluates 4,128 held-out observations with a fixed random split.

[Source code and notebook](https://github.com/Yusyer174/house-prices-prediction-portfolio) · [Verified CI run](https://github.com/Yusyer174/house-prices-prediction-portfolio/actions/runs/43220651075)

> Scope: historical educational dataset; not a current real-estate valuation service.

## Technical toolkit

| Area | Tools and interests |
| --- | --- |
| Programming | Python, Git, GitHub |
| Machine learning | scikit-learn, pandas, NumPy |
| Data exploration | Jupyter, Matplotlib |
| Software quality | unittest, GitHub Actions, reproducible experiments |
| AI systems | Agent evaluation, multi-agent coordination, auditability |

## Engineering approach

```text
Define the problem → Build a baseline → Test assumptions
         → Measure results → Document limitations → Iterate
```

I aim to make each public project runnable, understandable, and honest about its limitations. A successful test suite is evidence about the tested behavior, not a guarantee of production readiness.

## Learning roadmap

- AI agent evaluation with independently designed test cases.
- Machine learning baselines, validation strategies, and error analysis.
- Reliable multi-agent architectures and human oversight.
- Software packaging, testing, documentation, and open-source collaboration.

---

<sub>Open-source contributions, reproducible bug reports, and constructive technical feedback are welcome.</sub>
