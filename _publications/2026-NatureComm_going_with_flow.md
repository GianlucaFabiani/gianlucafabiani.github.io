---
title: "Going with the flow to solve for symmetry-driven PDE dynamics with physics-informed neural networks"
collection: preprints
permalink: /preprint/2026-NatureComm_going_with_flow
excerpt: 'We developed a PINN-based framework that factors out continuous symmetries in nonlinear PDEs, transforming them into high-index DAE systems to simultaneously compute invariant solutions and symmetry parameters like wave speeds or scaling rates.'
date: 2025-09-19
venue: 'Nature Communications volume 17'
paperurl: 'https://www.nature.com/articles/s41467-026-75936-3'
citation: 'Kavousanakis, M. E., Fabiani, G., Georgiou, A. S., Siettos, C., Kevrekidis, P. G., & Kevrekidis, I. G. (2026). Going with the flow to solve for symmetry-driven PDE dynamics with physics-informed neural networks. Nature communications.'
---

Abstract
=====
We address a computational framework that integrates symmetry reduction into Physics-Informed Neural Networks (PINNs) for analysing symmetry-driven dynamics in nonlinear partial differential equations (PDEs). Using an auxiliary network to learn time-dependent transformations, we render the symmetry-invariant solutions stationary or slowly varying in rescaled coordinates while simultaneously inferring the symmetry parameters (e.g., wave speed, scaling rates). This yields a modified evolution equation coupled with algebraic constraints on symmetry parameters, producing index-2 differential-algebraic equation (DAE) systems. Since conventional standard PDE/ODE solvers struggle or even fail with such high-index DAEs, we employ PINNs as an alternative approach that naturally unifies PDE residuals and algebraic constraints in a single loss function. This allows simultaneous inference of the invariant solutions and the transformation properties without large domains, mesh adaptivity, or front tracking. Beyond forward simulation, our framework further enables robust parameter inference from sparse, spatially offset data where vanilla PINNs fail. Our numerical demonstrations include, among others, the 2D porous medium, the generalised Korteweg-de Vries and Burgers PDE, showcasing our proposed approach as a powerful tool for the solution of both the forward and inverse problems for index-2 DAEs arising in nonlinear wave and scaling dynamics.
