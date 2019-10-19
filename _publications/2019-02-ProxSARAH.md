---
title: "ProxSARAH: An Efficient Algorithmic Framework for Stochastic Composite Nonconvex Optimization"
collection: publications
permalink: /publication/2019-02-ProxSARAH
excerpt: 'We propose a new stochastic first-order algorithmic framework to solve stochastic composite nonconvex optimization problems that covers both finite-sum and expectation settings.'
date: 2019-02
venue: 'Submitted to JMLR'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

<details open>
<summary>Paper abtract.</summary>
<br>
We propose a new stochastic first-order algorithmic framework to solve stochastic  composite nonconvex optimization problems that covers both finite-sum and expectation settings.
Our algorithms rely on the SARAH estimator introduced in (Nguyen et al., 2017) and consist of two steps: a proximal gradient  and an averaging step making them different from existing nonconvex proximal-type algorithms.
The algorithms only require an average smoothness assumption of the nonconvex objective term and additional bounded variance assumption if applied to expectation problems.
They work with both  constant and adaptive step-sizes, while allowing single sample and mini-batches. 
In all these cases,  we prove that our algorithms can  achieve the best-known complexity bounds.
One key step of our methods is new constant and adaptive step-sizes that help to achieve desired complexity bounds while improving practical performance.
Our constant step-size is much larger than existing methods including proximal SVRG schemes in the single sample case. 
We also specify the algorithm to the non-composite case that covers  existing state-of-the-arts in terms of complexity bounds.
Our  update also allows one to trade-off between step-sizes and mini-batch sizes to improve performance.
We test the proposed algorithms on two composite nonconvex problems and neural networks using several well-known datasets. 
</details>

[Preprint](https://arxiv.org/abs/1902.05679)

<details open>
<summary>Bibtex</summary>
<br>
```
@article{Pham2019ProxSARAH,
  title={ProxSARAH: An Efficient Algorithmic Framework for Stochastic Composite Nonconvex Optimization},
  author={Nhan H. Pham and Lam M. Nguyen and Dzung T. Phan and Quoc Tran-Dinh},
  journal={ArXiv},
  year={2019},
  volume={abs/1902.05679}
}
```
</details>