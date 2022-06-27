---
title: Hardness of Maximum Likelihood Learning of DPPs
abstract: 'Determinantal Point Processes (DPPs) are a widely used probabilistic model
  for negatively correlated sets. DPPs are used in Machine Learning applications to
  select a diverse, yet representative subset of data. In these applications, the
  parameters of the DPP need to be fit to match the data; typically, we seek a set
  of parameters that maximize the likelihood of the data. The algorithms used for
  this task either optimize over a limited family of DPPs, or else use local improvement
  heuristics that do not provide theoretical guarantees of optimality. It is natural
  to ask if there exist efficient algorithms for finding a maximum likelihood DPP
  model for a given data set. In seminal work on DPPs in Machine Learning, Kulesza
  conjectured in his PhD Thesis (2012) that the problem is NP-complete.  In this work
  we prove Kulesza’s conjecture: we prove moreover, that even computing a $1-\frac{1}{\mathrm{poly}
  \log N}$-approximation to the maximum log-likelihood of a DPP on a set of $N$ items
  is NP-complete. At the same time, we also obtain the first polynomial-time algorithm
  obtaining a nontrivial worst-case approximation to the optimal likelihood: we present
  a polynomial-time $1/\log m$-approximation algorithm (for data sets of size $m$),
  which moreover obtains a $1-\frac{1}{\log N}$-approximation if all $N$ elements
  appear in a $O(1/N)$-fraction of the subsets. In terms of techniques, the hardness
  result reduces to solving a gap instance of a “vector coloring" problem on a hypergraph
  obtained from an adaptation of the constructions of Bogdanov, Obata and Trevisan
  (FOCS 2002), using the strong  expanders of  Alon and Capalbo (FOCS 2007).'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: grigorescu22a
month: 0
tex_title: Hardness of Maximum Likelihood Learning of DPPs
firstpage: 3800
lastpage: 3819
page: 3800-3819
order: 3800
cycles: false
bibtex_author: Grigorescu, Elena and Juba, Brendan and Wimmer, Karl and Xie, Ning
author:
- given: Elena
  family: Grigorescu
- given: Brendan
  family: Juba
- given: Karl
  family: Wimmer
- given: Ning
  family: Xie
date: 2022-06-28
address:
container-title: Proceedings of Thirty Fifth Conference on Learning Theory
volume: '178'
genre: inproceedings
issued:
  date-parts:
  - 2022
  - 6
  - 28
pdf: https://proceedings.mlr.press/v178/grigorescu22a/grigorescu22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
