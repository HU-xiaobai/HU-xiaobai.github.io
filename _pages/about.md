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

Hi, everyone! I am currently a second-year PhD student (10.2024-) at [King's College London, NLP group](https://kclnlp.github.io/), School of Informatics. I am fortunate to be supervised by [Dr. Lin Gui](https://sites.google.com/view/lin-gui/about-me) and [Prof. Yulan He](https://sites.google.com/view/yulanhe). I finished my MSC AI at the University of Edinburgh and my BEng EEE project jointly at the University of Edinburgh and North China Electric Power University(NCEPU). I am fortunate to be supervised by [Prof. Frank Keller](https://homepages.inf.ed.ac.uk/keller/) for my MSC and [Dr. Jiabin Jia](https://eng.ed.ac.uk/about/people/dr-jiabin-jia) for my BEng.

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

<p style="font-size: 0.92em; margin-bottom: 14px;">
† Equal contribution. * Corresponding author.
Representative and first-author works are highlighted.
For a complete publication list, please visit my
<a href="https://scholar.google.com/citations?user=trDOsRsAAAAJ" target="_blank">
Google Scholar
</a>.
</p>


<div class="pub-filters">
  <button class="pub-filter active" data-filter="all">All</button>
  <button class="pub-filter" data-filter="memory">Memory & Retrieval</button>
  <button class="pub-filter" data-filter="agent">Agents & Evaluation</button>
  <button class="pub-filter" data-filter="reasoning">Reasoning & Reliability</button>
  <button class="pub-filter" data-filter="multimodal">Multimodal</button>
</div>


<!-- ========================================================= -->
<!-- GroupAssistBench -->
<!-- ========================================================= -->

<div class="paper-box pub-item leading-paper"
     data-category="memory agent">

<div class='paper-box-image'>
<div>
<div class="badge">ICLR 2027 Submission</div>
<img src='images/groupassistbench.png' alt="GroupAssistBench" width="100%">
</div>
</div>

<div class='paper-box-text' markdown="1">

[**One Assistant, Many Memories: Benchmarking Real-World Group Assistance When Recall Is Not Enough**](https://openreview.net/forum?id=cZtUReT2nl)

**Zhanghao Hu**, Linhai Zhang, Qian Zhao, Qi Zhu, Yuan Hua, Di Liang, Jiasheng Si, Xin Zhao, Yulan He, Zhumin Chen, Lin Gui

[**Paper**](https://openreview.net/forum?id=cZtUReT2nl)

A real-world group-memory benchmark showing that successful recall does not necessarily translate into effective assistance, especially when memories are distributed or conflicting.

</div>
</div>


<!-- ========================================================= -->
<!-- xMemory -->
<!-- ========================================================= -->

<div class="paper-box pub-item leading-paper"
     data-category="memory agent">

<div class='paper-box-image'>
<div>
<div class="badge">NeurIPS 2026</div>
<img src='images/xMemory.png' alt="xMemory" width="75%">
</div>
</div>

<div class='paper-box-text' markdown="1">

[**Beyond RAG for Agent Memory: Retrieval by Decoupling and Aggregation**](https://arxiv.org/abs/2602.02007)

**Zhanghao Hu**, Qinglin Zhu, Hanqi Yan, Yulan He, Lin Gui

[![GitHub stars](https://img.shields.io/github/stars/HU-xiaobai/xMemory?style=social)](https://github.com/HU-xiaobai/xMemory)
[**Project**](https://zhanghao-xmemory.github.io/Academic-project-page-template/) /
[**Code**](https://github.com/HU-xiaobai/xMemory) /
[**Paper**](https://arxiv.org/abs/2602.02007)

A hierarchical agent-memory framework that decouples correlated interactions into semantic components and aggregates them for structure-aware retrieval beyond conventional top-k RAG.

<span class="featured-by">
Featured by:
<a href="https://venturebeat.com/orchestration/how-xmemory-cuts-token-costs-and-context-bloat-in-ai-agents">VentureBeat</a> ·
<a href="https://x.com/dair_ai/status/2018765444702982395">DAIR.AI</a> ·
<a href="https://www.getmaxim.ai/blog/xmemory-why-top-k-retrieval-breaks-for-agent-memory/">Maxim AI</a>
</span>

</div>
</div>


<!-- ========================================================= -->
<!-- SPS -->
<!-- ========================================================= -->

<div class="paper-box pub-item leading-paper"
     data-category="memory reasoning">

<div class='paper-box-image'>
<div>
<div class="badge">AAAI 2026 Oral</div>
<img src='images/xcompress.png' alt="SPS" width="100%">
</div>
</div>

<div class='paper-box-text' markdown="1">

[**Beyond Perplexity: Let the Reader Select Retrieval Summaries via Spectrum Projection Score**](https://arxiv.org/abs/2508.05909)

**Zhanghao Hu**, Qinglin Zhu, Siya Qi, Yulan He, Hanqi Yan, Lin Gui

<span style="color:red">Oral 🌟</span> /
[**Project**](https://zhanghao-aaai2026-sps.github.io/AAAI2026-SPS/) /
[**Paper**](https://arxiv.org/abs/2508.05909)

A reader-aware metric and inference-time retrieval controller for selecting summaries according to their alignment with downstream LLM representations.

</div>
</div>


<!-- ========================================================= -->
<!-- CoMateEval -->
<!-- ========================================================= -->

<div class="paper-box pub-item leading-paper"
     data-category="agent">

<div class='paper-box-image'>
<div>
<div class="badge">ICLR 2027 Submission</div>
<img src='images/comateeval.png' alt="CoMateEval" width="100%">
</div>
</div>

<div class='paper-box-text' markdown="1">

[**CoMateEval: Benchmarking LLMs Across Team Roles in Dynamic Multi-Party Collaboration**](https://openreview.net/forum?id=QcCZA9gmq6)

Xianjie Wu, **Zhanghao Hu**, Tianle Gu, Wuzhenghong Wen, Xiaohang Xu, Yuhui Wang, et al.

[**Paper**](https://openreview.net/forum?id=QcCZA9gmq6)

A benchmark for evaluating how well LLMs fulfil diverse team responsibilities across dynamic multi-party collaborative environments.

</div>
</div>


<!-- ========================================================= -->
<!-- EmbQA -->
<!-- ========================================================= -->

<div class="paper-box pub-item leading-paper"
     data-category="memory reasoning">

<div class='paper-box-image'>
<div>
<div class="badge">ACL 2025 Main</div>
<img src='images/EmbQA.jpg' alt="EmbQA" width="100%">
</div>
</div>

<div class='paper-box-text' markdown="1">

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

<div class='paper-box-image'>
<div>
<div class="badge">LREC-COLING 2024</div>
<img src='images/eee-qa.png' alt="EEE-QA" width="100%">
</div>
</div>

<div class='paper-box-text' markdown="1">

[**EEE-QA: Exploring Effective and Efficient Question-Answer Representations**](https://aclanthology.org/2024.lrec-main.490/)

**Zhanghao Hu**†, Yijun Yang†, Junjie Xu†, Yifu Qiu, Pinzhen Chen

[**Paper**](https://aclanthology.org/2024.lrec-main.490/)

Studies effective and memory-efficient question-answer representations while maintaining competitive QA performance.

</div>
</div>


<!-- ========================================================= -->
<!-- CODI -->
<!-- hidden by default -->
<!-- ========================================================= -->

<div class="paper-box pub-item extra-pub"
     data-category="reasoning">

<div class='paper-box-image'>
<div>
<div class="badge">EMNLP 2025 Main</div>
<img src='images/codi.png' alt="CODI" width="100%">
</div>
</div>

<div class='paper-box-text' markdown="1">

[**CODI: Compressing Chain-of-Thought into Continuous Space via Self-Distillation**](https://arxiv.org/abs/2502.21074)

Zhenyi Shen, Hanqi Yan, Linhai Zhang, **Zhanghao Hu**, Yali Du, Yulan He

[**Paper**](https://arxiv.org/abs/2502.21074)

Compresses explicit chain-of-thought reasoning into continuous latent representations through self-distillation.

</div>
</div>


<!-- ========================================================= -->
<!-- Human Motion Generation -->
<!-- hidden by default -->
<!-- ========================================================= -->

<div class="paper-box pub-item extra-pub"
     data-category="multimodal">

<div class='paper-box-image'>
<div>
<div class="badge">TPAMI 2025</div>
<img src='images/dance_motion.png' alt="Human Motion Generation" width="100%">
</div>
</div>

<div class='paper-box-text' markdown="1">

[**Human Motion Video Generation: A Survey**](https://www.techrxiv.org/doi/full/10.36227/techrxiv.172793202.22697340)

Haiwei Xue, Xiangyang Luo, **Zhanghao Hu**, Xin Zhang, Xunzhi Xiang, Yuqin Dai, et al.

[**Paper**](https://www.techrxiv.org/doi/full/10.36227/techrxiv.172793202.22697340)

A comprehensive survey and taxonomy of human-motion video generation across the full generation pipeline and major task settings.

</div>
</div>


<!-- ========================================================= -->
<!-- VQG -->
<!-- hidden by default -->
<!-- ========================================================= -->

<div class="paper-box pub-item extra-pub"
     data-category="multimodal">

<div class='paper-box-image'>
<div>
<div class="badge">ACL ALVR 2024</div>
<img src='images/video_causal.png' alt="Visual Question Generation" width="100%">
</div>
</div>

<div class='paper-box-text' markdown="1">

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

/* =========================
   Publication Filters
   ========================= */

.pub-filters {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin: 14px 0 24px 0;
}

.pub-filter,
.show-more-pubs {
  border: 1px solid #d0d7de;
  background: #ffffff;
  color: #444;
  border-radius: 18px;
  padding: 5px 13px;
  font-size: 0.88em;
  cursor: pointer;
  transition: all 0.2s ease;
}

.pub-filter:hover,
.show-more-pubs:hover {
  background: #f3f4f6;
}

.pub-filter.active {
  background: #24292f;
  color: #ffffff;
  border-color: #24292f;
}


/* =========================
   Publication Cards
   ========================= */

.leading-paper {
  border-left: 3px solid #888;
}

/* hide non-core papers on the default All view */
.extra-pub {
  display: none;
}

.featured-by {
  display: block;
  margin-top: 6px;
  font-size: 0.83em;
  color: #666;
}

.show-more-container {
  text-align: center;
  margin: 15px 0 28px 0;
}


/* =========================
   Mobile
   ========================= */

@media (max-width: 600px) {

  .pub-filters {
    gap: 6px;
  }

  .pub-filter {
    padding: 4px 9px;
    font-size: 0.80em;
  }

}

</style>

<script>

document.addEventListener("DOMContentLoaded", function () {

  const filters = document.querySelectorAll(".pub-filter");
  const papers = document.querySelectorAll(".pub-item");
  const showMoreButton = document.getElementById("show-more-pubs");

  let expanded = false;
  let currentFilter = "all";

  function updatePublications() {

    papers.forEach((paper) => {

      const categories = paper.dataset.category.split(" ");

      const matchesFilter =
        currentFilter === "all" ||
        categories.includes(currentFilter);

      const isExtra =
        paper.classList.contains("extra-pub");

      if (!matchesFilter) {

        paper.style.display = "none";

      } else if (
        currentFilter === "all" &&
        isExtra &&
        !expanded
      ) {

        paper.style.display = "none";

      } else {

        paper.style.display = "";

      }

    });


    /* Show-more button only appears in "All" */
    if (showMoreButton) {

      if (currentFilter === "all") {

        showMoreButton.style.display = "inline-block";

        showMoreButton.textContent =
          expanded
            ? "Show fewer publications"
            : "Show more publications";

      } else {

        showMoreButton.style.display = "none";

      }

    }

  }


  filters.forEach((button) => {

    button.addEventListener("click", function () {

      filters.forEach((b) =>
        b.classList.remove("active")
      );

      this.classList.add("active");

      currentFilter = this.dataset.filter;

      updatePublications();

    });

  });


  if (showMoreButton) {

    showMoreButton.addEventListener("click", function () {

      expanded = !expanded;

      updatePublications();

    });

  }


  updatePublications();

});

</script>
