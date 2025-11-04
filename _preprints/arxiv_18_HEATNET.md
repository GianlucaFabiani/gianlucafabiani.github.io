---
title: "HEATNETs: Explainable Random Feature Neural Networks for High-Dimensional Parabolic PDEs"
collection: preprints
permalink: /preprint/arxiv_18_HEATNET
excerpt: 'HEATNET, a random feature neural network built from heat-kernel Green’s functions, provides an unbiased and scalable universal approximator for high-dimensional parabolic PDEs, achieving high accuracy up to 2,000 dimensions with relatively few features.'
date: 2025-11-02
venue: 'Arxiv'
paperurl: 'https://arxiv.org/abs/2511.00886'
citation: 'Georgiou K., Fabiani G., Siettos C., Yannacopoulos A.N. (2025). HEATNETs: Explainable Random Feature Neural Networks for High-Dimensional Parabolic PDEs. arXiv preprint arXiv:2511.00886.'
---

Abstract
=====
We deal with the solution of the forward problem for high-dimensional parabolic PDEs with random feature (projection) neural networks (RFNNs). We first prove that there exists a single-hidden layer neural network with randomized heat-kernels arising from the fundamental solution (Green's functions) of the heat operator, that we call HEATNET, that provides an unbiased universal approximator to the solution of parabolic PDEs in arbitrary (high) dimensions, with the rate of convergence being analogous to the O(N^(-1/2)), where N is the size of HEATNET. Thus, HEATNETs are explainable schemes, based on the analytical framework of parabolic PDEs, exploiting insights from physics-informed neural networks aided by numerical and functional analysis, and the structure of the corresponding solution operators. Importantly, we show how HEATNETs can be scaled up for the efficient numerical solution of arbitrary high-dimensional parabolic PDEs using suitable transformations and importance Monte Carlo sampling of the integral representation of the solution, in order to deal with the singularities of the heat kernel around the collocation points. We evaluate the performance of HEATNETs through benchmark linear parabolic problems up to 2,000 dimensions. We show that HEATNETs result in remarkable accuracy with the order of the approximation error ranging from 1E-05 to 1E-07 for problems up to 500 dimensions, and of the order of 1E-04 to 1E-03  for 1,000 to 2,000 dimensions, with a relatively low number (up to 15,000) of features.
