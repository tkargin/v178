---
title: Chasing Convex Bodies and Functions with Black-Box Advice
abstract: We consider the problem of convex function chasing with black-box advice,
  where an online decision-maker aims to minimize the total cost of making and switching
  between decisions in a normed vector space, aided by black-box advice such as the
  decisions of a machine-learned algorithm. The decision-maker seeks cost comparable
  to the advice when it performs well, known as \emph{consistency}, while also ensuring
  worst-case \emph{robustness} even when the advice is adversarial. We first consider
  the common paradigm of algorithms that switch between the decisions of the advice
  and a competitive algorithm, showing that no algorithm in this class can improve
  upon 3-consistency while staying robust. We then propose two novel algorithms that
  bypass this limitation by exploiting the problem’s convexity. The first, $\textsc{Interp}$,
  achieves $(\sqrt{2}+\epsilon)$-consistency and $\mathcal{O}(\frac{C}{\epsilon^2})$-robustness
  for any $\epsilon > 0$, where $C$ is the competitive ratio of an algorithm for convex
  function chasing or a subclass thereof. The second, $\textsc{BdInterp}$, achieves
  $(1+\epsilon)$-consistency and $\mathcal{O}(\frac{CD}{\epsilon})$-robustness when
  the problem has bounded diameter $D$. Further, we show that $\textsc{BdInterp}$
  achieves near-optimal consistency-robustness trade-off for the special case where
  cost functions are $\alpha$-polyhedral.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: christianson22a
month: 0
tex_title: Chasing Convex Bodies and Functions with Black-Box Advice
firstpage: 867
lastpage: 908
page: 867-908
order: 867
cycles: false
bibtex_author: Christianson, Nicolas and Handina, Tinashe and Wierman, Adam
author:
- given: Nicolas
  family: Christianson
- given: Tinashe
  family: Handina
- given: Adam
  family: Wierman
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
pdf: https://proceedings.mlr.press/v178/christianson22a/christianson22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
