---
title: Spectral Sparsification of Random-Walk Matrix Polynomials
authors:
- Dehua Cheng
- Yu Cheng
- Yan Liu
- Richard Peng
- Shang-Hua Teng
date: '2015-02-01'
publishDate: '2025-01-08T22:16:47.083344Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.1502.03496
abstract: "We consider a fundamental algorithmic question in spectral graph theory:
  Compute a spectral sparsifier of random-walk matrix-polynomial $$L_alpha(G)=D-sum_r=1textasciicircumdalpha_rD(Dtextasciicircum-1A)textasciicircumr$$
  where $A$ is the adjacency matrix of a weighted, undirected graph, $D$ is the diagonal
  matrix of weighted degrees, and $alpha=(alpha_1...alpha_d)$ are nonnegative coefficients
  with $sum_r=1textasciicircumdalpha_r=1$. Recall that $Dtextasciicircum-1A$ is the
  transition matrix of random walks on the graph. The sparsification of $L_alpha(G)$
  appears to be algorithmically challenging as the matrix power $(Dtextasciicircum-1A)textasciicircumr$
  is defined by all paths of length $r$, whose precise calculation would be prohibitively
  expensive. In this paper, we develop the first nearly linear time algorithm for
  this sparsification problem: For any $G$ with $n$ vertices and $m$ edges, $d$ coefficients
  $alpha$, and $epsilon textgreater 0$, our algorithm runs in time $O(dtextasciicircum2mlogtextasciicircum2n/epsilontextasciicircum2)$
  to construct a Laplacian matrix $tildeL=D-tildeA$ with $O(nlog n/epsilontextasciicircum2)$
  non-zeros such that $tildeLapprox_epsilonL_alpha(G)$. Matrix polynomials arise in
  mathematical analysis of matrix functions as well as numerical solutions of matrix
  equations. Our work is particularly motivated by the algorithmic problems for speeding
  up the classic Newton's method in applications such as computing the inverse square-root
  of the precision matrix of a Gaussian random field, as well as computing the $q$th-root
  transition (for $qgeq1$) in a time-reversible Markov model. The key algorithmic
  step for both applications is the construction of a spectral sparsifier of a constant
  degree random-walk matrix-polynomials introduced by Newton's method. Our algorithm
  can also be used to build efficient data structures for effective resistances for
  multi-step time-reversible Markov models, and we anticipate that it could be useful
  for other tasks in network analysis."
tags:
- Computer Science - Data Structures and Algorithms
- Computer Science - Discrete Mathematics
- Computer Science - Machine Learning
- Computer Science - Social and Information Networks
- Statistics - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/1502.03496
---
