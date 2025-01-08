---
title: Efficient Sampling for Gaussian Graphical Models via Spectral Sparsification
authors:
- Dehua Cheng
- Yu Cheng
- Yan Liu
- Richard Peng
- Shang-Hua Teng
date: '2015-06-01'
publishDate: '2025-01-08T22:16:47.060013Z'
publication_types:
- paper-conference
publication: '*Proceedings of The 28th Conference on Learning Theory*'
abstract: 'Motivated by a sampling problem basic to computational statistical inference,
  we develop a toolset based on spectral sparsification for a family of fundamental
  problems involving Gaussian sampling, matrix functionals, and reversible Markov
  chains. Drawing on the connection between Gaussian graphical models and the recent
  breakthroughs in spectral graph theory, we give the first nearly linear time algorithm
  for the following basic matrix problem: Given an ntimes n Laplacian matrix mathbfM
  and a constant -1 ≤p ≤1, provide efficient access to a sparse ntimes n linear operator
  tildemathbfC such that mathbfMp≈mathbfC~mathbfC~⊤,where≈denotesspectralsimilarity.Whenpissetto−1,thisgivesthefirstparallelsamplingalgorithmthatisessentiallyoptimalbothintotalworkandrandomnessforGaussianrandomfieldswithsymmetricdiagonallydominant(SDD)precisionmatrices.Itonlyrequiresemnearlylinearworkand2nemi.i.d.randomunivariateGaussiansamplestogenerateann−dimensionalemi.i.d.Gaussianrandomsampleinpolylogarithmicdepth.Thekeyingredientofourapproachisanintegrationofspectralsparsificationwithmultilevelmethod:OuralgorithmsarebasedonfactoringmathbfMpmathbfMp≈mathbfC~mathbfC~⊤,where≈denotesspectralsimilarity.Whenpissetto−1,thisgivesthefirstparallelsamplingalgorithmthatisessentiallyoptimalbothintotalworkandrandomnessforGaussianrandomfieldswithsymmetricdiagonallydominant(SDD)precisionmatrices.Itonlyrequiresemnearlylinearworkand2nemi.i.d.randomunivariateGaussiansamplestogenerateann−dimensionalemi.i.d.Gaussianrandomsampleinpolylogarithmicdepth.Thekeyingredientofourapproachisanintegrationofspectralsparsificationwithmultilevelmethod:OuralgorithmsarebasedonfactoringmathbfMpmathbfMtextasciicircump
  ≈tildemathbfC tildemathbfCtextasciicircum⊤, where ≈denotes spectral similarity.
  When p is set to -1, this gives the first parallel sampling algorithm that is essentially
  optimal both in total work and randomness for Gaussian random fields with symmetric
  diagonally dominant (SDD) precision matrices. It only requires em nearly linear
  work and 2n em i.i.d. random univariate Gaussian samples to generate an n-dimensional
  em i.i.d. Gaussian random sample in polylogarithmic depth. The key ingredient of
  our approach is an integration of spectral sparsification with multilevel method:
  Our algorithms are based on factoring mathbfMtextasciicircump into a product of
  well-conditioned matrices, then introducing powers and replacing dense matrices
  with sparse approximations. We give two sparsification methods for this approach
  that may be of independent interest. The first invokes Maclaurin series on the factors,
  while the second builds on our new nearly linear time spectral sparsification algorithm
  for random-walk matrix polynomials. We expect these algorithmic advances will also
  help to strengthen the connection between machine learning and spectral graph theory,
  two of the most active fields in understanding large data and networks.'
links:
- name: URL
  url: https://proceedings.mlr.press/v40/Cheng15.html
---
