---
layout: page
title: Adaptive Residual Partitioning Framework
description: Iterative residual-learning framework that dynamically partitions data into adaptive bins and retrains specialized models to improve prediction accuracy across heterogeneous datasets.
importance: 4
category: research
github: jassinghjatt/Adaptive-Residual-Partitioning-Framework
---

### Overview

Adaptive Residual Partitioning Framework (ARPF) is a general-purpose machine learning methodology designed for modelling complex residual structures in heterogeneous datasets.

The framework iteratively:

- Partitions data into residual-based bins
- Trains specialized models within each partition
- Updates bin boundaries using newly predicted residuals
- Repeats the process until convergence

Although developed for nuclear mass residual modelling, the methodology is applicable to any regression problem exhibiting non-uniform residual distributions and localized prediction patterns.

### Applications

- Nuclear mass modelling
- Scientific data analysis
- Time-series forecasting
- Financial modelling
- Engineering regression problems

### Resources

- [GitHub Repository](https://github.com/jassinghjatt/Adaptive-Residual-Partitioning-Framework)