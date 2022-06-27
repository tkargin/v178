---
title: Community Recovery in the Degree-Heterogeneous Stochastic Block Model
abstract: We consider the problem of recovering communities in a random directed graph
  with planted communities. To model real-world directed graphs such as the Twitter
  or Instagram graphs that exhibit very heterogeneous degree sequences, we introduce
  the Degree-Heterogeneous Stochastic Block Model (DHSBM), a generalization of the
  classic Stochastic Block Model (SBM), where the vertex set is partitioned into communities
  and each vertex $u$ has two (unknown) associated probabilities, $p_u$ and $q_u$,
  $p_u  > q_u$. An arc from $u$ to $v$ is generated with probability $p_u$ if $u$
  and $v$ are in the same community and with probability $q_u$ otherwise.  Given a
  graph generated from this model, the goal is to retrieve the communities. The DHSBM
  allows to generate graphs with planted communities while allowing heterogeneous
  degree distributions, a quite important feature of real-world networks.  In the
  case where there are two communities, we present an iterative greedy linear-time
  algorithm that recovers them whenever $\min_u \frac{p_u - q_u}{\sqrt{p_u}} = \Omega(\sqrt{\log
  (n)/n})$. We also show that, up to a constant, this condition is necessary. Our
  results also extend to the standard (undirected) SBM, where $p_u = p$ and $q_u=
  q$ for all nodes $u$. Our algorithm presents the first linear-time algorithm that
  recovers exactly the communities at the asymptotic information-theoretic threshold,
  improving over previous near-linear time spectral approaches.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: cohen-addad22a
month: 0
tex_title: Community Recovery in the Degree-Heterogeneous Stochastic Block Model
firstpage: 1662
lastpage: 1692
page: 1662-1692
order: 1662
cycles: false
bibtex_author: Cohen-Addad, Vincent and Mallmann-Trenn, Frederik and Saulpic, David
author:
- given: Vincent
  family: Cohen-Addad
- given: Frederik
  family: Mallmann-Trenn
- given: David
  family: Saulpic
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
pdf: https://proceedings.mlr.press/v178/cohen-addad22a/cohen-addad22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
