---
layout: archive
title: "Research"
permalink: /research/
author_profile: false
---

<style>
.page__title {
  display: none;
}

.pub-body {
  display: flex;
  gap: 16px;
  margin-bottom: 1em;
}
.pub-date {
  flex-shrink: 0;
  width: 90px;
  color: #536878;
  font-weight: 600;
  font-size: 0.8rem;
  padding-top: 1px;
}
.pub-desc {
  flex: 1;
  min-width: 0;
}

.pub-tab-bar {
  display: flex;
  gap: 6px;
  margin-bottom: 18px;
  flex-wrap: wrap;
}
.pub-tab-btn {
  font-size: 0.8rem;
  font-weight: 600;
  padding: 5px 14px;
  border: 1.5px solid rgba(8, 48, 107, 0.2);
  border-radius: 20px;
  background: none;
  color: #4F758B;
  cursor: pointer;
  transition: all 0.2s;
}
.pub-tab-btn:hover {
  border-color: #08306B;
  color: #08306B;
}
.pub-tab-btn.active {
  background: #08306B;
  border-color: #08306B;
  color: #fff;
}

.pub-panel {
  display: none;
}
.pub-panel.active {
  display: block;
}

@media (max-width: 700px) {
  .pub-body {
    flex-direction: column;
    gap: 4px;
  }
  .pub-date {
    width: auto;
  }
}
</style>

<script>
function showhide(id) {
  var e = document.getElementById(id);
  e.style.display = (e.style.display == 'block') ? 'none' : 'block';
}  
</script>

## Research Interest

- **Large Language Models (LLMs)** for enterprise data management applications, particularly Text-to-SQL systems
- **Stochastic optimization methods** for machine learning, deep learning, and reinforcement learning
- **Multi-agent reinforcement learning** and robustness evaluation
- **Federated learning** and distributed optimization

## Publications

<div class="pub-tab-bar" id="pub-tab-bar">
  <button class="pub-tab-btn active" data-tab="preprints">Preprints</button>
  <button class="pub-tab-btn" data-tab="conference">Conference</button>
  <button class="pub-tab-btn" data-tab="journal">Journal</button>
  <button class="pub-tab-btn" data-tab="workshop">Workshop</button>
</div>

<div class="pub-panel active" data-tab="preprints" markdown="1">

<div class="pub-body">
<div class="pub-date">2020</div>
<div class="pub-desc" markdown="1">

<a href="https://arxiv.org/pdf/2002.02873" target="_blank" style="color:#08306B">Convergence Rates of Accelerated Markov Gradient Descent with Applications in Reinforcement Learning.</a><br>
*<strong style="color:#08306B">arXiv:2002.02873</strong>.*<br>
T. T. Doan, L. M. Nguyen, **N. H. Pham**, and J. Romberg.

</div>
</div>

<div class="pub-body">
<div class="pub-date">2020</div>
<div class="pub-desc" markdown="1">

<a href="https://arxiv.org/pdf/2003.10973" target="_blank" style="color:#08306B">Finite-Time Analysis of Stochastic Gradient Descent under Markov Randomness.</a><br>
*<strong style="color:#08306B">arXiv:2003.10973</strong>.*<br>
T. T. Doan, L. M. Nguyen, **N. H. Pham**, and J. Romberg.

</div>
</div>

</div>

<div class="pub-panel" data-tab="conference" markdown="1">

<div class="pub-body">
<div class="pub-date">2025</div>
<div class="pub-desc" markdown="1">

<span style="color:#08306B">The Consistency Hypothesis in Uncertainty Quantification for Large Language Models.</span><br>
*Forty-First Conference on Uncertainty in Artificial Intelligence (<strong style="color:#08306B">UAI 2025</strong>).*<br>
Q. Xiao, D. Bhattacharjya, B. Ganesan, R. Marinescu, K. Mirylenka, **N. H. Pham**, M. Glass, and J. Lee.

</div>
</div>

<div class="pub-body">
<div class="pub-date">2023</div>
<div class="pub-desc" markdown="1">

<a href="https://ieeexplore.ieee.org/document/10415752" target="_blank" style="color:#08306B">Evaluating Robustness of Cooperative MARL: A Model-based Approach.</a><br>
*2023 IEEE International Conference on Data Mining (<strong style="color:#08306B">ICDM</strong>).*<br>
**N. H. Pham**, L. M. Nguyen, J. Chen, H. T. Lam, S. Das, T. W. Weng.

</div>
</div>

<div class="pub-body">
<div class="pub-date">2021</div>
<div class="pub-desc" markdown="1">

