---
title: Near-Optimal Statistical Query Hardness of Learning Halfspaces with Massart
  Noise
abstract: We study the problem of PAC learning halfspaces with Massart noise. Given
  labeled samples $(x, y)$ from a distribution $D$ on $\R^{d} \times \{ \pm 1\}$ such
  that the marginal $D_x$ on the examples is arbitrary and the label $y$ of example
  $x$ is generated from the target halfspace corrupted by a Massart adversary with
  flipping probability $\eta(x) \leq \eta \leq 1/2$, the goal is to compute a hypothesis
  with small misclassification error. The best known $\poly(d, 1/\eps)$-time algorithms
  for this problem achieve error of $\eta+\eps$, which can be far from the optimal
  bound of $\opt+\eps$, where $\opt = \E_{x \sim D_x} [\eta(x)]$. While it is known
  that achieving $\opt+o(1)$ error requires super-polynomial time in the Statistical
  Query model, a large gap remains between known upper and lower bounds. In this work,
  we essentially characterize the efficient learnability of Massart halfspaces in
  the Statistical Query (SQ) model. Specifically, we show that no efficient SQ algorithm
  for learning Massart halfspaces on $\R^d$ can achieve error better than $\Omega(\eta)$,
  even if $\opt  = 2^{-\log^{c} (d)}$, for any universal constant $c \in (0, 1)$.
  Furthermore, when the noise upper bound $\eta$ is close to $1/2$, our error lower
  bound becomes $\eta  - o_{\eta}(1)$, where the $o_{\eta}(1)$ term goes to $0$ when
  $\eta$ approaches $1/2$. Our results provide strong evidence that known learning
  algorithms for Massart halfspaces are nearly best possible.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: diakonikolas22b
month: 0
tex_title: Near-Optimal Statistical Query Hardness of Learning Halfspaces with Massart
  Noise
firstpage: 4258
lastpage: 4282
page: 4258-4282
order: 4258
cycles: false
bibtex_author: Diakonikolas, Ilias and Kane, Daniel
author:
- given: Ilias
  family: Diakonikolas
- given: Daniel
  family: Kane
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
pdf: https://proceedings.mlr.press/v178/diakonikolas22b/diakonikolas22b.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
