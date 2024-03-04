---
title: "Slow invariant manifolds of singularly perturbed systems via physics-informed machine learning"
collection: preprints
permalink: /preprint/arxiv_2
excerpt: 'This preprint is about the solution of invariance equation associated with SIM via PINNs'
date: 2023-09-14
venue: 'Arxiv'
paperurl: 'https://arxiv.org/abs/2309.07946'
citation: 'Patsatzis, D. G., Fabiani, G., Russo, L., & Siettos, C. (2023). Slow invariant manifolds of singularly perturbed systems via physics-informed machine learning. arXiv preprint arXiv:2309.07946.'
---

We present a physics-informed machine-learning (PIML) approach for the approximation of slow invariant manifolds (SIMs) of singularly perturbed systems, providing functionals in an explicit form that facilitate the construction and numerical integration of reduced order models (ROMs). The proposed scheme solves a partial differential equation corresponding to the invariance equation (IE) within the Geometric Singular Perturbation Theory (GSPT) framework. For the solution of the IE, we used two neural network structures, namely feedforward neural networks (FNNs), and random projection neural networks (RPNNs), with symbolic differentiation for the computation of the gradients required for the learning process. The efficiency of our PIML method is assessed via three benchmark problems, namely the Michaelis-Menten, the target mediated drug disposition reaction mechanism, and the 3D Sel'kov model. We show that the proposed PIML scheme provides approximations, of equivalent or even higher accuracy, than those provided by other traditional GSPT-based methods, and importantly, for any practical purposes, it is not affected by the magnitude of the perturbation parameter. This is of particular importance, as there are many systems for which the gap between the fast and slow timescales is not that big, but still ROMs can be constructed. A comparison of the computational costs between symbolic, automatic and numerical approximation of the required derivatives in the learning process is also provided.