<a href="https://arxiv.org/pdf/2103.03452.pdf" target="_blank" style="color:#08306B">FedDR–Randomized Douglas-Rachford Splitting Algorithms for Nonconvex Federated Composite Optimization.</a><br>
*The 35th Conference on Neural Information Processing Systems (<strong style="color:#08306B">NeurIPS 2021</strong>).*<br>
Q. Tran-Dinh, **N. H. Pham**, D. T. Phan, and L. M. Nguyen.

</div>
</div>

<div class="pub-body">
<div class="pub-date">2021</div>
<div class="pub-desc" markdown="1">

<a href="https://ieeexplore.ieee.org/document/9482638" target="_blank" style="color:#08306B">Regression Optimization for System-level Production Control.</a><br>
*2021 American Control Conference (<strong style="color:#08306B">ACC</strong>).*<br>
D. T. Phan, L. M. Nguyen, P. Murali, **N. H. Pham**, H. Liu, J. Kalagnanam.

</div>
</div>

<div class="pub-body">
<div class="pub-date">2020</div>
<div class="pub-desc" markdown="1">

<a href="http://proceedings.mlr.press/v119/tran-dinh20a.html" target="_blank" style="color:#08306B">Stochastic Gauss-Newton Algorithms for Nonconvex Compositional Optimization.</a><br>
*The 37th International Conference on Machine Learning (<strong style="color:#08306B">ICML 2020</strong>).*<br>
Q. Tran-Dinh, **N. H. Pham**, and L. M. Nguyen.<br>
<a href="https://github.com/unc-optimization/SGN" target="_blank">[Python Code]</a>

</div>
</div>

<div class="pub-body">
<div class="pub-date">2020</div>
<div class="pub-desc" markdown="1">

<a href="http://proceedings.mlr.press/v108/pham20a.html" target="_blank" style="color:#08306B">A Hybrid Stochastic Policy Gradient Algorithm for Reinforcement Learning.</a><br>
*The 23rd International Conference on Artificial Intelligence and Statistics (<strong style="color:#08306B">AISTATS 2020</strong>).*<br>
**N. H. Pham**, L. M. Nguyen, D. T. Phan, P. H. Nguyen, M. van Dijk, and Q. Tran-Dinh.<br>
<a href="https://github.com/unc-optimization/ProxHSPGA" target="_blank">[Python Code]</a>

</div>
</div>

<div class="pub-body">
<div class="pub-date">2017</div>
<div class="pub-desc" markdown="1">

<a href="https://www.researchgate.net/profile/Hung_La/publication/316190868_Autonomous_Robotic_System_using_Non-Destructive_Evaluation_methods_for_Bridge_Deck_Inspection/links/58fb75e30f7e9ba3ba523d10/Autonomous-Robotic-System-using-Non-Destructive-Evaluation-methods-for-Bridge-Deck-Inspection.pdf" target="_blank" style="color:#08306B">Autonomous Robotic System using Non-Destructive Evaluation methods for Bridge Deck Inspection.</a><br>
*IEEE International Conference on Robotics and Automation (<strong style="color:#08306B">ICRA</strong>).*<br>
T. D. Le, S. Gibb, **N. H. Pham**, H. M. La, L. Falk, and T. Berendsen.

</div>
</div>

<div class="pub-body">
<div class="pub-date">2016</div>
<div class="pub-desc" markdown="1">

<a href="https://www.researchgate.net/profile/Nhan_Pham8/publication/313692693_Design_and_implementation_of_an_autonomous_robot_for_steel_bridge_inspection/links/5c66460b45851582c3e97be9/Design-and-implementation-of-an-autonomous-robot-for-steel-bridge-inspection.pdf" target="_blank" style="color:#08306B">Design and Implementation of an Autonomous Robot for Steel Bridge Inspection.</a><br>
*54th Annual Allerton Conference on Communication, Control, and Computing (<strong style="color:#08306B">Allerton</strong>).*<br>
**N. H. Pham** and H. M. La.

</div>
</div>

<div class="pub-body">
<div class="pub-date">2016</div>
<div class="pub-desc" markdown="1">

<a href="http://www.iaarc.org/publications/fulltext/ISARC2016-Paper029.pdf" target="_blank" style="color:#08306B">Visual and 3D Mapping for Steel Bridge Inspection Using a Climbing Robot.</a><br>
*33rd International Symposium on Automation and Robotics in Construction and Mining (<strong style="color:#08306B">ISARC</strong>).*<br>
**N. H. Pham**, H. M. La, Q. P. Ha, S. N. Dang, A. H. Vo, and Q. H. Dinh.

