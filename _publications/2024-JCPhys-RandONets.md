---
title: "RandONets: Shallow-Networks with Random Projections for learning linear and nonlinear operators"
collection: publications
permalink: /publication/2024-JCPhy-RandONets
excerpt: 'This paper propose a novel architecture, RandONets, for learning generic Operators. It leverages Random Projections and Nonlinear Random Features, as well as tailor-made numerical analysis method for improving significantly efficiency and accuracy. We demonstrate that RandONets outperforms DeepONets by 10 order of magnitudes. Also, we theoretically prove and extend the theorem of Chen and Chen (1995) to such randomized architectures.'
date: 2024-09-10
venue: 'Journal of Computational Physics'
paperurl: 'https://doi.org/10.1016/j.jcp.2024.113433'
citation: 'Fabiani, G., Kevrekidis, I. G., Siettos, C., & Yannacopoulos, A. N. RandONets: Shallow-Networks with Random Projections for learning linear and nonlinear operators. J Comp Phys (2025)'
---

Graphical Abstract
=====
<img src="https://raw.githubusercontent.com/GianlucaFabiani/gianlucafabiani.github.io/master/images/Graphical_Abstract_RandOnet_details_big_colored_page-0001.jpg" width="1000" />

Abstract
=====
Deep neural networks have been extensively used for the solution of both the forward and the inverse problem for dynamical systems. However, their implementation necessitates optimizing a high-dimensional space of parameters and hyperparameters. This fact, along with the requirement of substantial computational resources, pose a barrier to achieving high numerical accuracy, but also interpretability.
Here, to address the above challenges, we present Random Projection-based Operator Networks (RandONets): shallow networks with random projections and tailor-made numerical analysis algorithms that learn linear and nonlinear operators. The implementation of RandONets involves: (a) incorporating random bases, thus enabling the use of shallow neural networks with a single hidden layer, where the only unknowns are the output weights of the network's weighted inner product; this reduces dramatically the dimensionality of the parameter space; and, based on this, (b) using tailor-made numerical analysis techniques to solve a linear ill-posed problem with regularization (e.g., Tikhonov regularization and preconditioned QR decomposition). 
In addition, we prove the universal approximation accuracy of RandONets for approximating linear and nonlinear operators. Furthermore, we demonstrate their efficiency in approximating linear and nonlinear evolution operators (right-hand-sides (RHS)) with a focus on PDEs. We also note that due to their simplicity, RandONets provide a one-step transformation of the input space, facilitating the interpretability.
We show, that for this particular task, RandONets outperform both in terms of numerical approximation accuracy and computational cost, by several orders of magnitudes the ``vanilla" DeepONets. Hence, we believe that our method will trigger further developments in the field of scientific machine learning, for the development of new `'light'' machine learning schemes that will provide high accuracy while reducing dramatically the computational costs. A software/ toolbox in Matlab for RandONets with demos is also provided and available on GitHub at
[https://github.com/GianlucaFabiani/RandONet](https://github.com/GianlucaFabiani/RandONets).
