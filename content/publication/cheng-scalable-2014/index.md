---
title: Scalable Parallel Factorizations of SDD Matrices and Efficient Sampling for
  Gaussian Graphical Models
authors:
- Dehua Cheng
- Yu Cheng
- Yan Liu
- Richard Peng
- Shang-Hua Teng
date: '2014-10-01'
publishDate: '2025-01-08T22:54:33.182730Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.1410.5392
abstract: Motivated by a sampling problem basic to computational statistical inference,
  we develop a nearly optimal algorithm for a fundamental problem in spectral graph
  theory and numerical analysis. Given an $ntimes n$ SDDM matrix $bf mathbfM$, and
  a constant $-1 leq p leq 1$, our algorithm gives efficient access to a sparse $ntimes
  n$ linear operator $tildemathbfC$ such that $$mathbfMtextasciicircump approx tildemathbfC
  tildemathbfCtextasciicircumtop.$$ The solution is based on factoring $bf mathbfM$
  into a product of simple and sparse matrices using squaring and spectral sparsification.
  For $mathbfM$ with $m$ non-zero entries, our algorithm takes work nearly-linear
  in $m$, and polylogarithmic depth on a parallel machine with $m$ processors. This
  gives the first sampling algorithm that only requires nearly linear work and $n$
  i.i.d. random univariate Gaussian samples to generate i.i.d. random samples for
  $n$-dimensional Gaussian random fields with SDDM precision matrices. For sampling
  this natural subclass of Gaussian random fields, it is optimal in the randomness
  and nearly optimal in the work and parallel complexity. In addition, our sampling
  algorithm can be directly extended to Gaussian random fields with SDD precision
  matrices.
tags:
- Computer Science - Data Structures and Algorithms
- Computer Science - Machine Learning
- Computer Science - Numerical Analysis
- Mathematics - Numerical Analysis
- Statistics - Computation
- Statistics - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/1410.5392
---
