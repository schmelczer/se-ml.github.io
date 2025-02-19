---
layout: practice
author: Alex Serban, Koen van der Blom, Joost Visser
name: Assign an Owner to Each Feature and Document its Rationale
title: Assign an Owner to Each Feature and Document its Rationale
category: Training
unique_id: exp_owner
index: 13
difficulty: "medium"
comments: True
references: [Rs4ML]
description:
image: #
photocredit: #

intent: Enhance feature development, understanding and maintenance. #
motivation: In a large data set, with multiple features that are composed from distinct data attributes, it is hard to keep track and understand all features. By assigning an owner and documenting each feature, they become easier to maintain and comprehend. #
applicability: Features should have an owner and documentation whenever features are manually engineered (and not automatically extracted, e.g. through deep learning).
related: [exp_archive] #
dependencies: #
survey_question: Q39

labels: quality

---

Ensuring that someone in the team is in charge of the information regarding a feature facilitates feature maintainability, and improves the overall understanding of the data and models.


Although feature names can be descriptive, it is important to also document their rationale in order to facilitate communication and share the knowledge among team members.


This practice suggests that whenever a feature owner is leaving a team, the ownership is transferred to other members.