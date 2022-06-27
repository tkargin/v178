---
title: Near optimal efficient decoding from pooled data
abstract: Consider $n$ items, each of which is characterised by one of $d+1$ possible
  features in $\{0, \ldots, d\}$. We study the inference task of learning these types
  by queries on subsets, or pools, of the items that only reveal a form of coarsened
  information on the features - in our case, the sum of all the features in the pool.
  This is a realistic scenario in situations where one has memory or technical constraints
  in the data collection process, or where the data is subject to anonymisation. Related
  prominent problems are the quantitative group testing problem, of which it is a
  generalisation, as well as the compressed sensing problem, of which it is a special
  case.  In the present article, we are interested in the minimum number of queries
  needed to efficiently infer the features, in the setting where the feature vector
  is chosen uniformly while fixing the frequencies, and one of the features, say $0$,
  is dominant in the sense that the number $k = n^{\theta}, \theta \in (0,1)$, of
  non-zero features among the items is much smaller than $n$. It is known that in
  this case, all features can be recovered in exponential time using no more than
  $O(k)$ queries. However, so far, all \emph{efficient} inference algorithms required
  at least $\Omega(k\ln n)$ queries, and it was unknown whether this gap is artificial
  or of a fundamental nature. Here we show that indeed, the previous gap between the
  information-theoretic and computational bounds is not inherent to the problem by
  providing an efficient algorithm that succeeds with high probability and employs
  no more than $O(k)$ measurements. This also solves a prominent open question for
  the quantitative group testing problem.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hahn-klimroth22a
month: 0
tex_title: Near optimal efficient decoding from pooled data
firstpage: 3395
lastpage: 3409
page: 3395-3409
order: 3395
cycles: false
bibtex_author: Hahn-Klimroth, Max and M\"uller, Noela
author:
- given: Max
  family: Hahn-Klimroth
- given: Noela
  family: Müller
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
pdf: https://proceedings.mlr.press/v178/hahn-klimroth22a/hahn-klimroth22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
