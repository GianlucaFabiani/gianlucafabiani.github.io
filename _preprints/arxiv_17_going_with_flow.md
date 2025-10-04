---
title: "Going with the Flow: Solving for Symmetry-Driven PDE dynamics with Physics-informed Neural Networks"
collection: preprints
permalink: /preprint/arxiv_17_going_with_flow
excerpt: 'We developed a PINN-based framework that factors out continuous symmetries in nonlinear PDEs, transforming them into high-index DAE systems to simultaneously compute invariant solutions and symmetry parameters like wave speeds or scaling rates.'
date: 2025-09-19
venue: 'Arxiv'
paperurl: 'https://arxiv.org/abs/2509.15963'
citation: 'Kavousanakis, M., Fabiani, G., Georgiou, A., Siettos, C., Kevrekidis, P., & Kevrekidis, I. (2025). Going with the Flow: Solving for Symmetry-Driven PDE dynamics with Physics-informed Neural Networks. arXiv preprint arXiv:2509.15963.'
---

Abstract
=====
In the past, we have presented a systematic computational framework for analyzing self-similar and traveling wave dynamics in nonlinear partial differential equations (PDEs) by dynamically factoring out continuous symmetries such as translation and scaling. This is achieved through the use of time-dependent transformations -- what can be viewed as dynamic pinning conditions -- that render the symmetry-invariant solution stationary or slowly varying in rescaled coordinates. The transformation process yields a modified evolution equation coupled with algebraic constraints on the symmetry parameters, resulting in index-2 differential-algebraic equation (DAE) systems. The framework accommodates both first-kind and second-kind self-similarity, and directly recovers the self-similarity exponents or wave speeds as part of the solution, upon considering steady-state solutions in the rescaled coordinate frame. To solve the resulting high-index DAE systems, we employ Physics-Informed Neural Networks (PINNs), which naturally integrate PDE residuals and algebraic constraints into a unified loss function. This allows simultaneous inference of both the invariant solution and the transformation properties (such as the speed or the scaling rate without the need for large computational domains, mesh adaptivity, or front tracking. We demonstrate the effectiveness of the method on four canonical problems: (i) the Nagumo equation exhibiting traveling waves, (ii) the diffusion equation (1D and 2D) with first-kind self-similarity, (iii) the 2D axisymmetric porous medium equation showcasing second-kind self-similarity, and (iv) the Burgers equation, which involves both translational and scaling invariance. The results demonstrate the capability of PINNs to effectively solve these complex PDE-DAE systems, providing a promising tool for studying nonlinear wave and scaling phenomena.
