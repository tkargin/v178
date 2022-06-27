---
title: Optimal Mean Estimation without a Variance
abstract: 'We study the problem of heavy-tailed mean estimation in settings where
  the variance of the data-generating distribution does not exist. Concretely, given
  a sample $\bm{X} = \{X_i\}_{i = 1}^n$ from a distribution $\mc{D}$ over $\mb{R}^d$
  with mean $\mu$ which satisfies the following \emph{weak-moment} assumption for
  some ${\alpha \in [0, 1]}$: \begin{equation*} \forall \norm{v} = 1: \mb{E}_{X \ts
  \mc{D}}[\abs{\inp{X - \mu}{v}}^{1 + \alpha}] \leq 1, \end{equation*} and given a
  target failure probability, $\delta$, our goal is to design an estimator which attains
  the smallest possible confidence interval as a function of $n,d,\delta$. For the
  specific case of $\alpha = 1$, foundational work of Lugosi and Mendelson exhibits
  an estimator achieving \emph{optimal} subgaussian confidence intervals, and subsequent
  work has led to computationally efficient versions of this estimator. Here, we study
  the case of general $\alpha$, and provide a precise characterization of the optimal
  achievable confidence interval by establishing the following information-theoretic
  lower bound: \begin{equation*} \Omega \lprp{\sqrt{\frac{d}{n}} + \lprp{\frac{d}{n}}^{\frac{\alpha}{(1
  + \alpha)}} + \lprp{\frac{\log 1 / \delta}{n}}^{\frac{\alpha}{(1 + \alpha)}}}. \end{equation*}
  and devising an estimator matching the aforementioned lower bound up to constants.
  Moreover, our estimator is computationally efficient.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: cherapanamjeri22a
month: 0
tex_title: Optimal Mean Estimation without a Variance
firstpage: 356
lastpage: 357
page: 356-357
order: 356
cycles: false
bibtex_author: Cherapanamjeri, Yeshwanth and Tripuraneni, Nilesh and Bartlett, Peter
  and Jordan, Michael
author:
- given: Yeshwanth
  family: Cherapanamjeri
- given: Nilesh
  family: Tripuraneni
- given: Peter
  family: Bartlett
- given: Michael
  family: Jordan
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
pdf: https://proceedings.mlr.press/v178/cherapanamjeri22a/cherapanamjeri22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
