---
title: "Stability and Bifurcation Analysis of Nonlinear PDEs via Random Projection-based PINNs: A Krylov-Arnoldi Approach"
collection: preprints
permalink: /preprint/arxiv_18_StabArnoldiRPNN
excerpt: 'We present a matrix-free Krylov–Arnoldi framework within physics-informed random projection neural networks that enables reliable computation of the leading eigenvalues governing linear stability and bifurcations of nonlinear PDEs despite the inherent rank deficiency of the collocation discretization.'
date: 2026-03-23
venue: 'Arxiv'
paperurl: 'https://arxiv.org/abs/2603.21568'
citation: 'Fabiani G., Kavousanakis M.E., Siettos C., Kevrekidis I.G. (2026). Stability and Bifurcation Analysis of Nonlinear PDEs via Random Projection-based PINNs: A Krylov-Arnoldi Approach. arXiv preprint arXiv:2603.21568.'
---

Abstract
=====
We address a numerical framework for the stability and bifurcation analysis of nonlinear partial differential equations (PDEs) in which the solution is sought in the function space spanned by physics-informed random projection neural networks (PI-RPNNs), and discretized via a collocation approach. These are single-hidden-layer networks with randomly sampled and fixed a priori hidden-layer weights; only the linear output layer weights are optimized, reducing training to a single least-squares solve. This linear output structure enables the direct and explicit formulation of the eigenvalue problem governing the linear stability of stationary solutions. This takes a generalized eigenvalue form, which naturally separates the physical domain interior dynamics from the algebraic constraints imposed by boundary conditions, at no additional training cost and without requiring additional PDE solves. However, the random projection collocation matrix is inherently numerically rank-deficient, rendering naive eigenvalue computation unreliable and contaminating the true eigenvalue spectrum with spurious near-zero modes. To overcome this limitation, we introduce a matrix-free shift-invert Krylov-Arnoldi method that operates directly in weight space, avoiding explicit inversion of the numerically rank-deficient collocation matrix and enabling the reliable computation of several leading eigenpairs of the physical Jacobian - the discretized Frechet derivative of the PDE operator with respect to the solution field, whose eigenvalue spectrum determines linear stability. We further prove that the PI-RPNN-based generalized eigenvalue problem is almost surely regular, guaranteeing solvability with standard eigensolvers, and that the singular values of the random projection collocation matrix decay exponentially for analytic activation functions.
