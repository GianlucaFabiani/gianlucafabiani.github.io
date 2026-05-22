---
title: "Enabling Local Neural Operators to perform Equation-Free System-Level Analysis"
collection: publications
permalink: /publication/2026-NatureMachInt
excerpt: 'We propose a framework that integrates Neural Operators (NOs) with Krylov subspace iterative methods for efficient stability and bifurcation analysis of large-scale dynamical systems, extending NO applications beyond temporal predictions to system-level numerical tasks'
date: 2025-06-01
venue: 'Nature Machine Intelligence'
paperurl: 'https://arxiv.org/abs/2505.02308'
citation: 'Fabiani, G., Vandecasteele, H., Goswami, S., Siettos, C., & Kevrekidis, I. G., Enabling Local Neural Operators to perform Equation-Free System-Level Analysis, Nat Mach Intell 8, 2026'
---

Abstract
=====
Neural Operators (NOs) offer a powerful computational framework to learn complex spatiotemporal dynamics as mappings between infinite-dimensional function spaces. Still, NOs have primarily been used as surrogates for brute-force temporal simulations and predictions. Their potential for systematic, system-level numerical analysis, such as fixed-point, stability, and bifurcation analysis– crucial for predicting irreversible transitions in real-world phenomena– remains largely unexplored. Motivated by the Equation-Free (EF) approach, we develop a framework that integrates (local) NOs with iterative numerical analysis methods in the Krylov subspace. This approach expands their potential beyond simulation to efficiently analyze large-scale dynamical systems and tackle fundamental challenges in computer-assisted modeling and numerical analysis of complex systems. Furthermore, we demonstrate the utility of learning local in space-time NOs, which, combined with multiscale EF schemes such as projective integration, Gap-Tooth, and Patch Dynamics, accelerate system-level computations, improve the conditioning of Krylov solvers, and reduce memory requirements, enabling efficient multiscale analysis of complex spatiotemporal dynamics.
We illustrate our framework via three nonlinear PDE benchmarks: the 1D Allen-Cahn equation, which undergoes multiple concatenated pitchfork bifurcations; the Liouville-Bratu-Gelfand PDE, which features a saddle-node tipping point; and the FitzHugh-Nagumo model, consisting of two coupled PDEs that exhibit both Hopf and saddle-node bifurcations.
