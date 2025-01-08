---
title: 'VigDet: Knowledge Informed Neural Temporal Point Process for Coordination
  Detection on Social Media'
authors:
- Yizhou Zhang
- Karishma Sharma
- Yan Liu
date: '2021-10-01'
publishDate: '2025-01-08T06:22:33.514074Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2110.15454
abstract: Recent years have witnessed an increasing use of coordinated accounts on
  social media, operated by misinformation campaigns to influence public opinion and
  manipulate social outcomes. Consequently, there is an urgent need to develop an
  effective methodology for coordinated group detection to combat the misinformation
  on social media. However, existing works suffer from various drawbacks, such as,
  either limited performance due to extreme reliance on predefined signatures of coordination,
  or instead an inability to address the natural sparsity of account activities on
  social media with useful prior domain knowledge. Therefore, in this paper, we propose
  a coordination detection framework incorporating neural temporal point process with
  prior knowledge such as temporal logic or pre-defined filtering functions. Specifically,
  when modeling the observed data from social media with neural temporal point process,
  we jointly learn a Gibbs-like distribution of group assignment based on how consistent
  an assignment is to (1) the account embedding space and (2) the prior knowledge.
  To address the challenge that the distribution is hard to be efficiently computed
  and sampled from, we design a theoretically guaranteed variational inference approach
  to learn a mean-field approximation for it. Experimental results on a real-world
  dataset show the effectiveness of our proposed method compared to the SOTA model
  in both unsupervised and semi-supervised settings. We further apply our model on
  a COVID-19 Vaccine Tweets dataset. The detection result suggests the presence of
  suspicious coordinated efforts on spreading misinformation about COVID-19 vaccines.
tags:
- Computer Science - Artificial Intelligence
- Computer Science - Machine Learning
- Computer Science - Social and Information Networks
links:
- name: URL
  url: http://arxiv.org/abs/2110.15454
---
