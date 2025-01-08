---
title: Enhancing Self-Attention with Knowledge-Assisted Attention Maps
authors:
- Jiangang Bai
- Yujing Wang
- Hong Sun
- Ruonan Wu
- Tianmeng Yang
- Pengfei Tang
- Defu Cao
- Mingliang Zhang1
- Yunhai Tong
- Yaming Yang
- Jing Bai
- Ruofei Zhang
- Hao Sun
- Wei Shen
date: '2022-07-01'
publishDate: '2025-01-08T06:22:33.482677Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 2022 Conference of the North American Chapter of
  the Association for Computational Linguistics: Human Language Technologies*'
doi: 10.18653/v1/2022.naacl-main.8
abstract: Large-scale pre-trained language models have attracted extensive attentions
  in the research community and shown promising results on various tasks of natural
  language processing. However, the attention maps, which record the attention scores
  between tokens in self-attention mechanism, are sometimes ineffective as they are
  learned implicitly without the guidance of explicit semantic knowledge. Thus, we
  aim to infuse explicit external knowledge into pre-trained language models to further
  boost their performance. Existing works of knowledge infusion largely depend on
  multi-task learning frameworks, which are inefficient and require large-scale re-training
  when new knowledge is considered. In this paper, we propose a novel and generic
  solution, KAM-BERT, which directly incorporates knowledge-generated attention maps
  into the self-attention mechanism. It requires only a few extra parameters and supports
  efficient fine-tuning once new knowledge is added. KAM-BERT achieves consistent
  improvements on various academic datasets for natural language understanding. It
  also outperforms other state-of-the-art methods which conduct knowledge infusion
  into transformer-based architectures. Moreover, we apply our model to an industry-scale
  ad relevance application and show its advantages in the real-world scenario.
links:
- name: URL
  url: https://aclanthology.org/2022.naacl-main.8/
---
