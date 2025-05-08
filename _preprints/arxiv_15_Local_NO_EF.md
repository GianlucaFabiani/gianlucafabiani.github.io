---
title: "Enabling Local Neural Operators to perform Equation-Free System-Level Analysis"
collection: preprints
permalink: /preprint/arxiv_15_Local_NO_EF
excerpt: 'We propose a framework that integrates Neural Operators (NOs) with Krylov subspace iterative methods for efficient stability and bifurcation analysis of large-scale dynamical systems, extending NO applications beyond temporal predictions to system-level numerical tasks'
date: 2025-05-25
venue: 'Arxiv'
paperurl: 'https://arxiv.org/abs/2505.02308'
citation: 'Fabiani, G., Vandecasteele, H., Goswami, S., Siettos, C., & Kevrekidis, I. G. (2025). Enabling Local Neural Operators to perform Equation-Free System-Level Analysis. arXiv preprint arXiv:2505.02308.'
---

Abstract
=====
Neural Operators (NOs) provide a powerful framework for computations involving physical laws that can be modelled by (integro-) partial differential equations (PDEs), directly learning maps between infinite-dimensional function spaces that bypass both the explicit equation identification and their subsequent numerical solving. Still, NOs have so far primarily been employed to explore the dynamical behavior as surrogates of brute-force temporal simulations/predictions. Their potential for systematic rigorous numerical system-level tasks, such as fixed-point, stability, and bifurcation analysis - crucial for predicting irreversible transitions in real-world phenomena - remains largely unexplored. Toward this aim, inspired by the Equation-Free multiscale framework, we propose and implement a framework that integrates (local) NOs with advanced iterative numerical methods in the Krylov subspace, so as to perform efficient system-level stability and bifurcation analysis of large-scale dynamical systems. Beyond fixed point, stability, and bifurcation analysis enabled by local in time NOs, we also demonstrate the usefulness of local in space as well as in space-time ("patch") NOs in accelerating the computer-aided analysis of spatiotemporal dynamics. We illustrate our framework via three nonlinear PDE benchmarks: the 1D Allen-Cahn equation, which undergoes multiple concatenated pitchfork bifurcations; the Liouville-Bratu-Gelfand PDE, which features a saddle-node tipping point; and the FitzHugh-Nagumo (FHN) model, consisting of two coupled PDEs that exhibit both Hopf and saddle-node bifurcations.
