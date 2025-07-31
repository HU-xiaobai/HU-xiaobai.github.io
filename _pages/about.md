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

Hi, everyone! I am currently a first-year PhD student (10.2024-) at [King's College London, NLP group](https://kclnlp.github.io/), School of Informatics. I am fortunate to be supervised by [Dr. Lin Gui](https://sites.google.com/view/lin-gui/about-me) and [Prof. Yulan He](https://sites.google.com/view/yulanhe). I finished my MSC AI at the University of Edinburgh and my BEng EEE project jointly at the University of Edinburgh and North China Electric Power University(NCEPU). I am fortunate to be supervised by [Prof. Frank Keller](https://homepages.inf.ed.ac.uk/keller/) for my MSC and [Dr. Jiabin Jia](https://eng.ed.ac.uk/about/people/dr-jiabin-jia) for my BEng.

In addition to research, I interned for four months as a full-stack engineer specialising in voice cloning algorithms at [01.AI](https://www.01.ai/).

# 🔍 Research Summary
My research interests lie in the intersection of Natural Language Processing and Multi-modal Learning, i.e., cross-modality (Vision-language-audio Environment Understanding), text-generation (Open domain/long-form question answering), and reasoning (Embedding planning, latent embedding learning), to enhance the fundamental reliability and multi-modal ability of NLP models. Generally speaking, my goal is to enhance 1) the robust cross-modality alignment and comprehension abilities in interactive communication environments, and 2) advancing knowledge-based large language models (LLMs) and agents to refine reasoning. My long-term objective is to construct a robust AI framework harmonising natural language understanding and generation, dismantling barriers in human-machine communication.

* Effectiveness and Efficiency in Question Answering implemented by large language models, such as [EEE-QA, COLING 2024](https://aclanthology.org/2024.lrec-main.490/): A gate layer framework in multi-choice question answering, and [EmbQA, ACL 2025 Main](https://arxiv.org/abs/2503.01606): A rerank-reading system with an unsupervised contrastive learning framework in the rerank and an exploratory embedding mechanism in the reading framework.

* Reasoning in latent space, such as [CODI](https://arxiv.org/abs/2502.21074): Train a large language model (LLM) to perform reasoning without explicitly generating Chain-of-Thought (CoT) tokens.

* Multi-modal interpretability and application, such as [Causal and temporal inference in videos QA, ACL ALVR 2024](https://aclanthology.org/2024.alvr-1.12/), and [Human motion video generation](https://www.techrxiv.org/doi/full/10.36227/techrxiv.172793202.22697340)


# 🔥 News

<div style="max-height: 300px; overflow-y: scroll; padding-right: 10px;">

<ul>
  <li><b>2025.07</b>: Our paper <i>Human motion video generation: A survey</i> has been accepted by <b>TPAMI 2025</b>! 🎉</li>
  <li><b>2025.05</b>: Our paper <i>Beyond Prompting: An Efficient Embedding Framework for Open-Domain Question Answering</i> has been accepted by <b>ACL 2025 Main</b>! 🎉</li>
  <li><b>2024.10</b>: I start my PhD📚 journey at King's College London, NLP group! </li>
  <li><b>2024.06</b>: Our paper <i>Causal and Temporal Inference in Visual Question Generation by Utilizing Pre-trained Models</i> has been accepted by <b>ACL ALVR 2024</b>! 🎉</li>
  <li><b>2024.02</b>: Our paper <i>Exploring Effective and Efficient Question-Answer Representations</i> has been accepted by <b>COLING 2024</b>! 🎉</li>
  <li><b>2023.12</b>: Our paper <i>EEE-QA: Exploring Effective and Efficient Question-Answer Representations</i> has been accepted by <b>AAAI 2024 DEPLOYABLE AI</b>! 🎉</li>
</ul>

</div>
🚀 I am always open to new collaborations and engaging discussions. Feel free to reach out if you are interested in working together or just want to chat!

# 📝 Publications
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2025</div><img src='images/dance_motion.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Human motion video generation: A survey](https://www.techrxiv.org/doi/full/10.36227/techrxiv.172793202.22697340)

Haiwei Xue, Xiangyang Luo, **Zhanghao Hu**, Xin Zhang, Xunzhi Xiang, Yuqin Dai, Jianzhuang Liu, Zhensong Zhang, Minglei Li, Jian Yang, Fei Ma, Zhiyong Wu, Changpeng Yang, Zonghong Dai, Fei Richard Yu

[**Project**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This paper addresses this gap by providing an in-depth survey of human motion video generation, encompassing over ten sub-tasks, and detailing the five key phases of the generation process: input, motion planning, motion video generation, refinement, and output. 
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025 Main</div><img src='images/EmbQA.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Beyond Prompting: An Efficient Embedding Framework for Open-Domain Question Answering](https://arxiv.org/abs/2503.01606)

**Zhanghao Hu**, Hanqi Yan, Qinglin Zhu, Zhenyi Shen, Yulan He, Lin Gui

[**Project**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Reordering retrieved passages to highlight those most likely to contain correct answers by refining query representations via lightweight linear layers under an unsupervised contrastive learning objective.
- Introduce an exploratory embedding that broadens the model's latent semantic space to diversify candidate generation and employs an entropy-based selection mechanism to choose the most confident answer automatically
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL ALVR 2024</div><img src='images/video_causal.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Causal and Temporal Inference in Visual Question Generation by Utilizing Pre-trained Models](https://aclanthology.org/2024.alvr-1.12/)

**Zhanghao Hu**, Frank Keller

[**Project**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Our study introduces a framework that leverages vision-text matching pre-trained models to guide language models in recognizing event-entity relationships within videos and generating inferential questions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">COLING 2024</div><img src='images/eee-qa.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EEE-QA: Exploring Effective and Efficient Question-Answer Representations](https://aclanthology.org/2024.lrec-main.490/)

**Zhanghao Hu***, Yijun Yang*, Junjie Xu*, Yifu Qiu, Pinzhen Chen

[**Project**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This work challenges the existing question-answer encoding convention and explores finer representations. We experiment with different PLMs, and with and without the integration of knowledge graphs. Results prove that the memory efficacy of the proposed techniques is with little sacrifice in performance.
</div>
</div>

# 📝 Publications -- Preprint

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025.02</div><img src='images/codi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CODI: Compressing Chain-of-Thought into Continuous Space via Self-Distillation](https://arxiv.org/abs/2502.21074)

Zhenyi Shen, Hanqi Yan, Linhai Zhang, **Zhanghao Hu**, Yali Du, Yulan He

[**Project**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- CODI (Continuous Chain-of-Thought via Self-Distillation) is a novel framework that distils CoT into a continuous space, where a shared model acts as both teacher and student, jointly learning explicit and implicit CoT while aligning their hidden activation on the token generating the final answer. 
</div>
</div>
  
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


# 💬 Invited Talks

# 💻 Internships
- *2024.04 - 2024.08*, Research Intern at [01.AI](https://www.01.ai/).

<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=lC8xf7GWbLCBnWh7I-lueayltNozk_xR93g5LfejVDI&cl=ffffff&w=a"></script>
