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
.news-filter-btn[data-filter="patent"],
.news-filter-btn[data-filter="publication"],
.news-filter-btn[data-filter="award"] {
  background: #fff;
  color: #536878;
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
  overflow: hidden;
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
.news-list a,
.news-list a:visited,
.news-list a:hover {
  text-decoration: none !important;
  color: #0F52BA;
}
.news-date {
  flex-shrink: 0;
  width: 90px;
  color: #536878;
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
.tag-milestone { background: #9ecae1; color: #191970; }
.tag-journal { background: rgba(66, 146, 198, 0.2); color: #2A6F97; }
.tag-conference { background: rgba(0, 89, 76, 0.2); color: #00594C; }
.tag-preprint { background: rgba(239, 68, 111, 0.15); color: #C43A5C; }
.tag-talk { background: rgba(8, 48, 107, 0.15); color: #08306B; }
.tag-other { background: rgba(8, 48, 107, 0.15); color: #08306B; }
.tag-workshop { background: rgba(8, 48, 107, 0.15); color: #08306B; }
.tag-newrole { background: #DEEBF7; color: #2171B5; }

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
  <button class="news-filter-btn" data-filter="talk">Other Activities</button>
  <button class="news-filter-btn" data-filter="newrole">New Role</button>
</div>

<ul class="news-list" id="news-list">

<li data-filter="talk"><span class="news-date">Jul 2026</span><span><span class="news-tag tag-workshop">Workshop</span> <span style="color:#08306B">Mixed-Policy GRPO for Text-to-SQL with Off-Policy Data Generation.</span> <em>M. Sterbentz, M. Glass, <strong>N. H. Pham</strong>, D. Subramanian, K. J. Hammond.</em> Workshop on Structured Understanding, Retrieval, and Generation in the LLM Era (2026) - SURGeLLM 2026.</span></li>

<li data-filter="patent"><span class="news-date">Apr 2026</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">Generating Dynamic Few-Shot Examples for Enterprise Text-to-SQL Tasks</span> patent filed. <em>L. H. Vu, D. Snoddy, T. R. Kaple, T. R. Dinger, <strong>N. H. Pham</strong>, M. R. Glass, D. Subramanian, A. W. Hagleitner.</em></span></li>

<li data-filter="patent"><span class="news-date">Feb 2026</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">System and Method for Combining Data Selection and Reward Function for Tuning LLMs using Reinforcement Learning</span> patent granted. <em>L. Vu, <strong>N. H. Pham</strong>, D. Subramanian, T. Mummert.</em></span></li>

<li data-filter="award"><span class="news-date">Feb 2026</span><span><span class="news-tag tag-award">Award</span> Received the IBM Outstanding Technical Achievement Award for NL2Insights Impacting Products and Clients.</span></li>

<li data-filter="award"><span class="news-date">Feb 2026</span><span><span class="news-tag tag-milestone">Milestone</span> Multilingual Text2SQL capabilities are now available across all IBM Cloud and AWS production regions for IBM watsonx.data intelligence SaaS, supporting English and Japanese with more languages coming.</span></li>

<li data-filter="patent"><span class="news-date">Jan 2026</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">Site-wide optimization for mixed regression models and mixed control variables</span> patent granted. <em>D. T. Phan, <strong>N. H. Pham</strong>, L. M. Nguyen.</em></span></li>

<li data-filter="award"><span class="news-date">Dec 2025</span><span><span class="news-tag tag-award">Award</span> Received IBM Growth Award for advancing Text2SQL service within watsonx.data intelligence.</span></li>

<li data-filter="award"><span class="news-date">Dec 2025</span><span><span class="news-tag tag-award">Award</span> NL2Insights achieved Product and Client-0 Adoption &amp; Impact recognition in IBM Research Accomplishments 2025 (A-level), powering watsonx.data, BI Assistant, and Process Mining with 200,000+ SQL queries across 1,000+ databases.</span></li>

<li data-filter="patent"><span class="news-date">Aug 2025</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">Generating structured query language queries from natural language inputs with schema enrichment</span> patent filed. <em>M. Eyceoz, G. Rossiello, A. M. Gliozzo, M. R. Glass, N. Mihindukulasooriya, <strong>N. H. Pham</strong>, L. H. Vu, D. Subramanian, F. M. Chowdhury.</em></span></li>

<li data-filter="award"><span class="news-date">May 2025</span><span><span class="news-tag tag-award">Award</span> Received the IBM Outstanding Technical Achievement Award for achieving first place on the BIRD Leaderboard with IBM Granite Text-to-SQL models.</span></li>

<li data-filter="publication"><span class="news-date">May 2025</span><span><span class="news-tag tag-conference">Conference</span> Our paper <span style="color:#08306B">The Consistency Hypothesis in Uncertainty Quantification for Large Language Models</span> accepted at the Forty-First Conference on Uncertainty in Artificial Intelligence (UAI 2025). Q. Xiao, D. Bhattacharjya, B. Ganesan, R. Marinescu, K. Mirylenka, <strong>N. H. Pham</strong>, M. Glass, and J. Lee.</span></li>

<li data-filter="patent"><span class="news-date">Mar 2025</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">Database Querying Using Natural Language Processing</span> patent filed. <em>T. R. Dinger, A. M. Gliozzo, <strong>N. H. Pham</strong>, O. Hassanzadeh, D. Subramanian, L. Amini, G. Rossiello, M. F. M. Chowdhury, L. Vu, T. Kaple, M. Glass.</em></span></li>

<li data-filter="award"><span class="news-date">Dec 2024</span><span><span class="news-tag tag-award">Award</span> IBM Granite fine-tuned Text-to-SQL models swept top spots in the BIRD Leaderboard in IBM Research Accomplishments 2024 (A-level) &mdash; Granite-20B and Granite-34B took first place in both tracks, outperforming GPT-4 and GPT-4o. Featured at THINK'24 and deployed on BAM and watsonx.ai.</span></li>

<li data-filter="patent"><span class="news-date">Aug 2024</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">Fine-tuned generative model</span> patent filed. <em>E. Lobo, <strong>N. H. Pham</strong>, L. Vu, T. Mummert, and D. Subramanian.</em></span></li>

<li data-filter="newrole"><span class="news-date">Apr 2024</span><span><span class="news-tag tag-newrole">New Role</span> Promoted to <strong>Staff Research Scientist</strong> at <a href="https://research.ibm.com/" target="_blank">IBM</a> Thomas J. Watson Research Center.</span></li>

<li data-filter="patent"><span class="news-date">Jan 2024</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">Combining data selection and reward functions for tuning large language models using reinforcement learning</span> patent filed. <em>L. Vu, <strong>N. H. Pham</strong>, D. Subramanian, T. Mummert.</em></span></li>

<li data-filter="publication"><span class="news-date">Sep 2023</span><span><span class="news-tag tag-conference">Conference</span> Our paper <span style="color:#08306B">Evaluating Robustness of Cooperative MARL: A Model-based Approach</span> accepted at the 2023 IEEE International Conference on Data Mining (ICDM). <strong>N. H. Pham</strong>, L. M. Nguyen, J. Chen, H. T. Lam, S. Das, T. W. Weng. <a href="https://ieeexplore.ieee.org/document/10415752" target="_blank">[Paper]</a></span></li>

<li data-filter="patent"><span class="news-date">Jun 2023</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">Generative modeling and representational learning from multi-sequence alignment and phylogenetic tree data</span> patent filed. <em>T. L. Hoang, M. M. Galindo, G. Picco, M. Zayats, <strong>N. H. Pham</strong>, L. M. Nguyen, M. L. Sbodio, D. T. Phan, and V. L. Garcia.</em></span></li>

<li data-filter="patent"><span class="news-date">Jun 2023</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">A novel meta-hyperparameter tuning system for RL using sequence model</span> patent filed. <em>E. Lobo, <strong>N. H. Pham</strong>, D. Subramanian, and T. Pedapati.</em></span></li>

<li data-filter="patent"><span class="news-date">Jun 2023</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">Reinforcement machine learning with multi-level agent search and hyperparameter optimization</span> patent filed. <em>L. Vu, P. Kirchner, R. Marinescu, D. Subramanian, and <strong>N. H. Pham</strong>.</em></span></li>

<li data-filter="talk"><span class="news-date">Feb 2023</span><span><span class="news-tag tag-workshop">Workshop</span> Co-organizing a tutorial/lab forum <a href="https://aaai-23.aaai.org/aaai23tutorials/#lsha2" target="_blank">LSHA2: Automated AI for Decision Optimization with Reinforcement Learning</a> at AAAI 2023.</span></li>

<li data-filter="talk"><span class="news-date">Feb 2023</span><span><span class="news-tag tag-other">Other</span> Session Chair of <strong>ML: Optimization 1</strong> at <a href="https://aaai-23.aaai.org/" target="_blank">AAAI 2023</a> on Feb 10, 2023.</span></li>

<li data-filter="patent"><span class="news-date">Sep 2022</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">Adversarial Attacks for Improving Cooperative Multi-Agent Reinforcement Learning Systems</span> patent filed. <em><strong>N. H. Pham</strong>, L. M. Nguyen, J. Chen, T. L. Hoang, S. Das.</em></span></li>

<li data-filter="newrole"><span class="news-date">Jan 2022</span><span><span class="news-tag tag-newrole">New Role</span> Started new role as <strong>Research Scientist</strong> at <a href="https://research.ibm.com/" target="_blank">IBM</a> Thomas J. Watson Research Center, Yorktown Heights, NY.</span></li>

<li data-filter="newrole"><span class="news-date">Dec 2021</span><span><span class="news-tag tag-milestone">Milestone</span> Completed <strong>PhD in Operations Research</strong> in the Department of Statistics and Operations Research at University of North Carolina at Chapel Hill. <a href="https://cdr.lib.unc.edu/concern/dissertations/qb98mr30t?locale=en" target="_blank">Dissertation</a></span></li>

<li data-filter="publication"><span class="news-date">Sep 2021</span><span><span class="news-tag tag-conference">Conference</span> Our manuscript <span style="color:#08306B">FedDR &ndash; Randomized Douglas-Rachford Splitting Algorithms for Nonconvex Federated Composite Optimization</span> accepted at the 35th Conference on Neural Information Processing Systems. Q. Tran-Dinh, <strong>N. H. Pham</strong>, D. T. Phan, and L. M. Nguyen. <a href="https://arxiv.org/pdf/2103.03452.pdf" target="_blank">[Preprint]</a></span></li>

<li data-filter="newrole"><span class="news-date">Aug 2021</span><span><span class="news-tag tag-milestone">Milestone</span> Finished summer internship at <a href="https://www.bluerivertechnology.com/" target="_blank">Blue River Technology</a>. Mentored by Ben Cline, supervised by Chris Padwick.</span></li>

<li data-filter="publication"><span class="news-date">Jun 2021</span><span><span class="news-tag tag-preprint">Preprint</span> Completed the manuscript <span style="color:#08306B">FedDR &ndash; Randomized Douglas-Rachford Splitting Algorithms for Nonconvex Federated Composite Optimization</span>. Q. Tran-Dinh, <strong>N. H. Pham</strong>, D. T. Phan, and L. M. Nguyen. <a href="https://arxiv.org/pdf/2103.03452.pdf" target="_blank">[Preprint]</a></span></li>

<li data-filter="patent"><span class="news-date">May 2021</span><span><span class="news-tag tag-patent">Patent</span> <span style="color:#08306B">Site-Wide Optimization for Mixed Regression Models and Mixed Control Variables</span> patent filed. <em>D. T. Phan, <strong>N. H. Pham</strong>, L. M. Nguyen.</em></span></li>

<li data-filter="newrole"><span class="news-date">May 2021</span><span><span class="news-tag tag-newrole">New Role</span> Joined <a href="https://www.bluerivertechnology.com/" target="_blank">Blue River Technology</a> as Machine Learning Intern.</span></li>

<li data-filter="publication"><span class="news-date">Mar 2021</span><span><span class="news-tag tag-preprint">Preprint</span> Completed the manuscript <span style="color:#08306B">Federated Learning with Randomized Douglas-Rachford Splitting Methods</span>. Q. Tran-Dinh, <strong>N. H. Pham</strong>, D. T. Phan, and L. M. Nguyen. <a href="https://arxiv.org/pdf/2103.03452v1.pdf" target="_blank">[Preprint]</a></span></li>

<li data-filter="publication"><span class="news-date">Jan 2021</span><span><span class="news-tag tag-conference">Conference</span> Our paper <span style="color:#08306B">Regression Optimization for System-level Production Control</span> accepted to the 2021 American Control Conference (ACC). D. T. Phan, L. M. Nguyen, P. Murali, <strong>N. H. Pham</strong>, H. Liu, J. Kalagnanam. <a href="https://ieeexplore.ieee.org/document/9482638" target="_blank">[Full paper]</a></span></li>

<li data-filter="publication"><span class="news-date">Oct 2020</span><span><span class="news-tag tag-journal">Journal</span> Our paper <span style="color:#08306B">A Hybrid Stochastic Optimization Framework for Stochastic Composite Nonconvex Optimization</span> accepted for publication at <strong>Mathematical Programming</strong>. Q. Tran-Dinh, <strong>N. H. Pham</strong>, D. T. Phan, and L. M. Nguyen. <a href="https://link.springer.com/article/10.1007/s10107-020-01583-1" target="_blank">[Full paper]</a></span></li>

<li data-filter="newrole"><span class="news-date">Aug 2020</span><span><span class="news-tag tag-milestone">Milestone</span> Finished summer internship at <a href="https://research.ibm.com/" target="_blank">IBM Research</a>. Mentored by Dzung T. Phan and Lam M. Nguyen, and supervised by Roman Vaculin.</span></li>

<li data-filter="publication"><span class="news-date">Jun 2020</span><span><span class="news-tag tag-conference">Conference</span> Our paper <span style="color:#08306B">Stochastic Gauss-Newton Algorithms for Nonconvex Compositional Optimization</span> accepted for publication at the International Conference on Machine Learning (ICML). Q. Tran-Dinh, <strong>N. H. Pham</strong>, and L. M. Nguyen. <a href="http://proceedings.mlr.press/v119/tran-dinh20a.html" target="_blank">[Full paper]</a></span></li>

<li data-filter="newrole"><span class="news-date">May 2020</span><span><span class="news-tag tag-newrole">New Role</span> Joined <a href="https://research.ibm.com/" target="_blank">IBM Research</a> as Research Intern.</span></li>

<li data-filter="publication"><span class="news-date">May 2020</span><span><span class="news-tag tag-journal">Journal</span> Our paper <span style="color:#08306B">ProxSARAH: An Efficient Algorithmic Framework For Stochastic Composite Nonconvex Optimization</span> accepted for publication at the Journal of Machine Learning Research (JMLR). <strong>N. H. Pham</strong>, L. M. Nguyen, D. T. Phan, and Q. Tran-Dinh. <a href="http://proceedings.mlr.press/v119/tran-dinh20a.html" target="_blank">[Full paper]</a></span></li>

<li data-filter="publication"><span class="news-date">Feb 2020</span><span><span class="news-tag tag-preprint">Preprint</span> Completed the manuscript <span style="color:#08306B">Stochastic Gauss-Newton Algorithms for Nonconvex Compositional Optimization</span>. Q. Tran-Dinh, <strong>N. H. Pham</strong>, and L. M. Nguyen. <a href="https://arxiv.org/pdf/2002.07290.pdf" target="_blank">[Preprint]</a></span></li>

<li data-filter="publication"><span class="news-date">Feb 2020</span><span><span class="news-tag tag-preprint">Preprint</span> Manuscript <span style="color:#08306B">Convergence Rates of Accelerated Markov Gradient Descent with Applications in Reinforcement Learning</span> released. T. T. Doan, L. M. Nguyen, <strong>N. H. Pham</strong>, and J. Romberg. <a href="https://arxiv.org/pdf/2103.03452v1.pdf" target="_blank">[Preprint]</a></span></li>

<li data-filter="publication"><span class="news-date">Jan 2020</span><span><span class="news-tag tag-journal">Journal</span> Our manuscript <span style="color:#08306B">ProxSARAH: An Efficient Algorithmic Framework For Stochastic Composite Nonconvex Optimization</span> accepted for publication at the Journal of Machine Learning Research (JMLR) with minor revision. <strong>N. H. Pham</strong>, L. M. Nguyen, D. T. Phan, and Q. Tran-Dinh. <a href="https://arxiv.org/pdf/1902.05679.pdf" target="_blank">[Preprint]</a></span></li>

<li data-filter="publication"><span class="news-date">Jan 2020</span><span><span class="news-tag tag-conference">Conference</span> Our paper <span style="color:#08306B">A Hybrid Stochastic Policy Gradient Algorithm for Reinforcement Learning</span> accepted for AISTATS 2020. <strong>N. H. Pham</strong>, L. M. Nguyen, D. T. Phan, P. H. Nguyen, M. van Dijk, and Q. Tran-Dinh. <a href="http://proceedings.mlr.press/v108/pham20a.html" target="_blank">[Full paper]</a></span></li>

<li data-filter="talk"><span class="news-date">Oct 2019</span><span><span class="news-tag tag-talk">Talk</span> <span style="color:#08306B">ProxSARAH: An Efficient Algorithmic Framework For Stochastic Composite Nonconvex Optimization</span>. Oral Presentation: 2019 INFORMS Annual Meeting.</span></li>

<li data-filter="award"><span class="news-date">Aug 2019</span><span><span class="news-tag tag-award">Award</span> Worked with Quoc Tran-Dinh as a SAMSI (The Statistical and Applied Mathematical Sciences Institute) Research Fellow for the 2019 Fall Program on Deep Learning.</span></li>

<li data-filter="publication"><span class="news-date">Jul 2019</span><span><span class="news-tag tag-preprint">Preprint</span> Completed the manuscript <span style="color:#08306B">A Hybrid Stochastic Optimization Framework for Composite Nonconvex Optimization</span>. Q. Tran-Dinh, <strong>N. H. Pham</strong>, D. T. Phan, and L. M. Nguyen. <a href="https://nhanph.github.io/research/" target="_blank">Research page</a>.</span></li>

<li data-filter="publication"><span class="news-date">Feb 2019</span><span><span class="news-tag tag-preprint">Preprint</span> Completed the manuscript <span style="color:#08306B">ProxSARAH: An Efficient Algorithmic Framework For Stochastic Composite Nonconvex Optimization</span>. <strong>N. H. Pham</strong>, L. M. Nguyen, D. T. Phan, and Q. Tran-Dinh. <a href="https://nhanph.github.io/research/" target="_blank">Research page</a>.</span></li>

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
