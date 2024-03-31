---
title: "Markovian Foundations for Quasi-Stochastic Approximation with Applications to Extremum Seeking Control"
collection: publications
permalink: /publication/MarkovQSA-arxiv
excerpt: 'This paper concerns  quasi-stochastic approximation (QSA) to solve root finding problems commonly found in applications to optimization and reinforcement learning.     The general constant gain algorithm may be expressed as the time-inhomogeneous ODE $$ \tfrac{d}{dt} \Theta_t = \alpha f_t (\Theta_t)$$,  with state process $$\Theta$$ evolving on $$\mathbb{R}^d$$.    Theory is based on an almost periodic vector field, so that in particular the time average of $$f_t(\theta)$$ defines the time-homogeneous mean vector field $$\bar{f}\colon\mathbb{R}^d\to\mathbb{R}^d$$ with $$\bar{f}(\theta^*) = 0$$.    Under smoothness assumptions on the functions involved, the following exact representation is obtained:
along with formulae for the smooth signals $\{ \overline{\Upsilon}_t, \mathcal{W}_t^i :  i=0, 1, 2\}$.    This representation is based on the application of techniques from Markov processes,  for which Poisson's equation plays a central role. This new representation, combined with new conditions for ultimate boundedness, has many applications for furthering the theory of QSA and its applications, including the following implications that are developed in this paper:  
======
* A proof that the estimation error $$\| \Theta_t - \theta^* \|$$ is of order $$O(\alpha)$$, but can be reduced to $$O(\alpha^2)$$  using a second order linear filter.   
* In application to extremum seeking control (an approach to gradient free optimization), 
it is found that the results do not apply because the standard algorithms are not Lipschitz continuous.   A new approach is presented to ensure that the required Lipschitz bounds hold, and from this we obtain stability, transient bounds,   asymptotic bias of order  $$O(\alpha^2)$$, and asymptotic variance of order  $$O(\alpha^4)$$.    
* It is in general possible to obtain better than $$O(\alpha)$$  bounds on error in traditional stochastic approximation when there is Markovian noise.'
date: 2022-07-13
venue: 'ArXiv'
paperurl: 'https://arxiv.org/pdf/2207.06371.pdf'
---
