---
permalink: /
title: "Bio"
excerpt: "Bio"
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<style>
.bio-tab-bar {
  display: flex;
  gap: 6px;
  margin-bottom: 18px;
  flex-wrap: wrap;
}
.bio-tab-btn {
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
.bio-tab-btn:hover {
  border-color: #08306B;
  color: #08306B;
}
.bio-tab-btn.active {
  background: #08306B;
  border-color: #08306B;
  color: #fff;
}

.bio-panel {
  display: none;
}
.bio-panel.active {
  display: block;
}
.bio-panel h2 {
  margin-bottom: 0.25em;
}

.bio-body {
  display: flex;
  gap: 16px;
  margin-bottom: 1em;
}
.bio-date {
  flex-shrink: 0;
  width: 90px;
  color: #536878;
  font-weight: 600;
  font-size: 0.8rem;
  padding-top: 1px;
}
.bio-desc {
  flex: 1;
  min-width: 0;
}
.bio-desc p:first-child {
  margin-top: 0;
}

@media (max-width: 700px) {
  .bio-body {
    flex-direction: column;
    gap: 4px;
  }
  .bio-date {
    width: auto;
  }
}
</style>

I am a Staff Research Scientist at the IBM Thomas J. Watson Research Center in Yorktown Heights, NY. I finished my PhD in Operations Research in the Department of Statistics and Operations Research at University of North Carolina at Chapel Hill in 2021 under supervision by Dr. Quoc Tran-Dinh.

<div class="bio-tab-bar" id="bio-tab-bar">
  <button class="bio-tab-btn active" data-tab="education">Education</button>
  <button class="bio-tab-btn" data-tab="research">Current Research</button>
  <button class="bio-tab-btn" data-tab="achievements">Recent Achievements</button>
  <button class="bio-tab-btn" data-tab="skills">Skills & Technologies</button>
</div>

<div class="bio-panel active" data-tab="education" markdown="1">

<div class="bio-body">
<div class="bio-date">2017 – 2021</div>
<div class="bio-desc" markdown="1">

**Ph.D. in Operations Research**<br>
Department of Statistics and Operations Research<br>
University of North Carolina at Chapel Hill &middot; Chapel Hill, NC, USA

</div>
</div>

<div class="bio-body">
<div class="bio-date">2015 – 2017</div>
<div class="bio-desc" markdown="1">

**Graduate Study in Computer Engineering**<br>
Department of Computer Science and Engineering<br>
University of Nevada, Reno &middot; Reno, NV, USA

</div>
</div>

<div class="bio-body">
<div class="bio-date">2008 – 2013</div>
<div class="bio-desc" markdown="1">

**Bachelor of Engineering (Honor Program) in Computer Engineering**<br>
Department of Computer Science and Engineering<br>
Ho Chi Minh City University of Technology &middot; Ho Chi Minh City, Vietnam

</div>
</div>

</div>

<div class="bio-panel" data-tab="research" markdown="1">

My current research focuses on **Large Language Models (LLMs) for enterprise data management applications**, particularly building end-to-end Text-to-SQL systems. I lead the development of NL2Insights, an automated pipeline that powers flagship IBM products including watsonx.data intelligence, BI Assistant, and Process Mining. Our system has generated over **200,000 SQL queries across 1,000+ databases** at enterprise scale.

I also continue research on stochastic optimization methods for machine learning, deep learning, and reinforcement learning.

</div>

<div class="bio-panel" data-tab="achievements" markdown="1">

<div class="bio-body">
<div class="bio-date">2026</div>
<div class="bio-desc" markdown="1">

**IBM Outstanding Technical Achievement Award**: For NL2Insights Impacting Products and Clients

</div>
</div>

<div class="bio-body">
<div class="bio-date">2026</div>
<div class="bio-desc" markdown="1">

**Production Impact**: Enabled multilingual Text2SQL capabilities across all IBM Cloud and AWS regions

</div>
</div>

<div class="bio-body">
<div class="bio-date">2025</div>
<div class="bio-desc" markdown="1">

**IBM Growth Award**: For advancing Text2SQL service within watsonx.data intelligence

</div>
</div>

<div class="bio-body">
<div class="bio-date">2025</div>
<div class="bio-desc" markdown="1">

**IBM Outstanding Technical Achievement Award**: For achieving first place on the BIRD leaderboard

</div>
</div>

<div class="bio-body">
<div class="bio-date">2024-2025</div>
<div class="bio-desc" markdown="1">

**Multiple IBM Research Accomplishments**: For NL2Insights product adoption and BIRD leaderboard success

</div>
</div>

<div class="bio-body">
<div class="bio-date">2024</div>
<div class="bio-desc" markdown="1">

**#1 on BIRD Leaderboard**: Led IBM Granite Text-to-SQL models to first place in both tracks of the prestigious BIRD benchmark, outperforming larger models like GPT-4 and GPT-4o

</div>
</div>

</div>

<div class="bio-panel" data-tab="skills" markdown="1">

<div class="bio-body">
<div class="bio-date">Large Language Models</div>
<div class="bio-desc" markdown="1">

Fine-tuning, prompt engineering, reasoning systems, RAG (Retrieval-Augmented Generation)

</div>
</div>

<div class="bio-body">
<div class="bio-date">Programming</div>
<div class="bio-desc" markdown="1">

Python, TensorFlow, Keras, PyTorch, Scikit-learn, C/C++, MATLAB

</div>
</div>

<div class="bio-body">
<div class="bio-date">ML/AI</div>
<div class="bio-desc" markdown="1">

Deep learning, reinforcement learning, federated learning, optimization algorithms

</div>
</div>

<div class="bio-body">
<div class="bio-date">Databases</div>
<div class="bio-desc" markdown="1">

SQL, Text-to-SQL, schema linking, query optimization

</div>
</div>

<div class="bio-body">
<div class="bio-date">Enterprise AI</div>
<div class="bio-desc" markdown="1">

Production deployment, scalability, safety & security, multilingual systems

</div>
</div>

</div>

<script>
(function () {
  var tabBtns = document.querySelectorAll('#bio-tab-bar .bio-tab-btn');
  var panels = document.querySelectorAll('.bio-panel');

  tabBtns.forEach(function (btn) {
    btn.addEventListener('click', function () {
      tabBtns.forEach(function (b) { b.classList.remove('active'); });
      btn.classList.add('active');
      var tab = btn.getAttribute('data-tab');
      panels.forEach(function (p) {
        p.classList.toggle('active', p.getAttribute('data-tab') === tab);
      });
    });
  });
})();
</script>
