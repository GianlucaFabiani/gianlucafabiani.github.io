---
title: "Parsimonious Physics-Informed Random Projection Neural Networks (PIRPNN) for solving Forward and Inverse Problems"
collection: talks
type: "Talk"
permalink: /talks/2023-Crunch
venue: "Crunch Seminars"
date: 2023-06-23
location: "Brown, Division of Applied Mathematics"
---

Youtube video
=====
here the following video of the talk (presentation #2)
[https://www.youtube.com/watch?v=eEiN3bN1TxE&t=134s](https://www.youtube.com/watch?v=eEiN3bN1TxE&t=134s)


Abstract
====
In this talk, I will present a physics-informed random projection neural network (PIRPNNs)
scheme for the solution of both the forward (for stiff ODEs, index-1 DAEs and steady-state
problems of PDEs) and inverse problem for differential equations. The convergence properties
of the scheme are guaranteed by the universal approximation theorems of linear (see e.g. the
Johnson-Lindestrauss Lemma) and nonlinear random projections. Within this framework, the
training of PIRPNNs simplifies to a regularization problem for the solution of a system of
nonlinear algebraic equations with respect only to the external weights. To deal with stiff ODEs
and sharp gradients, we propose an adaptive step-size scheme, and address a continuation
method for providing good initial guesses of the weights of the networks to facilitate
convergence. Furthermore, we propose an approach to parsimoniously choose the intervals of
the random hyperparameters of the activation functions. Remarkably, we show for the first
time, that a machine learning scheme may be comparable, and in several cases better, in terms
of both numerical accuracy, and importantly, computational cost when compared to traditional
stiff solvers of the Matlab ODE suite and also against well-established finite differences and
Galerkin Finite Elements for the solution of steady state problems of nonlinear PDEs. I will show
the performance of the proposed scheme via eight benchmark problems of stiff ODEs and
index-1 DAEs, and three steady problems of PDEs, namely the 1D and 2D Bratu problem and the
1D viscous Burgers PDE. For the Inverse problem, we used RPNNs to learn the right-hand-side
of the effective coarse-scale PDEs from high-dimensional spatio-temporal data produced by
Lattice-Boltzmann simulations of the 1D FitzHugh-Nagumo model and to reconstruct the
corresponding bifurcation diagram. In concluding, we show that the proposed PIRPNN schemes
achieve a high numerical accuracy being much less costly than deep learning for the particular
family of problems in scientific machine learning, thus highlighting the need for developing /
bridging (beyond) state-of-the-art numerical analysis techniques with machine learning
algorithms.

