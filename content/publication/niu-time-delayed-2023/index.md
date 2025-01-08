---
title: Time-delayed Multivariate Time Series Predictions
authors:
- Hao Niu
- Guillaume Habault
- Roberto Legaspi
- Chuizheng Meng
- Defu Cao
- Shinya Wada
- Chihiro Ono
- Yan Liu
date: '2023-01-01'
publishDate: '2025-01-08T06:22:33.400023Z'
publication_types:
- chapter
publication: '*Proceedings of the 2023 SIAM International Conference on Data Mining
  (SDM)*'
doi: 10.1137/1.9781611977653.ch37
abstract: 'A major issue with real-time monitoring is to collect complete data. Hardware
  or software failures, network issues or, more frequently, time delays can disrupt
  such a collection. This results in having two versions of the same information:
  one in real-time but with potentially missing data, and the another, albeit complete,
  is delayed. Many works have studied how to handle missing data for classification
  and prediction. However, to the best of our knowledge, they do not consider how
  to leverage the delayed complete data to assist in learning the representation of
  real-time available data with missing values. This is despite the fact that the
  delayed complete data contain all the information (e.g., periodicities and trends).
  In this paper, we propose a framework to enhance the representation learning of
  the real-time available data by aligning the representation of past real-time but
  with missing data to that of past delayed but complete data. We test both a distance
  metric and contrastive learning to achieve this alignment. We implement our framework
  on a Transformer-based model and experiment it on three datasets. The efficiency
  of our solution is evaluated against seven baselines and considering four distinct
  patterns of missing data. Our experiments show that this proposal has a significant
  improvement in prediction accuracy (5.21% on average) over the baselines.'
links:
- name: URL
  url: https://epubs.siam.org/doi/10.1137/1.9781611977653.ch37
---
