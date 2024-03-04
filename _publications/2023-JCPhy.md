---
title: "Discrete-time nonlinear feedback linearization via physics-informed machine learning"
collection: publications
permalink: /publication/2023-JCPhy
excerpt: 'This paper is about the one-step feedback linearization and control via PINNs'
date: 2023-01-01
venue: 'Journal of Computational Physics Volume 492, 1 November 2023, 112408'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S002199912300503X'
citation: 'Hector Vargas Alvarez, Gianluca Fabiani, Nikolaos Kazantzis, Constantinos Siettos, Ioannis G. Kevrekidis, Discrete-time nonlinear feedback linearization via physics-informed machine learning, Journal of Computational Physics, Volume 492, 2023, 112408, ISSN 0021-9991, https://doi.org/10.1016/j.jcp.2023.112408.'
---

Highlights
======
* We present a physics informed machine learning approach for the feedback linearization of nonlinear discrete-time systems.
* Our approach finds the nonlinear transformation law and guarantees stability of the closed loop dynamics in one step.
* We highlight the importance of using continuation techniques in the training procedure of PIML, when steep-gradients arise.
* We validate the methodology via a benchmark problem, which contains singularities in the domain of interest.

Abstract
======
We present a physics-informed machine learning (PIML) scheme for the feedback linearization of nonlinear discrete-time dynamical systems. The PIML finds the nonlinear transformation law, thus ensuring stability via pole placement, in one step. In order to facilitate convergence in the presence of steep gradients in the nonlinear transformation law, we address a greedy training procedure. We assess the performance of the proposed PIML approach via a benchmark nonlinear discrete map for which the feedback linearization transformation law can be derived analytically; the example is characterized by steep gradients, due to the presence of singularities, in the domain of interest. We show that the proposed PIML outperforms, in terms of numerical approximation accuracy, the traditional numerical implementation, which involves the construction –and the solution in terms of the coefficients of a power-series expansion–of a system of homological equations as well as the implementation of the PIML in the entire domain, thus highlighting the importance of continuation techniques in the training procedure of PIML schemes.