</div>
</div>

<div class="pub-body">
<div class="pub-date">2013</div>
<div class="pub-desc" markdown="1">

<span style="color:#08306B">Quadrotor Helicopter: A Practical Design Approach.</span><br>
*IEICE International Conference on Integrated Circuits, Design and Verification (<strong style="color:#08306B">IEICE</strong>).*<br>
T.-D. D. Phan, **N. H. Pham**, K.-N. Le-Huu, and A.-V. D. Dinh.

</div>
</div>

</div>

<div class="pub-panel" data-tab="journal" markdown="1">

<div class="pub-body">
<div class="pub-date">2021</div>
<div class="pub-desc" markdown="1">

<a href="https://link.springer.com/article/10.1007/s10107-020-01583-1" target="_blank" style="color:#08306B">A Hybrid Stochastic Optimization Framework for Composite Nonconvex Optimization.</a><br>
*<strong style="color:#08306B">Mathematical Programming</strong>.*<br>
Q. Tran-Dinh, **N. H. Pham**, D. T. Phan, and L. M. Nguyen.

</div>
</div>

<div class="pub-body">
<div class="pub-date">2020</div>
<div class="pub-desc" markdown="1">

<a href="https://www.jmlr.org/papers/v21/19-248.html" target="_blank" style="color:#08306B">ProxSARAH: An Efficient Algorithmic Framework for Stochastic Composite Nonconvex Optimization.</a><br>
*Journal of Machine Learning Research (<strong style="color:#08306B">JMLR</strong>).*<br>
**N. H. Pham**, L. M. Nguyen, D. T. Phan, and Q. Tran-Dinh.<br>
<a href="https://github.com/unc-optimization/StochasticProximalMethods" target="_blank">[Python Code]</a>

</div>
</div>

<div class="pub-body">
<div class="pub-date">2018</div>
<div class="pub-desc" markdown="1">

<span style="color:#08306B">Automated Robotic Monitoring and Inspection of Steel Structures and Bridges.</span><br>
*<strong style="color:#08306B">Robotica</strong>.*<br>
H. M. La, T. H. Dinh, **N. H. Pham**, Q. P. Ha, and A. Q. Pham.

</div>
</div>

</div>

<div class="pub-panel" data-tab="workshop" markdown="1">

<div class="pub-body">
<div class="pub-date">2026</div>
<div class="pub-desc" markdown="1">

<span style="color:#08306B">Black-Box Uncertainty Quantification for Large Language Models via Ensemble-of-Ensembles.</span><br>
*AAAI 2026 Workshop on Assessing and Improving Reliability of Foundation Models in the Real World (<strong style="color:#08306B">AAAI 2026 Workshop</strong>).*<br>
W. Ma, D. Bhattacharjya, J. Lee, **N. H. Pham**, H. Kokel, Q. Ji.

</div>
</div>

<div class="pub-body">
<div class="pub-date">2025</div>
<div class="pub-desc" markdown="1">

<a href="https://arxiv.org/abs/2511.09693" target="_blank" style="color:#08306B">ConstrainedSQL: Training LLMs for Text2SQL via Constrained Reinforcement Learning.</a><br>
*NeurIPS 2025 Workshop on Efficient Reasoning (<strong style="color:#08306B">NeurIPS 2025 Workshop</strong>).*<br>
W. Chen, **N. H. Pham**, M. Glass, L. Vu, G. Rossiello, D. Subramanian, S. Paternain.

</div>
</div>

<div class="pub-body">
<div class="pub-date">2025</div>
<div class="pub-desc" markdown="1">

<a href="https://arxiv.org/abs/2502.06759" target="_blank" style="color:#08306B">Rationalization Models for Text-to-SQL.</a><br>
*ICLR 2025 Workshop on Reasoning and Planning for LLMs (<strong style="color:#08306B">ICLR 2025 Workshop</strong>).*<br>
G. Rossiello, **N. H. Pham**, M. Glass, J. Lee, D. Subramanian.

</div>
</div>

</div>

<script>
(function () {
  var pubTabBtns = document.querySelectorAll('#pub-tab-bar .pub-tab-btn');
  var pubPanels = document.querySelectorAll('.pub-panel');

  pubTabBtns.forEach(function (btn) {
    btn.addEventListener('click', function () {
      pubTabBtns.forEach(function (b) { b.classList.remove('active'); });
      btn.classList.add('active');
      var tab = btn.getAttribute('data-tab');
      pubPanels.forEach(function (p) {
        p.classList.toggle('active', p.getAttribute('data-tab') === tab);
      });
    });
  });
})();
</script>
