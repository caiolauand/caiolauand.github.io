---
title: "Approaching Quartic Convergence Rates for Quasi-Stochastic Approximation with Application to Gradient-Free Optimization"
collection: publications
permalink: /publication/QuarticQSA-NeurIPS
date: 2022-11-28
venue: 'Advances in Neural Information Processing Systems 35 (NeurIPS 2022)'
paperurl: 'https://proceedings.neurips.cc/paper_files/paper/2022/hash/6530274c68e81047e1f4a2ceb0b8c0ef-Abstract-Conference.html'
---

Stochastic approximation is a foundation for many algorithms found in machine learning and optimization.   It is in general slow to converge:  the mean square error vanishes as $$O(n^{-1})$$.    A deterministic counterpart known as quasi-stochastic approximation is a viable alternative in many applications, including gradient-free optimization and reinforcement learning.   It was assumed in prior research that the optimal achievable convergence rate is $$O(n^{-2})$$.    It is shown in this paper that through design it is possible to obtain far faster convergence,   of order $$O(n^{-4+\delta})$$,  with $$\delta>0$$  arbitrary.   
Two techniques are introduced for the first time to achieve this rate of convergence.   The theory is also specialized within the context of gradient-free optimization, and tested on standard benchmarks.  The main results are based on a combination of novel application of results from number theory and techniques adapted from stochastic approximation theory.
