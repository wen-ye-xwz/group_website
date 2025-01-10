---
title: Proximity-Based Anomaly Detection using Sparse Structure Learning
authors:
- Tsuyoshi Idé
- Aurelie C. Lozano
- Naoki Abe
- Yan Liu
date: '2009-04-01'
publishDate: '2025-01-10T01:56:20.059615Z'
publication_types:
- chapter
publication: '*Proceedings of the 2009 SIAM International Conference on Data Mining
  (SDM)*'
doi: 10.1137/1.9781611972795.9
abstract: We consider the task of performing anomaly detection in highly noisy multivariate
  data. In many applications involving real-valued time-series data, such as physical
  sensor data and economic metrics, discovering changes and anomalies in the way variables
  depend on one another is of particular importance. Our goal is to robustly compute
  the “correlation anomaly” score of each variable by comparing the test data with
  reference data, even when some of the variables are highly correlated (and thus
  collinearity exists). To remove seeming dependencies introduced by noise, we focus
  on the most significant dependencies for each variable. We perform this “neighborhood
  selection” in an adaptive manner by fitting a sparse graphical Gaussian model. Instead
  of traditional covariance selection procedures, we solve this problem as maximum
  likelihood estimation of the precision matrix (inverse covariance matrix) under
  the L1 penalty. Then the anomaly score for each variable is computed by evaluating
  the distances between the fitted conditional distributions within the Markov blanket
  for that variable, for the (two) data sets to be compared. Using real-world data,
  we demonstrate that our matrix-based sparse structure learning approach successfully
  detects correlation anomalies under collinearities and heavy noise.
links:
- name: URL
  url: https://epubs.siam.org/doi/10.1137/1.9781611972795.9
---
