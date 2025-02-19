---
layout: practice
author: Alex Serban, Koen van der Blom, Joost Visser
name: Continuously Monitor the Behaviour of Deployed Models
title: Continuously Monitor the Behaviour of Deployed Models
category: Deployment
unique_id: deployment_monitor
index: 34
difficulty: "medium"
references: [CD4ML, MLPROD, MLLG, TFX, TDBML]
comments: True
description:
image: #
photocredit: #

intent: Avoid unintended behaviour in production models. #
motivation: Once a model is promoted to production, the team has to understand how it performs. #
applicability: Monitoring should be implemented in any production-level ML application.
related: [deployment_distskew, deployment_rollback, exp_quality] #
dependencies: #
survey_question: Q60

labels: [agility, traceability]

---

Monitoring plays an important role in production level machine learning.
Because the performance between training and production data can vary drastically, it is important to continuously monitor the behaviour of deployed models and raise alerts when unintended behaviour is observed.

The monitoring pipeline should include:
- performance, quality and skew metrics,
- fairness metrics,
- model interpretability outputs (e.g. <a href="https://arxiv.org/pdf/1602.04938v1.pdf">LIME</a>),
- metrics for the perceived effect of the model, e.g. user interactions, conversion rates, etc.