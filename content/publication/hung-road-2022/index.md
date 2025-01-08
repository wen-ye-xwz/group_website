---
title: 'Road to automating robotic suturing skills assessment: Battling mislabeling
  of the ground truth'
authors:
- Andrew J. Hung
- Sirisha Rambhatla
- Daniel I. Sanford
- Nilay Pachauri
- Erik Vanstrum
- Jessica H. Nguyen
- Yan Liu
date: '2022-04-01'
publishDate: '2025-01-08T06:22:33.522150Z'
publication_types:
- article-journal
publication: '*Surgery*'
doi: 10.1016/j.surg.2021.08.014
abstract: "OBJECTIVE: To automate surgeon skills evaluation using robotic instrument
  kinematic data. Additionally, to implement an unsupervised mislabeling detection
  algorithm to identify potentially mislabeled samples that can be removed to improve
  model performance. METHODS: Video recordings and instrument kinematic data were
  derived from suturing exercises completed on the Mimic FlexVR robotic simulator.
  A structured human consensus-building process was developed to determine Robotic
  Anastomosis Competency Evaluation technical scores across 3 human graders. A 2-layer
  long short-term memory-based classification model used instrument kinematic data
  to automate suturing skills assessment. An unsupervised label analyzer (NoiseRank)
  was used to identify potential mislabeling of skills data. Performance of the long
  short-term memory model's technical skill score prediction was measured by best
  area under the curve over the training runs. NoiseRank outputted a ranked list of
  rated skills assessments based on likelihood of mislabeling. RESULTS: 22 surgeons
  performed 226 suturing attempts, which were broken down into 1,404 individual skill
  assessment points. Automation of needle entry angle, needle driving, and needle
  withdrawal technical skill scores performed better (area under the curve 0.698-0.705)
  than needle positioning (0.532) at baseline using all available data. Potential
  mislabels were subsequently identified by NoiseRank and removed, improving model
  performance across all domains (area under the curve 0.551-0.766). CONCLUSION: Using
  ground truth labels from human graders and robotic instrument kinematic data, machine
  learning models have automated assessment of detailed suturing technical skills
  with good performance. Further, an unsupervised mislabeling detection algorithm
  projected mislabeled data, allowing for their removal and subsequent improvement
  of model performance."
tags:
- Clinical Competence
- Humans
- Robotic Surgical Procedures
- Robotics
- Surgeons
- Sutures
---
