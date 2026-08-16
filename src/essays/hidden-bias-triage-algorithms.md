---
layout: essay.njk
title: "The Hidden Bias in Triage Algorithms"
date: 2026-08-16
description: "How risk-scoring models trained on historical utilization data can systematically underestimate need in underserved populations."
tags: essay
---

Draft placeholder — replace with the real essay text.

A common pattern in clinical risk-scoring models: when a model is trained to predict
future healthcare *cost* as a proxy for future healthcare *need*, it can inherit the
access gaps already baked into the historical data. Patients who were underserved in
the past show up as "low cost," and the model learns to treat them as "low need" —
even when their actual clinical risk is high.

This essay would walk through:
- how proxy variables introduce bias even without protected attributes in the model
- a real published example (e.g. the 2019 Obermeyer et al. study on a widely used
  commercial risk-prediction algorithm)
- what "fixing" bias in a deployed clinical model actually requires
