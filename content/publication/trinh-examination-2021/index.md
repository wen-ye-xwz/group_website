---
title: An Examination of Fairness of AI Models for Deepfake Detection
authors:
- Loc Trinh
- Yan Liu
date: '2021-05-01'
publishDate: '2025-01-08T06:22:33.581420Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2105.00558
abstract: Recent studies have demonstrated that deep learning models can discriminate
  based on protected classes like race and gender. In this work, we evaluate bias
  present in deepfake datasets and detection models across protected subgroups. Using
  facial datasets balanced by race and gender, we examine three popular deepfake detectors
  and find large disparities in predictive performances across races, with up to 10.7%
  difference in error rate between subgroups. A closer look reveals that the widely
  used FaceForensics++ dataset is overwhelmingly composed of Caucasian subjects, with
  the majority being female Caucasians. Our investigation of the racial distribution
  of deepfakes reveals that the methods used to create deepfakes as positive training
  signals tend to produce \"irregular\" faces - when a person's face is swapped onto
  another person of a different race or gender. This causes detectors to learn spurious
  correlations between the foreground faces and fakeness. Moreover, when detectors
  are trained with the Blended Image (BI) dataset from Face X-Rays, we find that those
  detectors develop systematic discrimination towards certain racial subgroups, primarily
  female Asians.
tags:
- Computer Science - Artificial Intelligence
- Computer Science - Computer Vision and Pattern Recognition
links:
- name: URL
  url: http://arxiv.org/abs/2105.00558
---
