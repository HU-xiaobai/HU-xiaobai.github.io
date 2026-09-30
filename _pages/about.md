---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# ✨ About me

Hi, everyone! I am currently a Third-year PhD student (10.2024-) at [King's College London, NLP group](https://kclnlp.github.io/), School of Informatics. I am fortunate to be supervised by [Dr. Lin Gui](https://sites.google.com/view/lin-gui/about-me) and [Prof. Yulan He](https://sites.google.com/view/yulanhe). I finished my MSC AI at the University of Edinburgh and my BEng EEE project jointly at the University of Edinburgh and North China Electric Power University(NCEPU). I am fortunate to be supervised by [Prof. Frank Keller](https://homepages.inf.ed.ac.uk/keller/) for my MSC and [Dr. Jiabin Jia](https://eng.ed.ac.uk/about/people/dr-jiabin-jia) for my BEng.

I am currently a Qingyun intern at Tencent YuanBao <img src="https://www.google.com/s2/favicons?sz=64&domain_url=https://yuanbao.tencent.com" alt="Tencent Yuanbao" width="16" height="16" /> for Agent Memory, welcome any chat with me!




<div class="profile-links" style="margin: 16px 0 24px 0; white-space: nowrap; line-height: 2; font-size: 14px;">

  <a href="mailto:zhanghao.hu@kcl.ac.uk">
    <i class="fas fa-envelope"></i> Email
  </a> /

  <a href="https://x.com/HZhanghao" target="_blank">
    <i class="fab fa-twitter"></i> Twitter
  </a> /

  <a href="https://xhslink.cn/o/5za2nfHuc2y" target="_blank">
    <i class="fas fa-book-open"></i> RedNote
  </a> /

  <a href="https://scholar.google.com/citations?user=trDOsRsAAAAJ" target="_blank">
    <i class="fas fa-graduation-cap"></i> Google Scholar
    <img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fhu-xiaobai.github.io%2Fassets%2Fgs_data_shieldsio.json&amp;logo=Google%20Scholar&amp;labelColor=f6f6f6&amp;color=9cf&amp;style=flat&amp;label=citations"
         alt="Citations" style="vertical-align: middle;">
  </a> /

  <a href="https://github.com/HU-xiaobai" target="_blank">
    <i class="fab fa-github"></i> GitHub
    <img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fhu-xiaobai.github.io%2Fassets%2Fstars_data_shieldsio.json&amp;logo=github&amp;logoColor=181717&amp;labelColor=f6f6f6&amp;color=9cf&amp;style=flat&amp;label=stars"
         alt="Stars" style="vertical-align: middle;">
  </a>

</div>

# 🔍 Research Summary

My research focuses on **Agent Memory, Agent Harnesses, and Self-Improving AI Agents**, aiming to build reliable and adaptive LLM agents for complex, long-horizon tasks. My work explores how agents can **organise and leverage past experience**, how their **capabilities can be evaluated in realistic environments**, and how their **memory and supporting systems can evolve through feedback**. My current research interests include:

* **Agent Memory and Retrieval.** I investigate how agents organise, retrieve, and utilise past experience for reliable reasoning and decision-making. Building on my earlier work in [EEE-QA (LREC-COLING 2024)](https://aclanthology.org/2024.lrec-main.490/), [EmbQA (ACL 2025)](https://arxiv.org/abs/2503.01606), and [SPS (AAAI 2026 Oral)](https://arxiv.org/abs/2508.05909), I developed [xMemory (NeurIPS 2026)](https://arxiv.org/abs/2602.02007), a hierarchical memory framework extending structured retrieval beyond conventional RAG. My ongoing work explores **adaptive memory structures and utility-driven memory evolution**.

* **Agent Harnesses and Evaluation.** I explore how memory, retrieval, and external agent systems support reliable behaviour in complex environments. My recent work includes [GroupAssistBench (ICLR 2027 Submission)], evaluating memory-informed group assistance, and [CoMateEval (ICLR 2027 Submission)], benchmarking LLMs in dynamic multi-party collaboration.

* **Self-Improving Agents (RSI).** My long-term interest is in enabling agents to iteratively improve their memory, harnesses, and behaviours through experience and feedback.

Beyond these directions, my broader research experience includes **efficient LLM reasoning** ([CODI, EMNLP 2025](https://arxiv.org/abs/2502.21074)), **robustness and hallucination detection** ([OSCR-Attack, ACL Findings 2026](https://aclanthology.org/2026.findings-acl.1235/); [ICML 2026](https://openreview.net/forum?id=Mo6iakSLwn)), and **multimodal reasoning and generation** ([VQG, ACL ALVR 2024](https://aclanthology.org/2024.alvr-1.12/); [Human Motion Generation, TPAMI 2025](https://www.techrxiv.org/doi/full/10.36227/techrxiv.172793202.22697340)).

# 🔥 News

<div style="max-height: 150px; overflow-y: scroll; padding-right: 10px;">

<ul>
    <li><b>2026.09</b>: Our paper <i>Beyond RAG for Agent Memory: Retrieval by Decoupling and Aggregation</i> has been accepted by <b>Neurips 2026</b>! 🎉</li>
    <li><b>2026.09</b>: Our paper <i> Beyond Task Boundaries: Instruction-Level Parameter Isolation for Supervised Fine-Tuning</i> has been accepted by <b>EMNLP Oral</b>! 🎉</li>
    <li><b>2026.05</b>: Our paper <i>Detecting Contextual Hallucinations in LLMs with Frequency-Aware Attention</i> has been accepted by <b>ICML 2026</b>! 🎉</li>
    <li><b>2026.04</b>:🧑‍💻Started internship at Tencent Yuanbao Qingyun Intern for Agent Memory <img src="https://www.google.com/s2/favicons?sz=64&domain_url=https://yuanbao.tencent.com" alt="Tencent Yuanbao" width="16" height="16" />! 🎉</li>
    <li><b>2026.04</b>: Our paper <i>OSCR-Attack: One-Shot Character Level Attacks through Self-Optimizing Continuous Relaxation</i> has been accepted by <b>ACL 2026 findings</b>! 🎉</li>
  <li><b>2025.11</b>: Our paper <i>Spectrum Projection Score: Aligning Retrieved Summaries with Reader Models in Retrieval-Augmented Generation</i> has been accepted by <b>AAAI 2026 <span style="color:red">Oral🌟</span></b>! 🎉</li>
  <li><b>2025.08</b>: Our paper <i>CODI: Compressing Chain-of-Thought into Continuous Space via Self-Distillation</i> has been accepted by <b>EMNLP 2025 Main</b>! 🎉</li>
  <li><b>2025.07</b>: Our paper <i>Human motion video generation: A survey</i> has been accepted by <b>TPAMI 2025</b>! 🎉</li>
  <li><b>2025.05</b>: Our paper <i>Beyond Prompting: An Efficient Embedding Framework for Open-Domain Question Answering</i> has been accepted by <b>ACL 2025 Main</b>! 🎉</li>
  <li><b>2024.10</b>: I start my PhD📚 journey at King's College London, NLP group! </li>
  <li><b>2024.06</b>: Our paper <i>Causal and Temporal Inference in Visual Question Generation by Utilizing Pre-trained Models</i> has been accepted by <b>ACL ALVR 2024</b>! 🎉</li>
  <li><b>2024.02</b>: Our paper <i>Exploring Effective and Efficient Question-Answer Representations</i> has been accepted by <b>COLING 2024</b>! 🎉</li>
  <li><b>2023.12</b>: Our paper <i>EEE-QA: Exploring Effective and Efficient Question-Answer Representations</i> has been accepted by <b>AAAI 2024 DEPLOYABLE AI</b>! 🎉</li>
</ul>

</div>
🚀 I am always open to new collaborations and engaging discussions. Feel free to reach out if you are interested in working together or just want to chat!

# 📚 Selected Publications

<p class="pub-note">
† Equal contribution. * Corresponding author.
Selected and representative works are shown below.
For a complete publication list, please visit my
<a href="https://scholar.google.com/citations?user=trDOsRsAAAAJ" target="_blank">
Google Scholar
</a>.
</p>

<div class="pub-filters">

  <button class="pub-filter active" data-filter="all">
    All <span class="pub-count" data-count="all">0</span>
  </button>

  <button class="pub-filter" data-filter="memory">
    Memory & Retrieval <span class="pub-count" data-count="memory">0</span>
  </button>

  <button class="pub-filter" data-filter="agent">
    Agents & Evaluation <span class="pub-count" data-count="agent">0</span>
  </button>

  <button class="pub-filter" data-filter="reasoning">
    Reasoning & Reliability <span class="pub-count" data-count="reasoning">0</span>
  </button>

  <button class="pub-filter" data-filter="multimodal">
    Multimodal <span class="pub-count" data-count="multimodal">0</span>
  </button>

</div>


<!-- ========================================================= -->
<!-- GroupAssistBench -->
<!-- ========================================================= -->

<div class="paper-box pub-item leading-paper"
     data-category="memory agent">

<div class="paper-box-image">
<div>
<div class="badge">ICLR 2027 Submission</div>
<img src="images/GroupAssisBenchmark_Intro.jpg"
     alt="GroupAssistBench"
     width="100%">
</div>
</div>

<div class="paper-box-text" markdown="1">

[**One Assistant, Many Memories: Benchmarking Real-World Group Assistance When Recall Is Not Enough**](https://openreview.net/forum?id=cZtUReT2nl)

**Zhanghao Hu**, Linhai Zhang, Qian Zhao, Qi Zhu, Yuan Hua, Di Liang, Jiasheng Si, Xin Zhao, Yulan He, Zhumin Chen, Lin Gui

[**Paper**](https://openreview.net/forum?id=cZtUReT2nl)

A real-world group-memory benchmark showing that successful recall does not necessarily translate into effective assistance, especially when memories are distributed or conflicting.

</div>
</div>


<!-- ========================================================= -->
<!-- CoMateEval -->
<!-- ========================================================= -->

<div class="paper-box pub-item leading-paper"
     data-category="agent">

<div class="paper-box-image">
<div>
<div class="badge">ICLR 2027 Submission</div>
<img src="images/CoMateSim.png"
     alt="CoMateEval"
     width="100%">
</div>
</div>

<div class="paper-box-text" markdown="1">

[**CoMateEval: Benchmarking LLMs Across Team Roles in Dynamic Multi-Party Collaboration**](https://openreview.net/forum?id=QcCZA9gmq6)

Xianjie Wu, **Zhanghao Hu**, Tianle Gu, Wuzhenghong Wen, Xiaohang Xu, Yuhui Wang, Yujia Chen, Naifu Liang, et al.

[**Paper**](https://openreview.net/forum?id=QcCZA9gmq6)

A benchmark for evaluating how well LLMs fulfil diverse team responsibilities across dynamic multi-party collaborative environments.

</div>
</div>



<!-- ========================================================= -->
<!-- xMemory -->
<!-- ========================================================= -->

<div class="paper-box pub-item leading-paper"
     data-category="memory agent">

<div class="paper-box-image">
<div>
<div class="badge">NeurIPS 2026</div>
<img src="images/xMemory_intro_ql.jpg"
     alt="xMemory">
</div>
</div>

<div class="paper-box-text" markdown="1">

[**Beyond RAG for Agent Memory: Retrieval by Decoupling and Aggregation**](https://arxiv.org/abs/2602.02007)

**Zhanghao Hu**, Qinglin Zhu, Hanqi Yan, Yulan He, Lin Gui

[![GitHub stars](https://img.shields.io/github/stars/HU-xiaobai/xMemory?style=social)](https://github.com/HU-xiaobai/xMemory)
[**Project**](https://zhanghao-xmemory.github.io/Academic-project-page-template/) /
[**Code**](https://github.com/HU-xiaobai/xMemory) /
[**Paper**](https://arxiv.org/abs/2602.02007)

A hierarchical agent-memory framework that decouples correlated interactions into semantic components and aggregates them for structure-aware retrieval beyond conventional top-k RAG.

<span class="featured-by">
  <span class="featured-label">Recommendation:</span>
  <a href="https://www.linkedin.com/posts/jason-mcewen-57300029_artificialintelligence-machinelearning-agenticai-activity-7448667198040141824-jL6S/"><strong>Alan Turing Institute</strong></a> ·
  <a href="https://venturebeat.com/orchestration/how-xmemory-cuts-token-costs-and-context-bloat-in-ai-agents"><strong>VentureBeat</strong></a> ·
  <a href="https://x.com/dair_ai/status/2018765444702982395"><strong>DAIR.AI</strong></a> ·
  <a href="https://www.getmaxim.ai/blog/xmemory-why-top-k-retrieval-breaks-for-agent-memory/"><strong>Maxim AI</strong></a> ·
  <a href="https://www.linkedin.com/posts/jason-mcewen-57300029_artificialintelligence-machinelearning-agenticai-activity-7448667198040141824-jL6S/"><strong>EmergentMind</strong></a>
</span>

</div>
</div>


<!-- ========================================================= -->
<!-- SPS -->
<!-- ========================================================= -->

<div class="paper-box pub-item leading-paper"
     data-category="memory">

<div class="paper-box-image">
<div>
<div class="badge">AAAI 2026 Oral</div>
<img src="images/xcompress.png"
     alt="SPS"
     width="100%">
</div>
</div>

<div class="paper-box-text" markdown="1">

[**Beyond Perplexity: Let the Reader Select Retrieval Summaries via Spectrum Projection Score**](https://arxiv.org/abs/2508.05909)

**Zhanghao Hu**, Qinglin Zhu, Siya Qi, Yulan He, Hanqi Yan, Lin Gui

<span class="paper-highlight">
Oral 🌟 around 4% (900 / 23,680)
</span>
/
[**Project**](https://zhanghao-aaai2026-sps.github.io/AAAI2026-SPS/) /
[**Paper**](https://arxiv.org/abs/2508.05909)

A reader-aware metric and inference-time retrieval controller for selecting summaries according to their alignment with downstream LLM representations.

</div>
</div>

<!-- ========================================================= -->
<!-- EmbQA -->
<!-- ========================================================= -->

<div class="paper-box pub-item leading-paper"
     data-category="memory">

<div class="paper-box-image">
<div>
<div class="badge">ACL 2025 Main</div>
<img src="images/EmbQA.jpg"
     alt="EmbQA"
     width="100%">
</div>
</div>

<div class="paper-box-text" markdown="1">

[**Beyond Prompting: An Efficient Embedding Framework for Open-Domain Question Answering**](https://arxiv.org/abs/2503.01606)

**Zhanghao Hu**, Hanqi Yan, Qinglin Zhu, Zhenyi Shen, Yulan He, Lin Gui

[**Project**](https://zhanghao-acl25-embqa.github.io/ACL2025-EmbQA/) /
[**Paper**](https://arxiv.org/abs/2503.01606)

An embedding-level framework for refining retrieval and diversifying answer generation without relying on additional prompting.

</div>
</div>


<!-- ========================================================= -->
<!-- EEE-QA -->
<!-- ========================================================= -->

<div class="paper-box pub-item leading-paper"
     data-category="memory">

<div class="paper-box-image">
<div>
<div class="badge">LREC-COLING 2024</div>
<img src="images/eee-qa.png"
     alt="EEE-QA"
     width="100%">
</div>
</div>

<div class="paper-box-text" markdown="1">

[**EEE-QA: Exploring Effective and Efficient Question-Answer Representations**](https://aclanthology.org/2024.lrec-main.490/)

**Zhanghao Hu**†, Yijun Yang†, Junjie Xu†, Yifu Qiu, Pinzhen Chen

[**Paper**](https://aclanthology.org/2024.lrec-main.490/)

Studies effective and memory-efficient question-answer representations while maintaining competitive QA performance.

</div>
</div>


<!-- ========================================================= -->
<!-- CODI -->
<!-- ========================================================= -->

<div class="paper-box pub-item extra-pub"
     data-category="reasoning">

<div class="paper-box-image">
<div>
<div class="badge">EMNLP 2025 Main</div>
<img src="images/codi.png"
     alt="CODI"
     width="100%">
</div>
</div>

<div class="paper-box-text" markdown="1">

[**CODI: Compressing Chain-of-Thought into Continuous Space via Self-Distillation**](https://arxiv.org/abs/2502.21074)

Zhenyi Shen, Hanqi Yan, Linhai Zhang, **Zhanghao Hu**, Yali Du, Yulan He

[**Paper**](https://arxiv.org/abs/2502.21074)

Compresses explicit chain-of-thought reasoning into continuous latent representations through self-distillation.

</div>
</div>


<!-- ========================================================= -->
<!-- OSCR-Attack -->
<!-- ========================================================= -->

<div class="paper-box pub-item extra-pub"
     data-category="reasoning">

<div class="paper-box-image">
<div>
<div class="badge">ACL 2026 Findings</div>
<img src="images/oscr_attack.png"
     alt="OSCR-Attack"
     width="100%">
</div>
</div>

<div class="paper-box-text" markdown="1">

[**OSCR-Attack: One-Shot Character Level Attacks through Self-Optimizing Continuous Relaxation**](https://aclanthology.org/2026.findings-acl.1235/)

Lingyi Kong, Zhuo Liu, **Zhanghao Hu**, Qilong Qiu, Yutao Yang, Jingjing Xue, Zheng Wang, Lin Gui, Feiping Nie

[**Paper**](https://aclanthology.org/2026.findings-acl.1235/)

An efficient character-level adversarial attack that transforms discrete perturbation choices into continuous optimisation for one-shot attacks on LLMs.

</div>
</div>


<!-- ========================================================= -->
<!-- ICML 2026 Hallucination -->
<!-- ========================================================= -->

<div class="paper-box pub-item extra-pub"
     data-category="reasoning">

<div class="paper-box-image">
<div>
<div class="badge">ICML 2026</div>
<img src="images/siya_main.png"
     alt="Contextual Hallucination Detection"
     width="100%">
</div>
</div>

<div class="paper-box-text" markdown="1">

[**Detecting Contextual Hallucinations in Large Language Models with Frequency-Aware Attention**](https://proceedings.mlr.press/v306/qi26d.html)

Siya Qi, Yudong Chen, Runcong Zhao, Qinglin Zhu, **Zhanghao Hu**, Wei Liu, Yulan He, Zheng Yuan, Lin Gui

[**Paper**](https://proceedings.mlr.press/v306/qi26d.html)

Detects contextual hallucinations through frequency-aware attention features that capture fragmented and unstable grounding during generation.

</div>
</div>


<!-- ========================================================= -->
<!-- Human Motion Video Generation -->
<!-- ========================================================= -->

<div class="paper-box pub-item extra-pub"
     data-category="multimodal">

<div class="paper-box-image">
<div>
<div class="badge">TPAMI 2025</div>
<img src="images/dance_motion.png"
     alt="Human Motion Video Generation"
     width="100%">
</div>
</div>

<div class="paper-box-text" markdown="1">

[**Human Motion Video Generation: A Survey**](https://www.techrxiv.org/doi/full/10.36227/techrxiv.172793202.22697340)

Haiwei Xue, Xiangyang Luo, **Zhanghao Hu**, Xin Zhang, Xunzhi Xiang, Yuqin Dai, et al.

[**Paper**](https://www.techrxiv.org/doi/full/10.36227/techrxiv.172793202.22697340)

A comprehensive taxonomy and survey of human-motion video generation covering the full generation pipeline and major task settings.

</div>
</div>


<!-- ========================================================= -->
<!-- Visual Question Generation -->
<!-- ========================================================= -->

<div class="paper-box pub-item extra-pub"
     data-category="multimodal">

<div class="paper-box-image">
<div>
<div class="badge">ACL ALVR 2024</div>
<img src="images/video_causal.png"
     alt="Visual Question Generation"
     width="100%">
</div>
</div>

<div class="paper-box-text" markdown="1">

[**Causal and Temporal Inference in Visual Question Generation by Utilizing Pre-trained Models**](https://aclanthology.org/2024.alvr-1.12/)

**Zhanghao Hu**, Frank Keller

[**Paper**](https://aclanthology.org/2024.alvr-1.12/)

Uses pretrained vision-language representations to generate questions requiring causal and temporal inference over videos.

</div>
</div>


<div class="show-more-container">
  <button id="show-more-pubs" class="show-more-pubs">
    Show more publications
  </button>
</div>

# 😆 Mentee
- **LLM Safety** 
    - Lingyi Kong (LLM Security and Attack)
- **Multi-modal Alignment** 
    - Zipeng Zhu (Image Edit)

# 💬 Invited Talks
- 02/2026. <strong> Queen Mary University of London, NLP Group </strong>


# Professional Service
  - Volunteer:
    - AAAI 2026
  - Reviewers:
    - NLP: EMNLP 2025, ACL 2026，EMNLP 2026
    - AI/ML: AAAI 2026, ICML 2026，NIPS 2026，ICLR 2026


  
# 🎖 Honors and Awards
- *2023.01* IBM Shortlist for Best Project in Machine Learning Practical Course, Ranked 5/103.

- *2022.06* Outstanding Graduate Award, NCEPU

- *2022.05* £3000 Scholarship, University of Edinburgh, For Excellent 2+2 International Students

- *2021.05* £2500 Scholarship, University of Edinburgh, For Excellent 2+2 International Students

- *2020.10* Third Prize Academic Scholarship, NCEPU, Awarded to top 10% of students

- *2019.10* Second Prize Academic Scholarship, NCEPU, Awarded to top 5% of students

# 📖 Educations
- *2022.09 – 2023.11*, **MSc in Artificial Intelligence**, University of Edinburgh, Distinction Degree, ranked top ~10%

- *2020.09 – 2022.05*, **Bachelor in Electronics and Electrical Engineering**, University of Edinburgh, First-Class Honour Degree, ranked top ~10%

- *2018.09 – 2020.06*, **Bachelor in Electrical Engineering and Its Automation**, North China Electric Power University (NCEPU) Ranked ~15%


# 💻 Internships
- *2024.04 - 2024.08*, Research Intern at [01.AI](https://www.01.ai/).

<style>

/* ==========================================
   Publication intro
   ========================================== */

.pub-note {
  margin-top: -5px;
  margin-bottom: 18px;
  font-size: 0.90em;
  color: #666;
}


/* ==========================================
   Filter bar
   ========================================== */

.pub-filters {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  align-items: center;

  margin: 12px 0 26px 0;
}

.pub-filter {
  display: inline-flex;
  align-items: center;
  gap: 7px;

  padding: 6px 12px;

  border: 1px solid #dfe3e8;
  border-radius: 18px;

  background: #f6f8fa;
  color: #444;

  font-family: inherit;
  font-size: 0.86em;
  font-weight: 500;

  cursor: pointer;

  transition:
    background 0.18s ease,
    border-color 0.18s ease,
    color 0.18s ease,
    transform 0.18s ease,
    box-shadow 0.18s ease;
}

.pub-filter:hover {
  background: #fff;
  border-color: #b8c0c8;

  transform: translateY(-1px);

  box-shadow: 0 2px 7px rgba(0, 0, 0, 0.06);
}

.pub-filter.active {
  background: #24292f;
  border-color: #24292f;
  color: #fff;

  box-shadow: 0 2px 7px rgba(0, 0, 0, 0.12);
}


/* ==========================================
   Count bubbles
   ========================================== */

.pub-count {
  display: inline-flex;
  align-items: center;
  justify-content: center;

  min-width: 19px;
  height: 19px;

  padding: 0 5px;

  border-radius: 10px;

  background: rgba(0, 0, 0, 0.08);

  font-size: 0.76em;
  font-weight: 600;
  line-height: 1;
}

.pub-filter.active .pub-count {
  background: rgba(255, 255, 255, 0.20);
  color: #fff;
}


/* ==========================================
   Publication cards
   ========================================== */

.paper-box.pub-item {
  display: flex;
  align-items: center;

  margin: 0 0 14px 0;
  padding: 12px 14px;

  border: 1px solid #e7e9ec;
  border-radius: 9px;
  background: #fff;
}

.paper-box-image {
  position: relative;

  flex: 0 0 42%;
  max-width: 420px;

  margin-right: 24px;
}

.paper-box-image > div {
  position: relative;
  width: 100%;
}

.paper-box-image img {
  display: block;

  width: 100%;
  height: auto;

  object-fit: contain;
  border-radius: 6px;
}

.paper-box-text {
  flex: 1;
  min-width: 0;
}

/* representative works */

.paper-box.leading-paper {
  border-left: 3px solid #777f89;
}


/* ==========================================
   Image
   ========================================== */

.paper-box-image {
  position: relative;

  flex: 0 0 40%;
  max-width: 400px;

  display: flex;
  align-items: center;
  justify-content: center;

  margin-right: 24px;
}

.paper-box-image > div {
  position: relative;
  width: 100%;
}

.paper-box-image .badge {
  position: absolute;

  top: 8px;
  left: -10px;

  z-index: 2;

  padding: 4px 9px;

  border-radius: 4px;

  background: #527bbd;
  color: white;

  font-size: 0.76em;
  font-weight: 600;
  line-height: 1.2;

  white-space: nowrap;

  box-shadow: 0 1px 4px rgba(0, 0, 0, 0.15);
}

/* ==========================================
   Text
   ========================================== */

.paper-box-text {
  flex: 1;
  min-width: 0;
}

.paper-box-text > p:first-child {
  margin-top: 0;
}

.paper-box-text p {
  margin-top: 7px;
  margin-bottom: 7px;
}

.paper-highlight {
  color: #d73a49;
  font-weight: 600;
}

.featured-by {
  display: block;
  margin-top: 8px;

  font-size: 0.84em;
  line-height: 1.4;

  white-space: nowrap;
}

.featured-label {
  color: #d73a49;
  font-weight: 600;
  margin-right: 3px;
}

/* ==========================================
   Show more
   ========================================== */

.show-more-container {
  display: flex;
  justify-content: center;

  margin: 10px 0 30px 0;
}

.show-more-pubs {
  padding: 7px 17px;

  border: 1px solid #d0d7de;
  border-radius: 18px;

  background: #fff;
  color: #444;

  font-family: inherit;
  font-size: 0.86em;

  cursor: pointer;

  transition:
    background 0.18s ease,
    box-shadow 0.18s ease;
}

.show-more-pubs:hover {
  background: #f6f8fa;

  box-shadow: 0 2px 7px rgba(0, 0, 0, 0.06);
}


/* ==========================================
   Fade animation
   ========================================== */

@keyframes pubFadeIn {

  from {
    opacity: 0;
    transform: translateY(4px);
  }

  to {
    opacity: 1;
    transform: translateY(0);
  }

}

.pub-visible {
  animation: pubFadeIn 0.22s ease;
}


/* ==========================================
   Mobile
   ========================================== */

@media (max-width: 700px) {
  .featured-by {
    white-space: normal;
  }
}
  
@media (max-width: 700px) {

  .pub-filters {
    gap: 6px;
  }

  .pub-filter {
    padding: 5px 9px;
    font-size: 0.78em;
  }

  .paper-box.pub-item {
    flex-direction: column;
    padding: 13px;
  }

  .paper-box-image {
    flex: none;
    width: 100%;
    max-width: 100%;

    margin-right: 0;
    margin-bottom: 15px;
  }

  .paper-box-image img {
    width: 100%;
    height: auto;
    max-height: none;
  }

}
  
</style>

<script>

document.addEventListener("DOMContentLoaded", function () {

  const filters =
    document.querySelectorAll(".pub-filter");

  const papers =
    document.querySelectorAll(".pub-item");

  const showMoreButton =
    document.getElementById("show-more-pubs");


  let currentFilter = "all";
  let expanded = false;


  /* ========================================
     Count publications automatically
     ======================================== */

  const counts = {
    all: papers.length,
    memory: 0,
    agent: 0,
    reasoning: 0,
    multimodal: 0
  };


  papers.forEach((paper) => {

    const categories =
      (paper.dataset.category || "")
        .split(/\s+/)
        .filter(Boolean);


    categories.forEach((category) => {

      if (
        Object.prototype.hasOwnProperty.call(
          counts,
          category
        )
      ) {

        counts[category]++;

      }

    });

  });


  Object.entries(counts).forEach(
    ([category, count]) => {

      const element =
        document.querySelector(
          '.pub-count[data-count="' +
          category +
          '"]'
        );

      if (element) {
        element.textContent = count;
      }

    }
  );


  /* ========================================
     Main filtering function
     ======================================== */

  function updatePublications() {

    papers.forEach((paper) => {

      const categories =
        (paper.dataset.category || "")
          .split(/\s+/)
          .filter(Boolean);


      const matches =
        currentFilter === "all" ||
        categories.includes(currentFilter);


      const isExtra =
        paper.classList.contains("extra-pub");


      let shouldShow = false;


      if (currentFilter === "all") {

        shouldShow =
          matches &&
          (!isExtra || expanded);

      }

      else {

        /*
         * When a specific category is selected,
         * ALWAYS show all matching papers,
         * including extra-pub.
         */

        shouldShow = matches;

      }


      if (shouldShow) {

        paper.style.display = "flex";

        paper.classList.remove("pub-visible");

        void paper.offsetWidth;

        paper.classList.add("pub-visible");

      }

      else {

        paper.style.display = "none";

      }

    });


    /* ========================================
       Show more button
       ======================================== */

    if (showMoreButton) {

      if (currentFilter === "all") {

        showMoreButton.style.display =
          "inline-flex";

        showMoreButton.textContent =
          expanded
            ? "Show fewer publications"
            : "Show more publications";

      }

      else {

        showMoreButton.style.display =
          "none";

      }

    }

  }


  /* ========================================
     Category buttons
     ======================================== */

  filters.forEach((button) => {

    button.addEventListener(
      "click",
      function () {

        filters.forEach((filter) => {
          filter.classList.remove("active");
        });


        this.classList.add("active");


        currentFilter =
          this.dataset.filter;


        updatePublications();

      }
    );

  });


  /* ========================================
     Show more
     ======================================== */

  if (showMoreButton) {

    showMoreButton.addEventListener(
      "click",
      function () {

        expanded = !expanded;

        updatePublications();

      }
    );

  }


  /* initial rendering */

  updatePublications();

});

</script>
