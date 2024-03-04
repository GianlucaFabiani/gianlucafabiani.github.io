---
title: "Numerical Solution of Stiff ODEs with Physics-Informed RPNNs"
collection: preprints
permalink: /preprint/arxiv_1
excerpt: 'This preprint contains preliminary results about the solution of stiff ODEs with Random Projection Neural Networks'
date: 2021-11-24
venue: 'Arxiv'
paperurl: 'http://arxiv.org/pdf/2108.01584.pdf'
citation: 'Galaris, E., Fabiani, G., Calabrò, F., di Serafino, D., & Siettos, C. (2021). Numerical Solution of Stiff ODEs with Physics-Informed RPNNs. arXiv preprint arXiv:2108.01584.'
---

Abstract
======
We propose a numerical method based on physics-informed Random Projection Neural Networks for the solution of Initial Value Problems (IVPs) of Ordinary Differential Equations (ODEs) with a focus on stiff problems. We address an Extreme Learning Machine with a single hidden layer with radial basis functions having as widths uniformly distributed random variables, while the values of the weights between the input and the hidden layer are set equal to one. The numerical solution of the IVPs is obtained by constructing a system of nonlinear algebraic equations, which is solved with respect to the output weights by the Gauss-Newton method, using a simple adaptive scheme for adjusting the time interval of integration. To assess its performance, we apply the proposed method for the solution of four benchmark stiff IVPs, namely the Prothero-Robinson, van der Pol, ROBER and HIRES problems. Our method is compared with an adaptive Runge-Kutta method based on the Dormand-Prince pair, and a variable-step variable-order multistep solver based on numerical differentiation formulas, as implemented in the ode45 and ode15s MATLAB functions, respectively. We show that the proposed scheme yields good approximation accuracy, thus outperforming ode45 and ode15s, especially in the cases where steep gradients arise. Furthermore, the computational times of our approach are comparable with those of the two MATLAB solvers for practical purposes.
