---
title: "Towards Efficient and Optimal Covariance-Adaptive Algorithms for Combinatorial Semi-Bandits"
collection: publications
category: conferences
permalink: /publication/2024_Towards
excerpt: ''
date: 2024/01/01
venue: 'NeurIPS 2024'
slidesurl: ''
paperurl: 'https://arxiv.org/abs/2402.15171'
citation: 'Zhou, J., Gaillard, P., Rahier, T., Zenati, H., & Arbel, J. (2024). Towards efficient and optimal covariance-adaptive algorithms for combinatorial semi-bandits. In The Thirty-eighth Annual Conference on Neural Information Processing Systems.'
---

We address the problem of stochastic combinatorial semi-bandits, where a player selects among actions from the power set of a set containing base items. Adaptivity to the problem's structure is essential in order to obtain optimal regret upper bounds. As estimating the coefficients of a covariance matrix can be manageable in practice, leveraging them should improve the regret. We design ``optimistic'' covariance-adaptive algorithms relying on online estimations of the covariance structure, called OLS-UCB-C and COS-V (only the variances for the latter). They both yields improved gap-free regret. Although COS-V can be slightly suboptimal, it improves on computational complexity by taking inspiration from Thompson Sampling approaches. It is the first sampling-based algorithm satisfying a $\sqrt(T)$ gap-free regret (up to poly-logs). We also show that in some cases, our approach efficiently leverages the semi-bandit feedback and outperforms bandit feedback approaches, not only in exponential regimes where $P\gg d$ but also when $P\leq d$, which is not covered by existing analyses.