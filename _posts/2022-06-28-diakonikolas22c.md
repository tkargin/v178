---
title: Learning a Single Neuron with Adversarial Label Noise via Gradient Descent
abstract: 'We study the fundamental problem of learning a single neuron, i.e., a  function
  of the form $\x \mapsto \sigma(\vec w \cdot \x)$ for monotone activations  $\sigma:\R
  \mapsto \R$, with respect to the $L_2^2$-loss in the presence of adversarial label
  noise.  Specifically, we are given labeled examples from a distribution $D$ on $(\x{},
  y) \in \R^d \times \R$ such that there exists $\vec w^\ast \in \R^d$ achieving $F(\vec
  w^\ast)  = \opt$, where $F(\vec w) = \E_{(\x{},y) \sim D}[(\sigma(\vec w\cdot \x)
  - y)^2]$. The goal of the learner is to output a hypothesis vector $\wt{\vec w}$
  such that $F(\wt{\vec w}) = C \, \opt+\eps$ with  high probability, where $C$ is
  a universal constant. As our main contribution, we give efficient constant-factor
  approximate learners  for a broad class of distributions (including log-concave
  distributions) and activation functions (including ReLUs and sigmoids). Concretely,
  for the class of isotropic log-concave distributions, we obtain the following important
  corollaries: \begin{itemize}[leftmargin=3pc, rightmargin = 1.5pc] \item For the
  logistic activation, i.e., $\sigma(t) = 1/(1+e^{-t})$, we obtain the first polynomial-time
  constant factor approximation, even under the Gaussian distribution. Moreover, our
  algorithm has sample complexity $\wt{O}(d/\eps)$, which is tight within  polylogarithmic
  factors.   \item For the ReLU activation, i.e., $\sigma(t) =  \max(0,t)$, we give
  an efficient algorithm with  sample complexity $\wt{O}(d \, \polylog(1/\eps))$.
  Prior to our work, the best known  constant-factor approximate learner had sample
  complexity $\Omega(d/\eps)$. \end{itemize}  In both settings, our algorithms are
  simple, performing gradient-descent on the (regularized) $L_2^2$-loss.  The correctness
  of our algorithms relies on novel structural results that we establish,  showing
  that (essentially all) stationary points of the underlying non-convex loss are approximately
  optimal.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: diakonikolas22c
month: 0
tex_title: Learning a Single Neuron with Adversarial Label Noise via Gradient Descent
firstpage: 4313
lastpage: 4361
page: 4313-4361
order: 4313
cycles: false
bibtex_author: Diakonikolas, Ilias and Kontonis, Vasilis and Tzamos, Christos and
  Zarifis, Nikos
author:
- given: Ilias
  family: Diakonikolas
- given: Vasilis
  family: Kontonis
- given: Christos
  family: Tzamos
- given: Nikos
  family: Zarifis
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
pdf: https://proceedings.mlr.press/v178/diakonikolas22c/diakonikolas22c.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
