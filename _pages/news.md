---
permalink: /news/
title: "News"
author_profile: false
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
}
.news-list li {
  display: flex;
  gap: 16px;
  padding: 11px 0;
  border-bottom: 1px solid rgba(8, 48, 107, 0.08);
  font-size: 0.95rem;
  color: #536878;
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
  font-size: 0.8rem;
  padding-top: 1px;
}
.news-tag {
  display: inline-block;
  font-size: 0.7rem;
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
.tag-patent-granted { background: rgba(239, 68, 111, 0.15); color: #C43A5C; }
.tag-award { background: rgba(255, 209, 0, 0.2); color: #9A7800; }
.tag-milestone { background: #9ecae1; color: #191970; }
.tag-journal { background: rgba(66, 146, 198, 0.2); color: #2A6F97; }
.tag-conference { background: #0067BC; color: #F0F8FF; }
.tag-preprint { background: rgba(8, 81, 156, 0.15); color: #08519C; }
.tag-talk { background: rgba(8, 48, 107, 0.15); color: #08306B; }
.tag-other { background: rgba(8, 48, 107, 0.15); color: #08306B; }
.tag-workshop { background: rgba(8, 48, 107, 0.15); color: #08306B; }
.tag-tutorial { background: rgba(8, 48, 107, 0.15); color: #08306B; }
.tag-demo { background: rgba(8, 48, 107, 0.15); color: #08306B; }
.tag-newrole { background: #DEEBF7; color: #2171B5; }

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
  <button class="news-filter-btn" data-filter="award">Award</button>
  <button class="news-filter-btn" data-filter="patent">Patent</button>
  <button class="news-filter-btn" data-filter="publication">Publication</button>
  <button class="news-filter-btn" data-filter="talk">Other Activities</button>
  <button class="news-filter-btn" data-filter="newrole">Career Update</button>
</div>

<ul class="news-list" id="news-list">

<li data-filter="publication"><span class="news-date">Jul 2026</span><span><span class="news-tag tag-workshop">Workshop</span> <a href="https://aclanthology.org/2026.surgellm-1.20/" target="_blank" style="color:#08306B">Mixed-Policy GRPO for Text-to-SQL with Off-Policy Data Generation</a> <em>accepted for Workshop on Structured Understanding, Retrieval, and Generation in the LLM Era (<strong>SURGeLLM 2026</strong>).</em><br>M. Sterbentz, M. Glass, <strong>N. H. Pham</strong>, D. Subramanian, K. J. Hammond</span></li>

<li data-filter="talk"><span class="news-date">Jun 2026</span><span><span class="news-tag tag-demo">Demo</span> <a href="https://research.ibm.com/publications/text-to-sql-evaluation-toolkit" target="_blank" style="color:#08306B">Text-to-SQL Evaluation Toolkit</a> <em>accepted for 52nd International Conference on Very Large Data Bases (<strong><a href="https://vldb.org/2026/demonstrations.html" target="_blank">VLDB 2026 Demo Track</a></strong>).</em><br>Oktie Hassanzadeh (IBM)*; Yotam Perlitz (IBM); <strong>Nhan Pham</strong> (IBM); Tanvi Kaple (IBM); Karolina Źróbek (IBM); Long Vu (IBM); Michael Glass (IBM); Dharmashankar Subramanian (IBM); Mohammadreza Pourreza (University of Alberta); Davood Rafiei (University of Alberta)</span></li>

<li data-filter="patent"><span class="news-date">Apr 2026</span><span><span class="news-tag tag-patent">Patent Application</span> <span style="color:#08306B">Generating Dynamic Few-Shot Examples for Enterprise Text-to-SQL Tasks</span><br>L. H. Vu, D. Snoddy, T. R. Kaple, T. R. Dinger, <strong>N. H. Pham</strong>, M. R. Glass, D. Subramanian, A. W. Hagleitner.</span></li>

<li data-filter="patent"><span class="news-date">Feb 2026</span><span><span class="news-tag tag-patent-granted">Patent Granted</span> <a href="https://patents.google.com/patent/US12566929/en" target="_blank" style="color:#08306B">System and Method for Combining Data Selection and Reward Function for Tuning LLMs using Reinforcement Learning</a>. Patent US12566929B2.<br>L. Vu, <strong>N. H. Pham</strong>, D. Subramanian, T. Mummert.</span></li>

<li data-filter="award"><span class="news-date">Feb 2026</span><span><span class="news-tag tag-award">Award</span> Received <strong>IBM Outstanding Technical Achievement Award</strong> for NL2Insights Impacting Products and Clients.</span></li>

<li data-filter="award"><span class="news-date">Feb 2026</span><span><span class="news-tag tag-milestone">Milestone</span> Multilingual Text2SQL capabilities are now available across all IBM Cloud and AWS production regions for IBM watsonx.data intelligence SaaS, supporting English and Japanese with more languages coming.</span></li>

<li data-filter="patent"><span class="news-date">Jan 2026</span><span><span class="news-tag tag-patent-granted">Patent Granted</span> <a href="https://patents.google.com/patent/US12518174/en" target="_blank" style="color:#08306B">Site-wide optimization for mixed regression models and mixed control variables</a>. Patent US12518174B2.<br>D. T. Phan, <strong>N. H. Pham</strong>, L. M. Nguyen.</span></li>

<li data-filter="publication"><span class="news-date">Jan 2026</span><span><span class="news-tag tag-workshop">Workshop</span> <a href="https://openreview.net/forum?id=jfq9DUrW90#discussion" target="_blank" style="color:#08306B">Black-Box Uncertainty Quantification for Large Language Models via Ensemble-of-Ensembles</a> <em>accepted for AAAI 2026 Workshop on Assessing and Improving Reliability of Foundation Models in the Real World (<strong>AAAI 2026 Workshop</strong>).</em><br>W. Ma, D. Bhattacharjya, J. Lee, <strong>N. H. Pham</strong>, H. Kokel, Q. Ji</span></li>

<li data-filter="award"><span class="news-date">Dec 2025</span><span><span class="news-tag tag-award">Award</span> Received <strong>IBM Growth Award</strong> for advancing Text2SQL service within watsonx.data intelligence.</span></li>

<li data-filter="award"><span class="news-date">Dec 2025</span><span><span class="news-tag tag-award">Award</span> <strong>IBM Research Accomplishments 2025 - A-level</strong>: NL2Insights achieved Product and Client-0 Adoption &amp; Impact recognition. Our fully automated Text2SQL pipeline now powers watsonx.data, BI Assistant, and Process Mining, generating over 200,000 SQL queries across 1,000+ databases at enterprise scale.</span></li>

<li data-filter="patent"><span class="news-date">Aug 2025</span><span><span class="news-tag tag-patent">Patent Application</span> <span style="color:#08306B">Generating structured query language queries from natural language inputs with schema enrichment</span><br>M. Eyceoz, G. Rossiello, A. M. Gliozzo, M. R. Glass, N. Mihindukulasooriya, <strong>N. H. Pham</strong>, L. H. Vu, D. Subramanian, F. M. Chowdhury.</span></li>

<li data-filter="award"><span class="news-date">May 2025</span><span><span class="news-tag tag-award">Award</span> Received <strong>IBM Outstanding Technical Achievement Award</strong> for achieving first place on the BIRD Leaderboard with IBM Granite Text-to-SQL models.</span></li>

<li data-filter="publication"><span class="news-date">May 2025</span><span><span class="news-tag tag-conference">Conference</span> <a href="https://proceedings.mlr.press/v286/xiao25a.html" target="_blank" style="color:#08306B">The Consistency Hypothesis in Uncertainty Quantification for Large Language Models</a> <em>accepted for Forty-First Conference on Uncertainty in Artificial Intelligence (<strong>UAI 2025</strong>).</em><br>Q. Xiao, D. Bhattacharjya, B. Ganesan, R. Marinescu, K. Mirylenka, <strong>N. H. Pham</strong>, M. Glass, and J. Lee</span></li>

<li data-filter="patent"><span class="news-date">Mar 2025</span><span><span class="news-tag tag-patent">Patent Application</span> <span style="color:#08306B">Database Querying Using Natural Language Processing</span><br>T. R. Dinger, A. M. Gliozzo, <strong>N. H. Pham</strong>, O. Hassanzadeh, D. Subramanian, L. Amini, G. Rossiello, M. F. M. Chowdhury, L. Vu, T. Kaple, M. Glass.</span></li>

<li data-filter="award"><span class="news-date">Dec 2024</span><span><span class="news-tag tag-award">Award</span> <strong>IBM Research Accomplishments 2024 - A-level</strong>: IBM Granite fine-tuned Text-to-SQL models sweep top spots in BIRD Leaderboard. Our Granite-20B and Granite-34B models achieved first place in both tracks, outperforming larger models like GPT-4 and GPT-4o. This success drove renewed interest from major industry players including Google, Alibaba, and ByteDance. Models were featured at THINK'24 and deployed on BAM and Watsonx.ai platforms.</span></li>

<li data-filter="patent"><span class="news-date">Aug 2024</span><span><span class="news-tag tag-patent">Patent Application</span> <span style="color:#08306B">Fine-tuned generative model</span><br>E. Lobo, <strong>N. H. Pham</strong>, L. Vu, T. Mummert, and D. Subramanian.</span></li>

<li data-filter="award"><span class="news-date">Jul 2024</span><span><span class="news-tag tag-milestone">Milestone</span> <a href="https://research.ibm.com/blog/granite-LLM-text-to-SQL?mhsrc=ibmsearch_a&amp;mhq=%20IBM%20Granite%20fine-tuned%20Text-to-SQL" target="_blank">IBM&rsquo;s text-to-SQL generator</a> takes top place on a benchmark for handling complex database queries.</span></li>

<li data-filter="newrole"><span class="news-date">Apr 2024</span><span><span class="news-tag tag-newrole">Career Update</span> Promoted to <strong>Staff Research Scientist</strong> at <a href="https://research.ibm.com/" target="_blank">IBM</a> Thomas J. Watson Research Center.</span></li>

<li data-filter="patent"><span class="news-date">Jan 2024</span><span><span class="news-tag tag-patent">Patent Application</span> <span style="color:#08306B">Combining data selection and reward functions for tuning large language models using reinforcement learning</span><br>L. Vu, <strong>N. H. Pham</strong>, D. Subramanian, T. Mummert.</span></li>

<li data-filter="publication"><span class="news-date">Sep 2023</span><span><span class="news-tag tag-conference">Conference</span> <a href="https://ieeexplore.ieee.org/document/10415752" target="_blank" style="color:#08306B">Evaluating Robustness of Cooperative MARL: A Model-based Approach</a> <em>accepted for 2023 IEEE International Conference on Data Mining (<strong>ICDM</strong>).</em><br><strong>N. H. Pham</strong>, L. M. Nguyen, J. Chen, H. T. Lam, S. Das, T. W. Weng</span></li>

<li data-filter="award"><span class="news-date">Aug 2023</span><span><span class="news-tag tag-award">Award</span> Received <strong>IBM 2022 Research Pat Goldberg Memorial Best Paper</strong>: <span style="color:#08306B">A Hybrid Stochastic Optimization Framework for Stochastic Composite Nonconvex Optimization</span>.<br>Q. Tran-Dinh, <strong>N. H. Pham</strong>, D. T. Phan, and L. M. Nguyen.</span></li>

<li data-filter="patent"><span class="news-date">Jun 2023</span><span><span class="news-tag tag-patent">Patent Application</span> <span style="color:#08306B">Generative modeling and representational learning from multi-sequence alignment and phylogenetic tree data</span><br>T. L. Hoang, M. M. Galindo, G. Picco, M. Zayats, <strong>N. H. Pham</strong>, L. M. Nguyen, M. L. Sbodio, D. T. Phan, and V. L. Garcia.</span></li>

<li data-filter="patent"><span class="news-date">Jun 2023</span><span><span class="news-tag tag-patent">Patent Application</span> <span style="color:#08306B">A novel meta-hyperparameter tuning system for RL using sequence model</span><br>E. Lobo, <strong>N. H. Pham</strong>, D. Subramanian, and T. Pedapati.</span></li>

<li data-filter="patent"><span class="news-date">Jun 2023</span><span><span class="news-tag tag-patent">Patent Application</span> <span style="color:#08306B">Reinforcement machine learning with multi-level agent search and hyperparameter optimization</span><br>L. Vu, P. Kirchner, R. Marinescu, D. Subramanian, and <strong>N. H. Pham</strong>.</span></li>

<li data-filter="talk"><span class="news-date">Feb 2023</span><span><span class="news-tag tag-tutorial">Tutorial</span> <a href="https://aaai-23.aaai.org/aaai23tutorials/#lsha2" target="_blank" style="color:#08306B">Automated AI For Decision Optimization with Reinforcement Learning</a>. AAAI 2023 Tutorial and Lab Organizer.</span></li>

<li data-filter="talk"><span class="news-date">Feb 2023</span><span><span class="news-tag tag-other">Other</span> Session Chair of <strong>ML: Optimization 1</strong> at <a href="https://aaai-23.aaai.org/" target="_blank">AAAI 2023</a> on Feb 10, 2023.</span></li>

<li data-filter="patent"><span class="news-date">Sep 2022</span><span><span class="news-tag tag-patent">Patent Application</span> <span style="color:#08306B">Adversarial Attacks for Improving Cooperative Multi-Agent Reinforcement Learning Systems</span><br><strong>N. H. Pham</strong>, L. M. Nguyen, J. Chen, T. L. Hoang, S. Das.</span></li>

<li data-filter="newrole"><span class="news-date">Jan 2022</span><span><span class="news-tag tag-newrole">Career Update</span> Started new role as <strong>Research Scientist</strong> at <a href="https://research.ibm.com/" target="_blank">IBM</a> Thomas J. Watson Research Center &middot; Yorktown Heights, NY.</span></li>

<li data-filter="newrole"><span class="news-date">Dec 2021</span><span><span class="news-tag tag-milestone">Milestone</span> Completed <strong>PhD in Operations Research</strong> in the Department of Statistics and Operations Research at University of North Carolina at Chapel Hill. <a href="https://cdr.lib.unc.edu/concern/dissertations/qb98mr30t?locale=en" target="_blank">Dissertation</a></span></li>

<li data-filter="publication"><span class="news-date">Sep 2021</span><span><span class="news-tag tag-conference">Conference</span> <a href="https://arxiv.org/pdf/2103.03452.pdf" target="_blank" style="color:#08306B">FedDR &ndash; Randomized Douglas-Rachford Splitting Algorithms for Nonconvex Federated Composite Optimization</a> <em>accepted for the 35th Conference on Neural Information Processing Systems (<strong>NeurIPS 2021</strong>).</em><br>Q. Tran-Dinh, <strong>N. H. Pham</strong>, D. T. Phan, and L. M. Nguyen</span></li>

<li data-filter="newrole"><span class="news-date">Aug 2021</span><span><span class="news-tag tag-milestone">Milestone</span> Finished summer internship at <a href="https://www.bluerivertechnology.com/" target="_blank">Blue River Technology</a>. Mentored by Ben Cline, supervised by Chris Padwick.</span></li>

<li data-filter="talk"><span class="news-date">Jul 2021</span><span><span class="news-tag tag-talk">Talk</span> <span style="color:#08306B">Stochastic Recursive Gradient Algorithms for Stochastic Composite Nonconvex Optimization and Policy Optimization</span>. MIT-IBM Guest Seminar.</span></li>

<li data-filter="publication"><span class="news-date">Jun 2021</span><span><span class="news-tag tag-preprint">Preprint</span> <a href="https://arxiv.org/pdf/2103.03452.pdf" target="_blank" style="color:#08306B">FedDR &ndash; Randomized Douglas-Rachford Splitting Algorithms for Nonconvex Federated Composite Optimization</a>.<br>Q. Tran-Dinh, <strong>N. H. Pham</strong>, D. T. Phan, and L. M. Nguyen</span></li>

<li data-filter="patent"><span class="news-date">May 2021</span><span><span class="news-tag tag-patent">Patent Application</span> <span style="color:#08306B">Site-Wide Optimization for Mixed Regression Models and Mixed Control Variables</span><br>D. T. Phan, <strong>N. H. Pham</strong>, L. M. Nguyen.</span></li>

<li data-filter="newrole"><span class="news-date">May 2021</span><span><span class="news-tag tag-newrole">Career Update</span> Joined <a href="https://www.bluerivertechnology.com/" target="_blank">Blue River Technology</a> as Machine Learning Intern.</span></li>

<li data-filter="publication"><span class="news-date">Mar 2021</span><span><span class="news-tag tag-preprint">Preprint</span> <a href="https://arxiv.org/pdf/2103.03452v1.pdf" target="_blank" style="color:#08306B">Federated Learning with Randomized Douglas-Rachford Splitting Methods</a>.<br>Q. Tran-Dinh, <strong>N. H. Pham</strong>, D. T. Phan, and L. M. Nguyen</span></li>

<li data-filter="publication"><span class="news-date">Jan 2021</span><span><span class="news-tag tag-conference">Conference</span> <a href="https://ieeexplore.ieee.org/document/9482638" target="_blank" style="color:#08306B">Regression Optimization for System-level Production Control</a> <em>accepted for 2021 American Control Conference (<strong>ACC</strong>).</em><br>D. T. Phan, L. M. Nguyen, P. Murali, <strong>N. H. Pham</strong>, H. Liu, J. Kalagnanam</span></li>

<li data-filter="talk"><span class="news-date">Nov 2020</span><span><span class="news-tag tag-talk">Talk</span> <span style="color:#08306B">A Hybrid Stochastic Policy Gradient Algorithm for Reinforcement Learning</span>. Oral Presentation: INFORMS Annual Meeting 2020.</span></li>

<li data-filter="publication"><span class="news-date">Oct 2020</span><span><span class="news-tag tag-journal">Journal</span> <a href="https://link.springer.com/article/10.1007/s10107-020-01583-1" target="_blank" style="color:#08306B">A Hybrid Stochastic Optimization Framework for Stochastic Composite Nonconvex Optimization</a> <em>accepted for Mathematical Programming (<strong>Math. Program</strong>).</em><br>Q. Tran-Dinh, <strong>N. H. Pham</strong>, D. T. Phan, and L. M. Nguyen</span></li>

<li data-filter="newrole"><span class="news-date">Aug 2020</span><span><span class="news-tag tag-milestone">Milestone</span> Finished summer internship at <a href="https://research.ibm.com/" target="_blank">IBM Research</a>. Mentored by Dzung T. Phan and Lam M. Nguyen, and supervised by Roman Vaculin.</span></li>

<li data-filter="publication"><span class="news-date">Jun 2020</span><span><span class="news-tag tag-conference">Conference</span> <a href="http://proceedings.mlr.press/v119/tran-dinh20a.html" target="_blank" style="color:#08306B">Stochastic Gauss-Newton Algorithms for Nonconvex Compositional Optimization</a> <em>accepted for the 37th International Conference on Machine Learning (<strong>ICML 2020</strong>).</em><br>Q. Tran-Dinh, <strong>N. H. Pham</strong>, and L. M. Nguyen</span></li>

<li data-filter="newrole"><span class="news-date">May 2020</span><span><span class="news-tag tag-newrole">Career Update</span> Joined <a href="https://research.ibm.com/" target="_blank">IBM Research</a> as Research Intern.</span></li>

<li data-filter="publication"><span class="news-date">May 2020</span><span><span class="news-tag tag-journal">Journal</span> <a href="https://www.jmlr.org/papers/v21/19-248.html" target="_blank" style="color:#08306B">ProxSARAH: An Efficient Algorithmic Framework For Stochastic Composite Nonconvex Optimization</a> <em>accepted for Journal of Machine Learning Research (<strong>JMLR</strong>).</em><br><strong>N. H. Pham</strong>, L. M. Nguyen, D. T. Phan, and Q. Tran-Dinh</span></li>

<li data-filter="publication"><span class="news-date">Mar 2020</span><span><span class="news-tag tag-preprint">Preprint</span> <a href="https://arxiv.org/abs/2003.10973" target="_blank" style="color:#08306B">Finite-time analysis of stochastic gradient descent under markov randomness</a>.<br>T. T. Doan, L. M. Nguyen, <strong>N. H. Pham</strong>, and J. Romberg</span></li>

<li data-filter="publication"><span class="news-date">Feb 2020</span><span><span class="news-tag tag-preprint">Preprint</span> <a href="https://arxiv.org/pdf/2002.07290.pdf" target="_blank" style="color:#08306B">Stochastic Gauss-Newton Algorithms for Nonconvex Compositional Optimization</a>.<br>Q. Tran-Dinh, <strong>N. H. Pham</strong>, and L. M. Nguyen</span></li>

<li data-filter="publication"><span class="news-date">Feb 2020</span><span><span class="news-tag tag-preprint">Preprint</span> <a href="https://arxiv.org/pdf/2103.03452v1.pdf" target="_blank" style="color:#08306B">Convergence Rates of Accelerated Markov Gradient Descent with Applications in Reinforcement Learning</a>.<br>T. T. Doan, L. M. Nguyen, <strong>N. H. Pham</strong>, and J. Romberg</span></li>

<li data-filter="publication"><span class="news-date">Jan 2020</span><span><span class="news-tag tag-journal">Journal</span> <a href="https://arxiv.org/pdf/1902.05679.pdf" target="_blank" style="color:#08306B">ProxSARAH: An Efficient Algorithmic Framework For Stochastic Composite Nonconvex Optimization</a> <em>accepted for Journal of Machine Learning Research (<strong>JMLR</strong>).</em><br><strong>N. H. Pham</strong>, L. M. Nguyen, D. T. Phan, and Q. Tran-Dinh</span></li>

<li data-filter="publication"><span class="news-date">Jan 2020</span><span><span class="news-tag tag-conference">Conference</span> <a href="http://proceedings.mlr.press/v108/pham20a.html" target="_blank" style="color:#08306B">A Hybrid Stochastic Policy Gradient Algorithm for Reinforcement Learning</a> <em>accepted for the 23rd International Conference on Artificial Intelligence and Statistics (<strong>AISTATS 2020</strong>).</em><br><strong>N. H. Pham</strong>, L. M. Nguyen, D. T. Phan, P. H. Nguyen, M. van Dijk, and Q. Tran-Dinh</span></li>

<li data-filter="talk"><span class="news-date">Oct 2019</span><span><span class="news-tag tag-talk">Talk</span> <span style="color:#08306B">ProxSARAH: An Efficient Algorithmic Framework For Stochastic Composite Nonconvex Optimization</span>. Oral Presentation: INFORMS Annual Meeting 2019.</span></li>

<li data-filter="publication"><span class="news-date">Jul 2019</span><span><span class="news-tag tag-preprint">Preprint</span> <a href="https://arxiv.org/abs/1907.03793" target="_blank" style="color:#08306B">A Hybrid Stochastic Optimization Framework for Composite Nonconvex Optimization</a>.<br>Q. Tran-Dinh, <strong>N. H. Pham</strong>, D. T. Phan, and L. M. Nguyen</span></li>

<li data-filter="publication"><span class="news-date">Feb 2019</span><span><span class="news-tag tag-preprint">Preprint</span> <a href="https://arxiv.org/pdf/1902.05679.pdf" target="_blank" style="color:#08306B">ProxSARAH: An Efficient Algorithmic Framework For Stochastic Composite Nonconvex Optimization</a>.<br><strong>N. H. Pham</strong>, L. M. Nguyen, D. T. Phan, and Q. Tran-Dinh</span></li>

<li data-filter="newrole"><span class="news-date">Aug 2017</span><span><span class="news-tag tag-newrole">Career Update</span> Started PhD in Operations Research at University of North Carolina at Chapel Hill &middot; Chapel Hill, NC. Under supervision of professor <a href="https://quoctd.web.unc.edu/" target="_blank">Quoc Tran-Dinh</a>.</span></li>

</ul>

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
})();
</script>
