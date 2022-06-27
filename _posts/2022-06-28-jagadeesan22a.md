---
title: Inductive Bias of Multi-Channel Linear Convolutional Networks with Bounded
  Weight Norm
abstract: 'We provide a function space characterization of the inductive bias resulting
  from minimizing the $\ell_2$ norm of the weights in multi-channel convolutional
  neural networks with linear activations and empirically test our resulting hypothesis
  on ReLU  networks trained using gradient descent. We define an \emph{induced regularizer}
  in the function space as the minimum $\ell_2$ norm of weights of a network required
  to realize a function.  For two layer linear convolutional networks with $C$ output
  channels and kernel size $K$, we show the following: (a) If the inputs to the network
  are single channeled, the induced regularizer for any $K$ is \emph{independent}
  of the number of output channels $C$. Furthermore, we derive the regularizer is
  a norm given by a semidefinite program (SDP). (b) In contrast, for multi-channel
  inputs, multiple output channels can be necessary to merely realize all matrix-valued
  linear functions and thus the inductive bias \emph{does} depend on $C$. However,
  for sufficiently large $C$, the induced regularizer is again given by an SDP that
  is independent of $C$. In particular, the induced regularizer for  $K=1$ and $K=D$
  (input dimension) are given in closed form as the nuclear norm and the $\ell_{2,1}$
  group-sparse norm, respectively, of the Fourier coefficients of the linear predictor.
  We investigate the broader applicability of our theoretical results to implicit
  regularization from gradient descent on linear and ReLU networks through experiments
  on MNIST and CIFAR-10 datasets.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: jagadeesan22a
month: 0
tex_title: Inductive Bias of Multi-Channel Linear Convolutional Networks with Bounded
  Weight Norm
firstpage: 2276
lastpage: 2325
page: 2276-2325
order: 2276
cycles: false
bibtex_author: Jagadeesan, Meena and Razenshteyn, Ilya and Gunasekar, Suriya
author:
- given: Meena
  family: Jagadeesan
- given: Ilya
  family: Razenshteyn
- given: Suriya
  family: Gunasekar
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
pdf: https://proceedings.mlr.press/v178/jagadeesan22a/jagadeesan22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
