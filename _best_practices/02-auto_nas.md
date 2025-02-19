---
layout: practice
author: Koen van der Blom, Alex Serban, Joost Visser
name: Automate Configuration of Algorithms or Model Structure
category: Training
unique_id: exp_auto_nas
index: 20
difficulty: "advanced"
references: #
comments: True
description:
image: #
photocredit: #

intent: Improve algorithm and model performance by automatically optimising their structures #
motivation: Predicting which algorithm and model architectures or structures are high-performing is very difficult, and trying different combinations is time-consuming. Optimisation tools are available to automate this. #
applicability: Any machine learning application can benefit from automatic configuration. #
related: [exp_hyperparam] #
dependencies: #
survey_question: Q91 #
survey_item: We use automated methods to configure our algorithms or the structure of our models.

labels:

---

Like with hyper-parameters, performance of machine learning models also depends on their structure (also: configuration or architecture). By using automated tools for this task, a larger number of options can be systematically evaluated, resulting in better performance than when manually trying different configurations.

Through the use of <a href="http://www.prog-by-opt.net/">programming by optimisation (PbO)</a> more configuration options might be exposed. For instance in the case of neural architecture search (NAS) you could only optimise the number of layers, but by also exposing the type of layers (e.g. convolutional, pooling, etc.) more and possibly better structures become available.

As with any ML method, automatically configured models should be carefully assessed by team members, and also undergo peer-review before being used in a production environment.

