---
title: "On the accuracy of interpolation based on single-layer artificial neural networks with a focus on defeating the Runge phenomenon"
collection: publications
permalink: /publication/2024-SoftComputing
excerpt: 'This paper is about the interpolation of functions on the interpolation accuracy of Random featured Neural Networks, with particular focus on the possibility to use random grids, even for functions presenting the Runge-Phenomenon.'
date: 2024-07-29
venue: 'Soft Computing'
paperurl: 'https://doi.org/10.1007/s00500-024-09918-2'
citation: 'Auricchio, F., Belardo, M. R., Calabrò, F., Fabiani, G. & Pascaner, A. F. (2024). On the accuracy of interpolation based on single-layer artificial neural networks. Soft Computing'
---

Abstract
=====
Artificial Neural Networks (ANNs) are a tool in approximation theory widely used to solve interpolation problems. In fact, ANNs can be
assimilated to functions since they take an input and return an output. The structure of the specifically adopted network determines the
underlying approximation space, while the form of the function is selected by fixing the parameters of the network. In the present paper,
we consider one-hidden layer ANNs with a feedforward architecture,
also referred to as shallow or two-layer networks, so that the structure
is determined by the number and types of neurons. The determination
of the parameters that define the function, called training, is done via
the resolution of the approximation problem, so by imposing the interpolation through a set of specific nodes. We present the case where the
parameters are trained using a procedure that is referred to as Extreme
Learning Machine (ELM) that leads to a linear interpolation problem.
In such hypotheses, the existence of an ANN interpolating function is
guaranteed.
Given that the ANN is interpolating, the error incurred occurs outside
the sampling interpolation nodes provided by the user. In this study
various choices of nodes are analyzed: equispaced, Chebychev, and randomly selected ones. Then, the focus is on regular target functions, for
which it is known that interpolation can lead to spurious oscillations,
a phenomenon that in the ANN literature is referred to as overfitting. We obtain good accuracy of the ANN interpolating function in
all tested cases using these different types of interpolating nodes and
different types of neurons. The following study is conducted starting
from the well-known bell-shaped Runge example, which makes it clear
that the construction of a global interpolating polynomial is accurate
only if trained on suitably chosen nodes, ad example the Chebychev
ones. In order to evaluate the behavior when the number of interpolation nodes increases, we increase the number of neurons in our network and compare it with the interpolating polynomial. We test using
Runge’s function and other well-known examples with different regularities. As expected, the accuracy of the approximation with a global
polynomial increases only if the Chebychev nodes are considered. Instead, the error for the ANN interpolating function always decays, and
in most cases we observe that the convergence follows what is observed
in the polynomial case on Chebychev nodes, despite the set of nodes
used for training. Then we can conclude that the use of such an ANN
defeats the Runge phenomenon.
Our results show the power of ANNs to achieve excellent approximations when interpolating regular functions also starting from uniform
and random nodes, particularly for Runge’s function.
