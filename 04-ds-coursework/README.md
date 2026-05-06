# 04 — DS Coursework

Deep-dive modules on the technical concepts that come up in Data Science interviews — built the same way as the case study playbook: full content, no outlines, no "expand later."

**Status: Planned**

---

## Why This Exists

The case study playbook (folder 01) covers technical concepts at the depth needed for case interviews — but there's a separate class of technical questions that shows up in DS loops: statistics, ML theory, probability, SQL, and experimentation design at a level that requires more than a framework.

This folder is for that. Module by module, built in the order they come up most frequently.

---

## Planned Modules

| Module | Topics | Status |
|--------|---------|--------|
| `01-statistics-fundamentals` | Distributions, CLT, hypothesis testing, confidence intervals, power analysis, common pitfalls | Planned |
| `02-ab-testing-deep-dive` | Beyond the basics: CUPED, variance reduction, sequential testing, switchback experiments, interference, network effects | Planned |
| `03-regression-and-causal-inference` | OLS, logistic regression, DiD, RDD, PSM, IV — intuition + when to use each | Planned |
| `04-machine-learning-breadth` | Supervised, unsupervised, bias-variance tradeoff, feature engineering, model evaluation, common algorithms | Planned |
| `05-recommendation-systems` | Collaborative filtering, content-based, hybrid, cold start, evaluation metrics | Planned |
| `06-sql-patterns` | Window functions, cohort analysis, retention queries, funnel analysis, tricky joins | Planned |
| `07-probability-and-combinatorics` | Classic problems, expected value, Bayesian reasoning, common DS interview brainteasers | Planned |
| `08-time-series` | ARIMA, stationarity, seasonality decomposition, forecasting evaluation | Planned |

---

## Format

Each module will follow the same structure as the case study playbook:
- Core concepts explained from first principles
- Worked examples you can follow without code
- Interview-specific framing (how to explain this to a non-technical PM, how to discuss tradeoffs)
- Common misconceptions and how interviewers test for them
- Quick reference summary at the end

---

## Generation Approach

Same as the case study playbook — full content, generated with Claude, anchored to the actual interview bar at FAANG-level tech companies. Prompts for each module will be in a `prompts.md` file within each module folder.

---

## Priority Order

Modules will be built in order of:
1. How often they appear in DS interview loops
2. How much they overlap with case study prep (reinforcement > isolated topics)
3. Where the gap between "I know this" and "I can explain it under pressure" is largest

Based on that: statistics → A/B testing deep-dive → regression/causal inference → ML breadth → SQL → the rest.
