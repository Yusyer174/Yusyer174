# Yus-Builds (@Yusyer174)

I’m a technology student learning software engineering through Python projects in machine learning and AI-agent evaluation. I publish runnable examples, test results and limitations so others can check the work.

[**Try the live NEXUS Evaluation Lab**](https://yusyer174.github.io/Nexus-Agent-Evaluation/) · [CLI quickstart](https://github.com/Yusyer174/Nexus-Agent-Evaluation/blob/main/docs/TRY_IT.md) · [View projects](#selected-projects) · [Open-source contributions](#open-source-collaboration)

## Selected projects

### [NEXUS Agent Evaluation](https://github.com/Yusyer174/Nexus-Agent-Evaluation)

A dependency-free Python evaluator for catching regressions in structured AI-agent outputs. It checks reported decisions, actions and evidence IDs against explicit test cases.

- [Open the interactive browser demo](https://yusyer174.github.io/Nexus-Agent-Evaluation/): explore five synthetic scenarios, edit test cases and predictions, adjust the minimum pass rate, and inspect or export the resulting report. No installation or API key required.
- Run the [passing and failing examples](https://github.com/Yusyer174/Nexus-Agent-Evaluation#see-the-result) with Python 3.10+ and no API key.
- See the [input/output contract](https://github.com/Yusyer174/Nexus-Agent-Evaluation/blob/main/docs/INTEGRATION.md), [GitHub Action demo](https://github.com/Yusyer174/Nexus-Agent-Evaluation/blob/main/docs/CONSUMER_TRIAL.md) and [CI runs](https://github.com/Yusyer174/Nexus-Agent-Evaluation/actions?query=branch%3Amain).

The latest verified main revision includes 37 Python regression tests; the [unpublished 0.3.0rc1 review candidate](https://github.com/Yusyer174/Nexus-Agent-Evaluation/pull/22) adds synthetic scenarios and explicit scope counterexamples. CI results and candidate status are visible on the linked pull request.

This early prototype checks reported outputs. Runtime enforcement, evidence authentication and real-world agent safety are outside its scope.

### [California Housing Price Prediction](https://github.com/Yusyer174/house-prices-prediction-portfolio)

An educational scikit-learn baseline for historical California housing values, with a fixed holdout and preprocessing fitted on training data only.

| Historical holdout (4,128 examples) | Result |
| --- | ---: |
| R² | 0.6161 |
| RMSE | $70,925 |
| MAE | $51,215 |

[Reproduce the baseline](https://github.com/Yusyer174/house-prices-prediction-portfolio#run-locally) · [Model card and limitations](https://github.com/Yusyer174/house-prices-prediction-portfolio/blob/main/MODEL_CARD.md) · [Validation run](https://github.com/Yusyer174/house-prices-prediction-portfolio/actions/runs/43220651075).

These results describe one historical holdout. Generalization to new regions and current prices remains untested.

## Open-source collaboration

- I submitted a draft [PR to AI-Research-Agent](https://github.com/hemanthkumar1012/AI-Research-Agent/pull/2) with a focused citation-source isolation test, following the upstream maintainer’s guidance.
- An external contributor submitted a duplicate-JSON-key regression test for [NEXUS issue #9](https://github.com/Yusyer174/Nexus-Agent-Evaluation/issues/9). I reviewed it, and [PR #16](https://github.com/Yusyer174/Nexus-Agent-Evaluation/pull/16) was merged after all 15 CI checks passed.
- A second external contributor added regression tests for duplicate evidence identifiers. [PR #20](https://github.com/Yusyer174/Nexus-Agent-Evaluation/pull/20) passed all six PR workflows and was merged.
- I submitted [RepoHeart PR #107](https://github.com/OpenAgentHQ/repo-heart/pull/107), a synthetic `workflow_run.completed` fixture with a failure conclusion for an existing contributor task; it is awaiting upstream review.
- Two more external developers have submitted test-only contributions: Aadithya-kl ([PR #26](https://github.com/Yusyer174/Nexus-Agent-Evaluation/pull/26), [PR #27](https://github.com/Yusyer174/Nexus-Agent-Evaluation/pull/27)) and jwalith4418-Mj ([PR #28](https://github.com/Yusyer174/Nexus-Agent-Evaluation/pull/28)). An AI-assisted maintainer review reproduced all seven new tests and the combined 44-test suite locally on Python 3.13.5; GitHub Actions approval and merge are still pending. These are submitted contributions, not merged work or adoption evidence.
- [NEXUS issue #8](https://github.com/Yusyer174/Nexus-Agent-Evaluation/issues/8) invites developers to try the evaluator and report what works, what fails and what is unclear.

## What I am learning

Python · Git · GitHub Actions · unittest · pandas · NumPy · scikit-learn · agent evaluation · reproducible experiments.

I use AI tools to assist development. My learning process includes reading the resulting code, testing failure paths and explaining the results.

## Contribute or give feedback

[Open the live demo](https://yusyer174.github.io/Nexus-Agent-Evaluation/) · [Try the CLI](https://github.com/Yusyer174/Nexus-Agent-Evaluation/blob/main/docs/TRY_IT.md) · [Open issues](https://github.com/Yusyer174/Nexus-Agent-Evaluation/issues?q=is%3Aissue+is%3Aopen) · [Contributor guide](https://github.com/Yusyer174/Nexus-Agent-Evaluation/blob/main/CONTRIBUTING.md).

Focused bug reports, regression tests and documentation improvements are welcome. Please use synthetic or non-sensitive examples and keep credentials and private agent data out of reports.
