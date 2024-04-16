---
title: "Parsimonious physics-informed random projection neural networks for initial value problems of ODEs and index-1 DAEs"
collection: publications
permalink: /publication/2023-Chaos
excerpt: 'This paper was awarded with an Editor's Pick badge. It is about the solution of stiff system of ODEs and DAEs (including PDEs) via time-adaptive Random Projection Neural Networks.'
date: 2023-04-13
venue: 'Chaos: An Interdisciplinary Journal of Nonlinear Science, 33(4)'
paperurl: 'https://pubs.aip.org/aip/cha/article-abstract/33/4/043128/2878586/Parsimonious-physics-informed-random-projection?redirectedFrom=fulltext'
citation: 'Fabiani, G., Galaris, E., Russo, L., & Siettos, C. (2023). Parsimonious physics-informed random projection neural networks for initial value problems of ODEs and index-1 DAEs. Chaos: An Interdisciplinary Journal of Nonlinear Science, 33(4).'
---


Editor's Pick
======

Highlights
=====
We address a machine-learning-based method for the nu-merical solution of stiff ODEs and index-1 DAEs, thus exploiting the universal approximation properties of random projections with Gaussian Kernels. This is the first time shown, that a machine learning scheme may be comparable, and in several cases better, in terms of both numerical accuracy, and importantly, computational cost when compared to established/traditional stiff solvers such asthe ode23t and ode15s of the Matlab ODE suite, and also deep-learning PINNs as implemented in the DeepXDE library. Thus, we believe that this work may trigger further developments in the field of scientific machine learning for the numerical solution of differential equations. 

Abstract
======
We present a numerical method based on random projections with Gaussian kernels and physics-informed neural networks for the numerical solution of initial value problems (IVPs) of nonlinear stiff ordinary differential equations (ODEs) and index-1 differential algebraic equations (DAEs), which may also arise from spatial discretization of partial differential equations (PDEs). The internal weights are fixed to ones while the unknown weights between the hidden and output layer are computed with Newton’s iterations using the Moore–Penrose pseudo-inverse for low to medium scale and sparse QR decomposition with L 2 regularization for medium- to large-scale systems. Building on previous works on random projections, we also prove its approximation accuracy. To deal with stiffness and sharp gradients, we propose an adaptive step-size scheme and address a continuation method for providing good initial guesses for Newton iterations. The “optimal” bounds of the uniform distribution from which the values of the shape parameters of the Gaussian kernels are sampled and the number of basis functions are “parsimoniously” chosen based on bias-variance trade-off decomposition. To assess the performance of the scheme in terms of both numerical approximation accuracy and computational cost, we used eight benchmark problems (three index-1 DAEs problems, and five stiff ODEs problems including the Hindmarsh–Rose neuronal model of chaotic dynamics and the Allen–Cahn phase-field PDE). The efficiency of the scheme was compared against two stiff ODEs/DAEs solvers, namely, ode15s and ode23t solvers of the MATLAB ODE suite as well as against deep learning as implemented in the DeepXDE library for scientific machine learning and physics-informed learning for the solution of the Lotka–Volterra ODEs included in the demos of the library. A software/toolbox in Matlab (that we call RanDiffNet) with demos is also provided.
