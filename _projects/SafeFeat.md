---
title: "safefeat: Leakage-Safe Feature Engineering for Event Logs (Python)"
excerpt: "A Python package for point-in-time, leakage-safe feature engineering from event data."
collection: projects
date: 2026-02-18
---

Tech: Python · feature engineering · machine learning · MLOps

## `safefeat` Tool

*safefeat* is a Python package for leakage-safe, point-in-time feature engineering from event logs. It builds features for each `(entity_id, cutoff_time)` pair using only events that occurred at or before the cutoff time, ensuring no future data leakage — a common pitfall in building ML models on temporal data.

The package works around three core components: a **Spine** (defining when predictions are made), an **Events** table (historical event log), and a **Feature Specification** (a declarative description of what features to compute). This design makes it straightforward to build reproducible, production-ready feature pipelines for tasks such as churn prediction, fraud detection, and behavioural modelling.

Key features include:
- **Window aggregations** — count, sum, mean, and unique counts over configurable time windows (e.g. 7D, 30D)
- **Recency features** — time since last event, useful for churn, fraud, and behavioural models
- **Configurable lag** — strict enforcement of point-in-time correctness via `allowed_lag`

## My Contributions

- Designed and built an open-source Python package for leakage-safe feature engineering from event logs • Published on PyPI • Full MkDocs documentation • Built with applied ML workflows in mind, particularly for user behaviour, fraud, and healthcare event data.

### Links:

[GitHub](https://github.com/AlishaAng/safefeat)  
[Documentation](https://alishaang.github.io/safefeat/)  
[PyPI](https://pypi.org/project/safefeat/)
