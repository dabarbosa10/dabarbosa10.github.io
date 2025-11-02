---
layout: default
title: "Linear Regression — Intuition and Implementation"
categories: [aiml]
tags: [regression, basics]
---

Linear regression models the relationship between input features and a continuous target by minimizing squared error.

## Core idea
We fit parameters **β** to minimize  

$$ \min_{\beta} \sum_{i=1}^{n} (y_i - X_i^\top \beta)^2.
$$

## Notes
- Closed-form (normal equation) and gradient descent both work.
- Watch for multicollinearity and outliers.

