---
title: "Extreme learning machine collocation for the numerical solution of elliptic PDEs with sharp gradients"
collection: publications
permalink: /publication/2021-CMAME
excerpt: 'This paper is about the solution of linear stationary PDEs with Random Projection Neural Networks'
date: 2021-01-01
venue: 'Computer Methods in Applied Mechanics and Engineering 387, 114188'
paperurl: 'https://doi.org/10.1016/j.cma.2021.114188'
citation: 'Calabrò, F., Fabiani, G., & Siettos, C. (2021). Extreme learning machine collocation for the numerical solution of elliptic PDEs with sharp gradients. Computer Methods in Applied Mechanics and Engineering, 387, 114188.'
---

Highlights:
=====
* Collocation with Extreme Machine Learning networks for elliptic pdes is considered.
* The proposed approach does not require the training of the network.
* The underlying space is constructed by fixing the internal weights and biases.
* The proposed method is tested on benchmark problems, also with steep gradients.
* The proposed method is efficient and significantly reduces the computational costs.


Abstract
======
We address a new numerical method based on machine learning and in particular based on the concept of the so-called Extreme Learning Machines, to approximate the solution of linear elliptic partial differential equations with collocation. We show that a feedforward neural network with a single hidden layer and sigmoidal transfer functions and fixed, random, internal weights and biases can be used to compute accurately enough a collocated solution for such problems. We discuss how one can set the range of values for both the weights between the input and hidden layer and the biases of the hidden layer in order to obtain a good underlying approximating subspace, and we explore the required number of collocation points. We demonstrate the efficiency of the proposed method with several one-dimensional diffusion–advection–reaction benchmark problems that exhibit steep behaviors, such as boundary layers. We point out that there is no need of iterative training of the network, as the proposed numerical approach results to a linear problem that can be easily solved using least-squares and regularization. Numerical results show that the proposed machine learning method achieves a good numerical accuracy, outperforming central Finite Differences, thus bypassing the time-consuming training phase of other machine learning approaches.
