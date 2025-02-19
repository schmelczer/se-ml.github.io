---
layout: practice
author: Alex Serban, Koen van der Blom, Joost Visser
name: Enable Automatic Roll Backs for Production Models
title: Enable Automatic Roll Backs for Production Models
category: Deployment
unique_id: deployment_rollback
index: 36
difficulty: "medium"
references: [MLLG, CD4ML]
comments: True
description:
image: #
photocredit: #

intent: Avoid sub-optimal models in production. #
motivation: Similar to deployment, rolling back models can be a tedious process. Instead of manually performing this task, it is recommended to define an automatic process for it. #
applicability: Automatic rollbacks should be implemented in any production-level ML application.
related: [deployment_automate, deployment_monitor] #
dependencies: #
survey_question: Q62

labels: agility

---

If, due to changes in the input data or undetected skew, a deployed model performs sub-optimal, it should be rolled back to an earlier, better performing version.

Designing a process for automatic roll-back minimizes the time a deployed model with sub-optimal performance is kept in production.
