---
title: Self-supervised Sim-to-Real Kinematics Reconstruction for Video-Based Assessment
  of Intraoperative Suturing Skills
authors:
- Loc Trinh
- Tim Chu
- Zijun Cui
- Anand Malpani
- Cherine Yang
- Istabraq Dalieh
- Alvin Hui
- Oscar Gomez
- Yan Liu
- Andrew Hung
date: '2023-01-01'
publishDate: '2025-01-08T06:22:33.384839Z'
publication_types:
- paper-conference
publication: '*Medical Image Computing and Computer Assisted Intervention – MICCAI
  2023*'
doi: 10.1007/978-3-031-43996-4_68
abstract: 'Suturing technical skill scores are strong predictors of patient functional
  recovery following robot-assisted radical prostatectomy (RARP), but manual assessment
  of these skills is a time and resource-intensive process. By automating suturing
  skill scoring through computer vision methods, we can significantly reduce the burden
  on healthcare professionals and enhance the quality and quantity of educational
  feedbacks. Although automated skill assessment on simulated virtual reality (VR)
  environments have been promising, applying vision methods to live (‘real’) surgical
  videos has been challenging due to: 1) the lack of kinematic data from the da Vinci®
  surgical system, a key source of information for determining the movement and trajectory
  of robotic manipulators and suturing needles, and 2) the lack of training data due
  to the labor-intensive task of segmenting and scoring individual stitches from live
  videos. To address these challenges, we developed a self-supervised pre-training
  paradigm whereby sim-to-real generalizable representations are learned without requiring
  any live kinematic annotations. Our model is based on a masked autoencoder (MAE),
  termed as LiveMAE. We augment live stitches with VR images during pre-training and
  require LiveMAE to reconstruct images from both domains while also predicting the
  corresponding kinematics. This process learns a visual-to-kinematic mapping that
  seeks to locate the positions and orientations of surgical manipulators and needles,
  deriving “kinematics” from live videos without requiring supervision. With an additional
  skill-specific finetuning step, LiveMAE surpasses supervised learning approaches
  across 6 technical skill assessments, ranging from 0.56–0.84 AUC (0.70–0.91 AUPRC),
  with particular improvements of 35.78% in AUC for wrist rotation skills and 8.7%
  for needle driving skills. Mean-squared error for test VR kinematics was as low
  as 0.045 for each element of the instrument poses. Our contributions provide the
  foundation to deliver personalized feedback to surgeons training in VR and performing
  live prostatectomy procedures.'
---
