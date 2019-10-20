---
title: "A Hybrid Stochastic Optimization Framework for Composite Nonconvex Optimization"
collection: publications
permalink: /publication/2019-07-08-ProxHybrid
excerpt: 'We introduce a new approach to develop stochastic optimization algorithms for a class of stochastic composite and possibly nonconvex optimization problems.'
date: 2019-07-08
venue: 'Submitted to Math. Prog.'
paperurl: 'https://arxiv.org/abs/1907.03793'
citation: 'Q. Tran-Dinh, N. H. Pham, D. T. Phan, and L. M. Nguyen. A Hybrid Stochastic Optimization Framework for Stochastic Composite Nonconvex Optimization. Preprint: arXiv:1907.03793, 2019.'
---

<details>
<summary>Paper abtract</summary>
<br>
We introduce a new approach to develop stochastic optimization algorithms for a class of stochastic composite and possibly nonconvex optimization problems.
The main idea is to combine two stochastic estimators to create a new hybrid one.  
We first introduce our hybrid estimator and then investigate its fundamental properties to form foundational theories for algorithmic development.  
Next, we apply our theory to develop several variants of stochastic gradient methods to solve both expectation and finite-sum composite optimization problems. 
Our first algorithm can be viewed as a variant of proximal stochastic gradient methods with a single-loop, but can achieve  $\mathcal{O}\left(\sigma^3\varepsilon^{-1} + \sigma\varepsilon^{-3}\right)$-oracle complexity bound, which is best-known as state-of-the-art double-loop algorithms in the literature, where $\sigma$ is the variance and $\varepsilon$ is a desired accuracy.
Then, we consider two different variants of our method: adaptive step-size and restarting schemes that have the same theoretical guarantees as in our first algorithm.
We also study two mini-batch variants of the proposed methods.  
In all cases, we achieve the best-known complexity bounds under standard assumptions.
We test our methods on several numerical examples with real datasets and compare them with state-of-the-arts.
Our numerical experiments show that the new methods are comparable and, in many cases, outperform their competitors.
</details>

<details>
<summary>Bibtex</summary>
<br>
<pre><code class="tex bibtex">@article{TranDinh2019ProxHybrid,
  title={A Hybrid Stochastic Optimization Framework for Stochastic Composite Nonconvex Optimization},
  author={Quoc Tran-Dinh and Nhan H. Pham and Dzung T. Phan and Lam M. Nguyen},
  journal={ArXiv},
  year={2019},
  volume={abs/1907.03793}
}
</code></pre>
</details>