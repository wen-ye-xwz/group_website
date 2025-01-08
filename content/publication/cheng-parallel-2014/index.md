---
title: Parallel gibbs sampling for hierarchical dirichlet processes via gamma processes
  equivalence
authors:
- Dehua Cheng
- Yan Liu
date: '2014-08-01'
publishDate: '2025-01-08T22:54:33.197898Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 20th ACM SIGKDD international conference on Knowledge
  discovery and data mining*'
doi: 10.1145/2623330.2623708
abstract: The hierarchical Dirichlet process (HDP) is an intuitive and elegant technique
  to model data with latent groups. However, it has not been widely used for practical
  applications due to the high computational costs associated with inference. In this
  paper, we propose an effective parallel Gibbs sampling algorithm for HDP by exploring
  its connections with the gamma-gamma-Poisson process. Specifically, we develop a
  novel framework that combines bootstrap and Reversible Jump MCMC algorithm to enable
  parallel variable updates. We also provide theoretical convergence analysis based
  on Gibbs sampling with asynchronous variable updates. Experiment results on both
  synthetic datasets and two large-scale text collections show that our algorithm
  can achieve considerable speedup as well as better inference accuracy for HDP compared
  with existing parallel sampling algorithms.
links:
- name: URL
  url: https://doi.org/10.1145/2623330.2623708
---
