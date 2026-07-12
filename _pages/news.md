---
permalink: /news/
title: "News"
author_profile: true
redirect_from:
  - /wordpress/news/
---

<style>
.page__title {
  display: none;
}

.news-filter-bar {
  display: flex;
  gap: 6px;
  margin-bottom: 18px;
  flex-wrap: wrap;
}
.news-filter-btn {
  font-size: 0.78rem;
  font-weight: 600;
  padding: 5px 14px;
  border: 1.5px solid rgba(8, 48, 107, 0.2);
  border-radius: 20px;
  background: none;
  color: #4F758B;
  cursor: pointer;
  transition: all 0.2s;
}
.news-filter-btn:hover {
  border-color: #08306B;
  color: #08306B;
}
.news-filter-btn.active {
  background: #08306B;
  border-color: #08306B;
  color: #fff;
}

.news-list {
  list-style: none;
  margin: 0;
  padding: 0;
  max-height: 420px;
  overflow-y: auto;
}
.news-list.expanded {
  max-height: none;
  overflow: visible;
}
.news-list li {
  display: flex;
  gap: 16px;
  padding: 11px 0;
  border-bottom: 1px solid rgba(8, 48, 107, 0.08);
  font-size: 0.95rem;
}
.news-list li:last-child {
  border-bottom: none;
}
.news-date {
  flex-shrink: 0;
  width: 90px;
  color: #4F758B;
  font-weight: 600;
  font-size: 0.85rem;
  padding-top: 1px;
}
.news-tag {
  display: inline-block;
  font-size: 0.68rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.06em;
  padding: 2px 7px;
  border-radius: 3px;
  margin-right: 6px;
  vertical-align: middle;
  position: relative;
  top: -1px;
}
.tag-patent { background: rgba(8, 81, 156, 0.15); color: #08519C; }
.tag-award { background: rgba(255, 209, 0, 0.2); color: #9A7800; }
.tag-milestone { background: rgba(0, 128, 96, 0.15); color: #00734D; }
.tag-journal { background: rgba(66, 146, 198, 0.2); color: #2A6F97; }
.tag-conference { background: rgba(0, 89, 76, 0.2); color: #00594C; }
.tag-preprint { background: rgba(239, 68, 111, 0.15); color: #C43A5C; }
.tag-talk { background: rgba(8, 48, 107, 0.15); color: #08306B; }
.tag-newrole { background: rgba(146, 64, 14, 0.15); color: #92400E; }

.news-show-all {
  display: block;
  margin: 16px auto 0;
  padding: 8px 20px;
  font-size: 0.82rem;
  font-weight: 600;
  color: #08306B;
  background: none;
  border: 1.5px solid #08306B;
  border-radius: 5px;
  cursor: pointer;
  transition: all 0.2s;
}
.news-show-all:hover {
  background: #08306B;
  color: #fff;
}

@media (max-width: 700px) {
  .news-list li {
    flex-direction: column;
    gap: 4px;
  }
  .news-date {
    width: auto;
  }
}
</style>

<div class="news-filter-bar" id="news-filter-bar">
  <button class="news-filter-btn active" data-filter="all">All</button>
  <button class="news-filter-btn" data-filter="patent">Patent</button>
  <button class="news-filter-btn" data-filter="publication">Publication</button>
  <button class="news-filter-btn" data-filter="award">Award</button>
  <button class="news-filter-btn" data-filter="talk">Talk</button>
  <button class="news-filter-btn" data-filter="newrole">New Role</button>
</div>

<ul class="news-list" id="news-list">

<li data-filter="patent"><span class="news-date">Apr 2026</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">Generating Dynamic Few-Shot Examples for Enterprise Text-to-SQL Tasks</span> patent filed. Joint work with Long Vu, Daniel Snoddy, Tanvi Kaple, Michael Glass, Dharmashankar Subramanian, A. W. Hagleitner.</span></li>

<li data-filter="patent"><span class="news-date">Feb 2026</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">System and Method for Combining Data Selection and Reward Function for Tuning LLMs using Reinforcement Learning</span> patent granted. Joint work with Long Vu, Shankar Subramanian, and Todd Mummert from IBM Research.</span></li>

<li data-filter="award"><span class="news-date">Feb 2026</span><span><span class="news-tag tag-award">Award</span> Received the IBM Outstanding Technical Achievement Award for NL2Insights Impacting Products and Clients.</span></li>

<li data-filter="award"><span class="news-date">Feb 2026</span><span><span class="news-tag tag-milestone">Milestone</span> Multilingual Text2SQL capabilities are now available across all IBM Cloud and AWS production regions for IBM watsonx.data intelligence SaaS, supporting English and Japanese with more languages coming.</span></li>

<li data-filter="patent"><span class="news-date">Jan 2026</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">Site-wide optimization for mixed regression models and mixed control variables</span> patent granted. Joint work with Dzung Phan and Lam Nguyen from IBM Research.</span></li>

<li data-filter="award"><span class="news-date">Dec 2025</span><span><span class="news-tag tag-award">Award</span> Received IBM Growth Award for advancing Text2SQL service within watsonx.data intelligence.</span></li>

<li data-filter="award"><span class="news-date">Dec 2025</span><span><span class="news-tag tag-award">Award</span> NL2Insights achieved Product and Client-0 Adoption &amp; Impact recognition in IBM Research Accomplishments 2025 (A-level), powering watsonx.data, BI Assistant, and Process Mining with 200,000+ SQL queries across 1,000+ databases.</span></li>

<li data-filter="patent"><span class="news-date">Aug 2025</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">Generating structured query language queries from natural language inputs with schema enrichment</span> patent filed. Joint work with Mustafa Eyceoz, Gaetano Rossiello, Michael Glass, Nandana Mihindukulasooriya, Alfio Gliozzo, Long Vu, Dharmashankar Subramanian.</span></li>

<li data-filter="award"><span class="news-date">May 2025</span><span><span class="news-tag tag-award">Award</span> Received the IBM Outstanding Technical Achievement Award for achieving first place on the BIRD Leaderboard with IBM Granite Text-to-SQL models.</span></li>

<li data-filter="publication"><span class="news-date">May 2025</span><span><span class="news-tag tag-conference">Conference</span> Our paper <span style="color:#08306B">The Consistency Hypothesis in Uncertainty Quantification for Large Language Models</span> accepted at the Forty-First Conference on Uncertainty in Artificial Intelligence (UAI 2025). Joint work with Q. Xiao, D. Bhattacharjya, B. Ganesan, R. Marinescu, K. Mirylenka, M. Glass, and J. Lee.</span></li>

<li data-filter="patent"><span class="news-date">Mar 2025</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">Database Querying Using Natural Language Processing</span> patent filed. Joint work with Oktie Hassanzadeh, Dharmashankar Subramanian, Lisa Amini, Gaetano Rossiello, M. Faisal Chowdhury, Long Vu, Tanvi Kaple, Michael Glass.</span></li>

<li data-filter="award"><span class="news-date">Dec 2024</span><span><span class="news-tag tag-award">Award</span> IBM Granite fine-tuned Text-to-SQL models swept top spots in the BIRD Leaderboard in IBM Research Accomplishments 2024 (A-level) &mdash; Granite-20B and Granite-34B took first place in both tracks, outperforming GPT-4 and GPT-4o. Featured at THINK'24 and deployed on BAM and watsonx.ai.</span></li>

<li data-filter="patent"><span class="news-date">Aug 2024</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">Fine-tuned generative model</span> patent filed. Joint work with Elita Lobo, Long Vu, Todd Mummert, Dharmashankar Subramanian.</span></li>

<li data-filter="newrole"><span class="news-date">Apr 2024</span><span><span class="news-tag tag-newrole">New Role</span> Promoted to Staff Research Scientist at <a href="https://research.ibm.com/" target="_blank">IBM Research</a>, Thomas J. Watson Research Center.</span></li>

<li data-filter="patent"><span class="news-date">Jan 2024</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">Combining data selection and reward functions for tuning large language models using reinforcement learning</span> patent filed. Joint work with Long Vu, Dharmashankar Subramanian, Todd Mummert.</span></li>

<li data-filter="publication"><span class="news-date">Sep 2023</span><span><span class="news-tag tag-conference">Conference</span> Our paper <span style="color:#08306B">Evaluating Robustness of Cooperative MARL: A Model-based Approach</span> accepted at the 2023 IEEE International Conference on Data Mining (ICDM). Joint work with Dr. Lam M. Nguyen, Dr. Jie Chen, Dr. Hoang Thanh Lam, Dr. Subhro Das, and Dr. Tsui-Wei Weng. <a href="https://ieeexplore.ieee.org/document/10415752" target="_blank">[Paper]</a></span></li>

<li data-filter="patent"><span class="news-date">Jun 2023</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">Generative modeling and representational learning from multi-sequence alignment and phylogenetic tree data</span> patent filed. Joint work with Thanh Lam Hoang, Marcos M. Galindo, Gabriele Picco, Mykhaylo Zayats, Lam M. Nguyen, Marco Sbodio, Dzung T. Phan, Vanessa Garcia.</span></li>

<li data-filter="patent"><span class="news-date">Jun 2023</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">A novel meta-hyperparameter tuning system for RL using sequence model</span> patent filed. Joint work with Elita Lobo, Dharmashankar Subramanian.</span></li>

<li data-filter="patent"><span class="news-date">Jun 2023</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">Reinforcement machine learning with multi-level agent search and hyperparameter optimization</span> patent filed. Joint work with Long Vu, Peter Kirchner, Radu Marinescu, Dharmashankar Subramanian.</span></li>

<li data-filter="talk"><span class="news-date">Feb 2023</span><span><span class="news-tag tag-talk">Talk</span> Co-organizing a tutorial/lab forum "LSHA2: Automated AI for Decision Optimization with Reinforcement Learning" at <a href="https://aaai-23.aaai.org/" target="_blank">AAAI 2023</a>.</span></li>

<li data-filter="talk"><span class="news-date">Feb 2023</span><span><span class="news-tag tag-talk">Talk</span> Session Chair of <strong>ML: Optimization 1</strong> at AAAI 2023 on Feb 10, 2023.</span></li>

<li data-filter="patent"><span class="news-date">Sep 2022</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">Adversarial Attacks for Improving Cooperative Multi-Agent Reinforcement Learning Systems</span> patent filed. Joint work with Lam M. Nguyen, Jie Chen, Thanh-Lam Hoang, Subhro Das.</span></li>

<li data-filter="newrole"><span class="news-date">Jan 2022</span><span><span class="news-tag tag-newrole">New Role</span> Started new role as Research Scientist at <a href="https://research.ibm.com/" target="_blank">IBM</a> Thomas J. Watson Research Center, Yorktown Heights, NY.</span></li>

<li data-filter="newrole"><span class="news-date">Dec 2021</span><span><span class="news-tag tag-newrole">New Role</span> Completed PhD in Operations Research in the Department of Statistics and Operations Research at University of North Carolina at Chapel Hill. <a href="https://cdr.lib.unc.edu/concern/dissertations/qb98mr30t?locale=en" target="_blank">Dissertation</a></span></li>

<li data-filter="publication"><span class="news-date">Sep 2021</span><span><span class="news-tag tag-conference">Conference</span> Our manuscript <span style="color:#08306B">FedDR &ndash; Randomized Douglas-Rachford Splitting Algorithms for Nonconvex Federated Composite Optimization</span> accepted at the 35th Conference on Neural Information Processing Systems. Joint work with <strong>Lam Nguyen</strong>, <strong>Dzung Phan</strong> (IBM Research) and <strong>Quoc Tran-Dinh</strong> (UNC Chapel Hill). <a href="https://arxiv.org/pdf/2103.03452.pdf" target="_blank">[Preprint]</a></span></li>

<li data-filter="newrole"><span class="news-date">Aug 2021</span><span><span class="news-tag tag-milestone">Milestone</span> Finished summer internship at <a href="https://www.bluerivertechnology.com/" target="_blank">Blue River Technology</a>.</span></li>

<li data-filter="publication"><span class="news-date">Jun 2021</span><span><span class="news-tag tag-preprint">Preprint</span> Completed the manuscript <span style="color:#08306B">FedDR &ndash; Randomized Douglas-Rachford Splitting Algorithms for Nonconvex Federated Composite Optimization</span> with <strong>Lam Nguyen</strong>, <strong>Dzung Phan</strong> (IBM Research) and <strong>Quoc Tran-Dinh</strong> (UNC Chapel Hill). <a href="https://arxiv.org/pdf/2103.03452.pdf" target="_blank">[Preprint]</a></span></li>

<li data-filter="patent"><span class="news-date">May 2021</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">Site-Wide Optimization for Mixed Regression Models and Mixed Control Variables</span> patent filed. Joint work with Dzung T. Phan, Lam M. Nguyen.</span></li>

<li data-filter="newrole"><span class="news-date">May 2021</span><span><span class="news-tag tag-newrole">New Role</span> Joined <a href="https://www.bluerivertechnology.com/" target="_blank">Blue River Technology</a> as Machine Learning Intern.</span></li>

<li data-filter="publication"><span class="news-date">Mar 2021</span><span><span class="news-tag tag-preprint">Preprint</span> Completed the manuscript <span style="color:#08306B">Federated Learning with Randomized Douglas-Rachford Splitting Methods</span> with <strong>Lam Nguyen</strong>, <strong>Dzung Phan</strong> (IBM Research) and <strong>Quoc Tran-Dinh</strong> (UNC Chapel Hill). <a href="https://arxiv.org/pdf/2103.03452v1.pdf" target="_blank">[Preprint]</a></span></li>

<li data-filter="publication"><span class="news-date">Jan 2021</span><span><span class="news-tag tag-conference">Conference</span> Our paper <span style="color:#08306B">Regression Optimization for System-level Production Control</span> accepted to the 2021 American Control Conference (ACC). Joint work with <strong>Dzung Phan</strong>, <strong>Lam Nguyen</strong>, <strong>Pavankumar Murali</strong> (IBM Research), <strong>Hongsheng Liu</strong> (UNC Chapel Hill), and <strong>Jayant Kalagnanam</strong> (IBM Research). <a href="https://ieeexplore.ieee.org/document/9482638" target="_blank">[Full paper]</a></span></li>

<li data-filter="publication"><span class="news-date">Oct 2020</span><span><span class="news-tag tag-journal">Journal</span> Our paper <span style="color:#08306B">A Hybrid Stochastic Optimization Framework for Stochastic Composite Nonconvex Optimization</span> accepted for publication at <strong>Mathematical Programming</strong>. Joint work with <strong>Quoc Tran-Dinh</strong> (UNC Chapel Hill), <strong>Lam Nguyen</strong> and <strong>Dzung Phan</strong> (IBM Research). <a href="https://link.springer.com/article/10.1007/s10107-020-01583-1" target="_blank">[Full paper]</a></span></li>

<li data-filter="newrole"><span class="news-date">Aug 2020</span><span><span class="news-tag tag-milestone">Milestone</span> Finished summer internship at <a href="https://research.ibm.com/" target="_blank">IBM Research</a>, mentored by Dzung T. Phan and Lam M. Nguyen, and supervised by Roman Vaculin.</span></li>

<li data-filter="publication"><span class="news-date">Jun 2020</span><span><span class="news-tag tag-conference">Conference</span> Our paper <span style="color:#08306B">Stochastic Gauss-Newton Algorithms for Nonconvex Compositional Optimization</span> accepted for publication at the International Conference on Machine Learning (ICML). Joint work with <strong>Lam Nguyen</strong> (IBM Research) and <strong>Quoc Tran-Dinh</strong> (UNC Chapel Hill). <a href="http://proceedings.mlr.press/v119/tran-dinh20a.html" target="_blank">[Full paper]</a></span></li>

<li data-filter="newrole"><span class="news-date">May 2020</span><span><span class="news-tag tag-newrole">New Role</span> Joined <a href="https://research.ibm.com/" target="_blank">IBM Research</a> as Research Intern.</span></li>

<li data-filter="publication"><span class="news-date">May 2020</span><span><span class="news-tag tag-journal">Journal</span> Our paper <span style="color:#08306B">ProxSARAH: An Efficient Algorithmic Framework For Stochastic Composite Nonconvex Optimization</span> accepted for publication at the Journal of Machine Learning Research (JMLR). Joint work with <strong>Lam Nguyen</strong> (IBM Research), <strong>Dzung Phan</strong> (IBM Research), and <strong>Quoc Tran-Dinh</strong> (UNC Chapel Hill). <a href="http://proceedings.mlr.press/v119/tran-dinh20a.html" target="_blank">[Full paper]</a></span></li>

<li data-filter="publication"><span class="news-date">Feb 2020</span><span><span class="news-tag tag-preprint">Preprint</span> Completed the manuscript <span style="color:#08306B">Stochastic Gauss-Newton Algorithms for Nonconvex Compositional Optimization</span> with <strong>Lam Nguyen</strong> (IBM Research) and <strong>Quoc Tran-Dinh</strong> (UNC Chapel Hill). <a href="https://arxiv.org/pdf/2002.07290.pdf" target="_blank">[Preprint]</a></span></li>

<li data-filter="publication"><span class="news-date">Feb 2020</span><span><span class="news-tag tag-preprint">Preprint</span> Manuscript <span style="color:#08306B">Convergence Rates of Accelerated Markov Gradient Descent with Applications in Reinforcement Learning</span> released, joint work with <strong>Thinh Doan</strong> (GA Tech), <strong>Lam Nguyen</strong> (IBM Research), <strong>Justin Romberg</strong> (GA Tech). <a href="https://arxiv.org/pdf/2103.03452v1.pdf" target="_blank">[Preprint]</a></span></li>

<li data-filter="publication"><span class="news-date">Jan 2020</span><span><span class="news-tag tag-journal">Journal</span> Our manuscript <span style="color:#08306B">ProxSARAH: An Efficient Algorithmic Framework For Stochastic Composite Nonconvex Optimization</span> accepted for publication at the Journal of Machine Learning Research (JMLR) with minor revision. <a href="https://arxiv.org/pdf/1902.05679.pdf" target="_blank">[Preprint]</a></span></li>

<li data-filter="publication"><span class="news-date">Jan 2020</span><span><span class="news-tag tag-conference">Conference</span> Our paper <span style="color:#08306B">A Hybrid Stochastic Policy Gradient Algorithm for Reinforcement Learning</span> accepted for AISTATS 2020. Joint work with <strong>Lam Nguyen</strong> (IBM Research), <strong>Dzung Phan</strong> (IBM Research), <strong>Phuong-Ha Nguyen</strong> (UConn), <strong>Marten van Dijk</strong> (UConn), and <strong>Quoc Tran-Dinh</strong> (UNC Chapel Hill). <a href="http://proceedings.mlr.press/v108/pham20a.html" target="_blank">[Full paper]</a></span></li>

<li data-filter="talk"><span class="news-date">Oct 2019</span><span><span class="news-tag tag-talk">Talk</span> Traveled to Seattle for the 2019 INFORMS Annual Meeting to present <span style="color:#08306B">ProxSARAH: An Efficient Algorithmic Framework For Stochastic Composite Nonconvex Optimization</span>, joint work with <strong>Lam Nguyen</strong> (IBM Research), <strong>Dzung Phan</strong> (IBM Research), and <strong>Quoc Tran-Dinh</strong> (UNC Chapel Hill).</span></li>

<li data-filter="award"><span class="news-date">Aug 2019</span><span><span class="news-tag tag-award">Award</span> Worked with Quoc Tran-Dinh as a SAMSI (The Statistical and Applied Mathematical Sciences Institute) Research Fellow for the 2019 Fall Program on Deep Learning.</span></li>

<li data-filter="publication"><span class="news-date">Jul 2019</span><span><span class="news-tag tag-preprint">Preprint</span> Completed the manuscript <span style="color:#08306B">A Hybrid Stochastic Optimization Framework for Composite Nonconvex Optimization</span> with <strong>Lam Nguyen</strong> (IBM Research), <strong>Dzung Phan</strong> (IBM Research), and <strong>Quoc Tran-Dinh</strong> (UNC Chapel Hill). <a href="https://nhanph.github.io/research/" target="_blank">Research page</a>.</span></li>

<li data-filter="publication"><span class="news-date">Feb 2019</span><span><span class="news-tag tag-preprint">Preprint</span> Completed the manuscript <span style="color:#08306B">ProxSARAH: An Efficient Algorithmic Framework For Stochastic Composite Nonconvex Optimization</span> with <strong>Lam Nguyen</strong> (IBM Research), <strong>Dzung Phan</strong> (IBM Research), and <strong>Quoc Tran-Dinh</strong> (UNC Chapel Hill). <a href="https://nhanph.github.io/research/" target="_blank">Research page</a>.</span></li>

<li data-filter="newrole"><span class="news-date">Aug 2017</span><span><span class="news-tag tag-newrole">New Role</span> Started PhD in Operations Research at University of North Carolina at Chapel Hill &middot; Chapel Hill, NC, USA. Under supervision of professor <a href="https://quoctd.web.unc.edu/" target="_blank">Quoc Tran-Dinh</a>.</span></li>

</ul>

<button class="news-show-all" id="news-show-all">Show all &darr;</button>

<script>
(function () {
  var filterBtns = document.querySelectorAll('#news-filter-bar .news-filter-btn');
  var items = document.querySelectorAll('#news-list li');

  filterBtns.forEach(function (btn) {
    btn.addEventListener('click', function () {
      filterBtns.forEach(function (b) { b.classList.remove('active'); });
      btn.classList.add('active');
      var filter = btn.getAttribute('data-filter');
      items.forEach(function (li) {
        li.style.display = (filter === 'all' || li.getAttribute('data-filter') === filter) ? '' : 'none';
      });
    });
  });

  var showAllBtn = document.getElementById('news-show-all');
  var newsList = document.getElementById('news-list');
  showAllBtn.addEventListener('click', function () {
    var expanded = newsList.classList.toggle('expanded');
    showAllBtn.innerHTML = expanded ? 'Show less &uarr;' : 'Show all &darr;';
  });
})();
</script>
