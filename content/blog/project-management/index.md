---
title: Portfolio prioritization for corrosion-critical assets
summary: A practical workflow for ranking interventions across infrastructure portfolios.
date: 2023-10-23
authors:
  - me
tags:
  - Portfolio
  - Risk
  - Maintenance
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com)'
---

When resources are limited, the question is not whether to intervene but **where and when**. A portfolio approach ties
probabilistic risk to budget and operational constraints.

## A simple prioritization workflow

```mermaid
gantt
  title Portfolio Prioritization (Illustrative)
  dateFormat  YYYY-MM-DD
  section Intake
  Data review          :done,    a1, 2023-10-01, 7d
  Exposure alignment   :active,  a2, after a1, 7d
  section Modeling
  Parameter calibration:         b1, after a2, 10d
  Risk envelopes       :         b2, after b1, 7d
  section Decisions
  Action ranking       :         c1, after b2, 7d
  Budget scheduling    :         c2, after c1, 7d
```

## Ranking criteria that hold up in review

- Probability of corrosion initiation and propagation
- Consequence of failure and service disruption
- Timing sensitivity (cost escalation vs delay)
- Exposure severity and uncertainty

## Output formats clients prefer

- Ranked asset list with thresholds and triggers
- Scenario tables for do-nothing vs intervention
- Portfolio map of exposure classes and risk tiers

If you want us to adapt this to your asset classes (bridges, marine structures, industrial plants), share a sample
inventory and we will outline a tailored approach.
