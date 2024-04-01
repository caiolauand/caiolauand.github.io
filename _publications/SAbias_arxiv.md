---
title: "The Curse of Memory in Stochastic Approximation: Extended Version"
collection: publications
permalink: /publication/SAbias-arxiv
date: 2023-09-06
venue: 'ArXiv'
paperurl: 'https://arxiv.org/pdf/2309.02944.pdf'
---

Theory and application of stochastic approximation (SA) has grown within the control systems community since the earliest days of adaptive control.   
This paper takes a new look at the topic, motivated by recent results establishing remarkable performance of SA with (sufficiently small) constant step-size $$\alpha>0$$.    If averaging is implemented to obtain the final parameter estimate,  then the estimates are asymptotically unbiased with nearly optimal asymptotic covariance.    These results have been obtained for random linear SA recursions with i.i.d.\ coefficients.   

This paper obtains very different conclusions in the more common case of geometrically ergodic Markovian disturbance:   
(i) The \textit{target bias} is identified, even in the case of non-linear SA, and is in general non-zero.  The remaining results are established for linear SA recursions:  
(ii)  the bivariate parameter-disturbance process is geometrically ergodic in a topological sense;
(iii)    the representation for bias has a simpler form in this case, and cannot be expected to be zero if there is multiplicative noise;
(iv)   the asymptotic covariance of the  averaged parameters is  within $$O(\alpha)$$ of optimal.  The error term is identified, and may be massive if mean dynamics are not well conditioned.  The theory is illustrated with application to TD-learning.  
