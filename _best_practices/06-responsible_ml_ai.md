---
layout: practice
author: Alex Serban, Koen van der Blom, Joost Visser
name: Enforce Fairness and Privacy
title: Enforce Fairness and Privacy
category: Governance
unique_id: gov_responsible
index: 47
difficulty: "medium"
references: [MLFAIR, MLRES]
comments: True
description:
image: #
photocredit: #

intent: Avoid irresponsible use of machine learning and decisions with negative societal impact. #
motivation: When processing personal information or when developing decision making systems that can negatively impact individuals or groups, it is important to enforce requirements for fairness and privacy. #
applicability: Responsible ML should be applied in any production-level ML application that processes personal data or has a potentially negative an impact on society.
related: [social_bias, subgroup_bias, privacy_preserving, exp_status, deployment_monitor] #
dependencies: #
survey_question: Q64

labels: EU

---

Machine learning is a data driven process and, in most cases, the algorithm's performance improves when using more data.
This characteristic of machine learning algorithms is a central drive for collecting and processing more data.
Although there are many benefits that can be harvested from processing personal or sensitive data, it is essential to consider and assess the potential privacy violations in using this data.


Moreover, if the machine learning model you are developing makes decisions about individuals that can have a negative impact on their life -- e.g. an automatic loan system that may automatically refuse loans -- it is crucial to assess the algorithm's fairness and inclusiveness for all members of the society.
Moreover, it is crucial to assess that decisions are based on clear and interpretable features.

Whenever processing personal information or whenever developing algorithms that take automated decisions, consider to:
- assess that personal data used does not breach privacy,
- use privacy preserving machine learning whenever possible, e.g. differential privacy,
- define and implement metrics for bias, fairness and responsible use of machine learning,
- take security into account -- confidential information can be leaked by machine learning algorithms,
- continuously monitor that the algorithm behaves responsibly,
- be as transparent as possible about the data used and the model you are developing.

