---
layout: archive
title: "Projects & Impact"
permalink: /projects/
author_profile: true
---

<style>
.page__title {
  display: none;
}

.project-tab-bar {
  display: flex;
  gap: 6px;
  margin-bottom: 18px;
  flex-wrap: wrap;
}
.project-tab-btn {
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
.project-tab-btn:hover {
  border-color: #08306B;
  color: #08306B;
}
.project-tab-btn.active {
  background: #08306B;
  border-color: #08306B;
  color: #fff;
}

.project-panel {
  display: none;
}
.project-panel.active {
  display: block;
}
</style>

<div class="project-tab-bar" id="project-tab-bar">
  <button class="project-tab-btn active" data-tab="nl2insights">NL2Insights</button>
  <button class="project-tab-btn" data-tab="textsql">IBM Granite Text-to-SQL</button>
  <button class="project-tab-btn" data-tab="multilingual">Multilingual Text2SQL</button>
  <button class="project-tab-btn" data-tab="autodo">AutoDO</button>
  <button class="project-tab-btn" data-tab="rl">Reinforcement Learning</button>
  <button class="project-tab-btn" data-tab="fl">Federated Learning</button>
</div>

<div class="project-panel active" data-tab="nl2insights" markdown="1">

## NL2Insights: Enterprise Text-to-SQL at Scale

**Overview**: NL2Insights is a fully automated pipeline for converting natural language to SQL queries, powering flagship IBM products and transforming how enterprises interact with their data.

**Impact**:
- **200,000+ SQL queries** generated across **1,000+ databases**
- Powers **watsonx.data intelligence**, **BI Assistant**, and **Process Mining**
- **Doubled accuracy** while **reducing GPU usage**
- Core component of IBM's Data & AI strategy
- **Production deployment** across all IBM Cloud and AWS regions

**Key Innovations**:
- Optimized prompting strategies for enterprise data
- SQL safety modules ensuring query security
- Fine-tuned IBM Granite models for schema linking, content linking, and SQL generation
- Multilingual support (English, Japanese, with more languages coming)
- Automated reasoning capabilities for complex queries

**Recognition**:
- IBM Outstanding Technical Achievement Award - 2026 (NL2Insights Impacting Products and Clients)
- IBM Research Accomplishments (A-level) - 2025
- IBM Growth Award - 2025

</div>

<div class="project-panel" data-tab="textsql" markdown="1">

## BIRD Leaderboard: #1 in Text-to-SQL Benchmark

**Achievement**: Led IBM Granite Text-to-SQL models to **first place in both tracks** of the prestigious BIRD (BIg Bench for LaRge-scale Database Grounded Text-to-SQL Evaluation) leaderboard.

**Challenge**: BIRD features over **12,751 question-SQL pairs** across **95 databases** from **37 professional fields**, emphasizing accuracy and execution efficiency.

**Why It Matters**:
- **Outperformed GPT-4 and GPT-4o** with smaller, more efficient models (Granite-20B and Granite-34B)
- **Held #1 position for months** against intense competition
- Sparked renewed interest from major players: **Google, Alibaba, ByteDance**
- Demonstrated IBM's leadership in practical, production-ready LLM applications

**Technical Approach**:
- Fine-tuned models for three critical tasks:
  - Schema linking (connecting natural language to database schema)
  - Content linking (mapping to actual data values)
  - SQL code generation (producing accurate, executable queries)
- Developed novel training datasets from open-source and enterprise use cases
- Implemented advanced reasoning capabilities

**Recognition**:
- IBM Outstanding Technical Achievement Award - 2025
- IBM Research Accomplishments (A-level) - 2024
- Featured at THINK'24 (IBM's flagship conference)
- Deployed on BAM and Watsonx.ai platforms

</div>

<div class="project-panel" data-tab="multilingual" markdown="1">

## Multilingual Text2SQL

**Capability**: Extended Text2SQL to support multiple languages, making data accessible to global workforce.

**Deployment**:
- **Production-ready** across all IBM Cloud and AWS regions
- Integrated into IBM watsonx.data intelligence SaaS
- Currently supports English and Japanese (more languages in development)

**Impact**:
- Breaks language barriers for data interaction
- Enables non-English speakers to query databases in their native language
- Automatic conversion to optimized SQL regardless of input language

</div>

<div class="project-panel" data-tab="autodo" markdown="1">

## AutoDO: Automated Decision Optimization

**Overview**: An end-to-end automated system for solving sequential decision-making problems using data and knowledge-driven approaches.

**Contributions**:
- Designed application framework and system architecture
- Demonstrated effectiveness through comprehensive benchmarking
- **Available on IBM API Hub portal** for enterprise use

**Timeline**: Jan. 2022 – Mar. 2023

**Recognition**: Tutorial/Lab organizer at AAAI 2023: "Automated AI For Decision Optimization with Reinforcement Learning"

</div>

<div class="project-panel" data-tab="rl" markdown="1">

## Evaluating Robustness in Multi-Agent Reinforcement Learning

**Innovation**: Proposed the **first model-based adversarial attacks (cMBA)** for cooperative multi-agent reinforcement learning.

**Key Contributions**:
- Novel victim agent selection strategy
- Constrained nonconvex optimization approach
- Comprehensive experiments on multi-agent MuJoCo environments

**Publication**: IEEE International Conference on Data Mining (ICDM) 2023

**Patent**: Filed patent application on systematic approach for evaluating robustness (Sep. 2022)

</div>

<div class="project-panel" data-tab="fl" markdown="1">

## Federated Learning with Douglas-Rachford Splitting

**Innovation**: Proposed FedDR and asyncFedDR algorithms for federated learning with **best-known communication complexity**.

**Key Features**:
- Handles data heterogeneity across distributed clients
- Asynchronous updates for improved efficiency
- Rigorous theoretical guarantees

**Publication**: NeurIPS 2021 (35th Conference on Neural Information Processing Systems)

**Impact**: Advanced the state-of-the-art in federated optimization for non-convex problems

</div>

<script>
(function () {
  var tabBtns = document.querySelectorAll('#project-tab-bar .project-tab-btn');
  var panels = document.querySelectorAll('.project-panel');

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
