---
title: "Equation-Free Coarse Control of Distributed Parameter Systems via Local Neural Operators"
collection: preprints
permalink: /preprint/arxiv_16_control_NO
excerpt: 'We propose a framework, using data-driven local neural operators within Krylov subspace methods, to enable efficient model reduction and feedback control of high-dimensional systems without explicit coarse equations.'
date: 2025-09-28
venue: 'Arxiv'
paperurl: 'https://www.arxiv.org/abs/2509.23975'
citation: 'Fabiani, G., Siettos, C., & Kevrekidis, I. G. (2025). Equation-Free Coarse Control of Distributed Parameter Systems via Local Neural Operators. arXiv preprint arXiv:2509.23975.'
---

Abstract
=====
The control of high-dimensional distributed parameter systems (DPS) remains a challenge when explicit coarse-grained equations are unavailable. Classical equation-free (EF) approaches rely on fine-scale simulators treated as black-box timesteppers. However, repeated simulations for steady-state computation, linearization, and control design are often computationally prohibitive, or the microscopic timestepper may not even be available, leaving us with data as the only resource. We propose a data-driven alternative that uses local neural operators, trained on spatiotemporal microscopic/mesoscopic data, to obtain efficient short-time solution operators. These surrogates are employed within Krylov subspace methods to compute coarse steady and unsteady-states, while also providing Jacobian information in a matrix-free manner. Krylov-Arnoldi iterations then approximate the dominant eigenspectrum, yielding reduced models that capture the open-loop slow dynamics without explicit Jacobian assembly. Both discrete-time Linear Quadratic Regulator (dLQR) and pole-placement (PP) controllers are based on this reduced system and lifted back to the full nonlinear dynamics, thereby closing the feedback loop.
