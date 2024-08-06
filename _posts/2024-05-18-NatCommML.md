---
title: 'Machine Learns the Secrets of Tipping Points'
date: 2024-05-18
permalink: /posts/2024/05/NatCommML.md/
tags:
  - Machine Learning
  - Numerical Analysis
  - Micro-macro bridging
  - Tipping Points
  - Rare event analysis
  - Complex Systems
  - Partial Differential Equations (PDEs)
  - Stochastic Differential Equations (SDEs)
  - Convolutional Neural Networks
  - Euler-Maruyama SDE Networks
---

Ever wondered what triggers sudden, dramatic shifts in complex systems? Our research takes a thrilling Machine Learning adventure to unravel the mysteries of "tipping points" - those critical junctures where small changes lead to big, often irreversible consequences.
Read the paper: [Nature Communications 15, 4117](https://doi.org/10.1038/s41467-024-48024-7). Full blog post at [Springer Nature Research Communities](https://communities.springernature.com/posts/ai-learns-the-secrets-of-tipping-points)

Intro
=====
Imagine a financial market teetering on the brink of a bubble or crises,  an - apparently drowsy- disease outbreak escalating on a social network or a seemingly stable climate tipping into a cascade of extremes: scorching heat, vanishing water, and rising seas. These scenarios highlight the challenges of studying tipping points in complex systems. Traditional methods, like high-fidelity agent-based models (ABMs), offer valuable insights, but their computational demands can be a real roadblock.

This is where our research steps in. We propose a groundbreaking framework that harnesses the power of Machine Learning to analyze tipping points in large-scale ABMs. Here's the magic: we extract low-dimensional "hidden patterns" from the data, allowing us to develop efficient models that capture the key dynamics near tipping points.


The Big Picture: Our approach offers several benefits
=====
- Reduced Complexity: By focusing on the core dynamics, we significantly decrease computational costs compared to traditional methods.
- Unveiling Secrets: We identify the underlying mechanisms driving tipping points, providing valuable insights for prevention or mitigation.
- Quantifying the Unlikely: We calculate the probability of rare, catastrophic events triggered near tipping points.

Description
======
In the recent publication in [Nature Communications (Fabiani et al. 2024)](https://doi.org/10.1038/s41467-024-48024-7), the Professor Kevrekidis group  in collaboration with the Professor Siettos group, implement an efficient machine learning framework bridging numerical analysis, neural networks, Gaussian processes and the equation-free framework.
Our work paves the way for estimating probabilities of rare events in complex systems, and detect tipping points/catastrophic shifts.

The developed code is available in a [Gitlab repository](https://gitlab.com/nicolasevangelou/agent_based).

FIND THE FULL CONTENT HERE
====
Read the paper: [Nature Communications 15, 4117](https://doi.org/10.1038/s41467-024-48024-7). Full blog post at [Springer Nature Research Communities](https://communities.springernature.com/posts/ai-learns-the-secrets-of-tipping-points)

