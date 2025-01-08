---
title: Hierarchical Gaussian Mixture based Task Generative Model for Robust Meta-Learning
authors:
- Yizhou Zhang
- Jingchao Ni
- Wei Cheng
- Zhengzhang Chen
- Liang Tong
- Haifeng Chen
date: '2022-09-01'
publishDate: '2025-01-08T05:27:41.777218Z'
publication_types:
- article-journal
abstract: 'Meta-learning enables quick adaptation of machine learning models to new
  tasks with limited data. While tasks could come from varying distributions in reality,
  most of the existing meta-learning methods consider both training and testing tasks
  as from the same uni-component distribution, overlooking two critical needs of a
  practical solution: (1) the various sources of tasks may compose a multi-component
  mixture distribution, and (2) novel tasks may come from a distribution that is unseen
  during meta-training. In this paper, we demonstrate these two challenges can be
  solved jointly by modeling the density of task instances. We develop a meta-training
  framework underlain by a novel Hierarchical Gaussian Mixture based Task Generative
  Model (HTGM). HTGM extends the widely used empirical process of sampling tasks to
  a theoretical model, which learns task embeddings, fits mixture distribution of
  tasks, and enables density-based scoring of novel tasks. The framework is agnostic
  to the encoder and scales well with large backbone networks. The model parameters
  are learned end-to-end by maximum likelihood estimation via an Expectation-Maximization
  algorithm. Extensive experiments on benchmark datasets indicate the effectiveness
  of our method for both sample classification and novel task detection.'
links:
- name: URL
  url: https://openreview.net/forum?id=A4fSkNAs6E1
---
