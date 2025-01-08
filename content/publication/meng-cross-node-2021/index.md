---
title: Cross-Node Federated Graph Neural Network for Spatio-Temporal Data Modeling
authors:
- Chuizheng Meng
- Sirisha Rambhatla
- Yan Liu
date: '2021-06-01'
publishDate: '2025-01-08T06:22:33.559083Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2106.05223
abstract: Vast amount of data generated from networks of sensors, wearables, and the
  Internet of Things (IoT) devices underscores the need for advanced modeling techniques
  that leverage the spatio-temporal structure of decentralized data due to the need
  for edge computation and licensing (data access) issues. While federated learning
  (FL) has emerged as a framework for model training without requiring direct data
  sharing and exchange, effectively modeling the complex spatio-temporal dependencies
  to improve forecasting capabilities still remains an open problem. On the other
  hand, state-of-the-art spatio-temporal forecasting models assume unfettered access
  to the data, neglecting constraints on data sharing. To bridge this gap, we propose
  a federated spatio-temporal model -- Cross-Node Federated Graph Neural Network (CNFGNN)
  -- which explicitly encodes the underlying graph structure using graph neural network
  (GNN)-based architecture under the constraint of cross-node federated learning,
  which requires that data in a network of nodes is generated locally on each node
  and remains decentralized. CNFGNN operates by disentangling the temporal dynamics
  modeling on devices and spatial dynamics on the server, utilizing alternating optimization
  to reduce the communication cost, facilitating computations on the edge devices.
  Experiments on the traffic flow forecasting task show that CNFGNN achieves the best
  forecasting performance in both transductive and inductive learning settings with
  no extra computation cost on edge devices, while incurring modest communication
  cost.
tags:
- Computer Science - Artificial Intelligence
- Computer Science - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2106.05223
---
