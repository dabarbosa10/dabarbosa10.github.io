---
layout: default
title: "Logistic Regression — Classification"
permalink: /aiml/logistic-regression/
categories: [aiml]
---

# Logistic Regression

Logistic regression predicts class probabilities via the logistic (sigmoid) function.

\[
P(y=1 \mid x) = \sigma(w^\top x + b) = \frac{1}{1 + e^{-(w^\top x + b)}}
\]

- Loss: binary cross-entropy
- Regularization: L1/L2
- Metrics: accuracy, precision/recall, ROC-AUC
