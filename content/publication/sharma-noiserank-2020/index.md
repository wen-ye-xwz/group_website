---
title: 'NoiseRank: Unsupervised Label Noise Reduction with Dependence Models'
authors:
- Karishma Sharma
- Pinar Donmez
- Enming Luo
- Yan Liu
- I. Zeki Yalniz
date: '2020-03-01'
publishDate: '2025-01-08T09:52:10.356964Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2003.06729
abstract: Label noise is increasingly prevalent in datasets acquired from noisy channels.
  Existing approaches that detect and remove label noise generally rely on some form
  of supervision, which is not scalable and error-prone. In this paper, we propose
  NoiseRank, for unsupervised label noise reduction using Markov Random Fields (MRF).
  We construct a dependence model to estimate the posterior probability of an instance
  being incorrectly labeled given the dataset, and rank instances based on their estimated
  probabilities. Our method 1) Does not require supervision from ground-truth labels,
  or priors on label or noise distribution. 2) It is interpretable by design, enabling
  transparency in label noise removal. 3) It is agnostic to classifier architecture/optimization
  framework and content modality. These advantages enable wide applicability in real
  noise settings, unlike prior works constrained by one or more conditions. NoiseRank
  improves state-of-the-art classification on Food101-N (~20% noise), and is effective
  on high noise Clothing-1M (~40% noise).
tags:
- Computer Science - Computer Vision and Pattern Recognition
- Computer Science - Machine Learning
- Statistics - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2003.06729
---
