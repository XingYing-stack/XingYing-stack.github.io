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

I’m currently a Ph.D. student at the Gaoling School of Artificial Intelligence, Renmin University of China, advised by [Prof. Yankai Lin](https://linyankai.github.io/).

I am also conducting research at [Natural Language Processing Lab at Tsinghua University(THUNLP)](https://nlp.csai.tsinghua.edu.cn/), supervised by [Prof. XinCong](https://scholar.google.com/citations?user=RL9CmXgAAAAJ&hl=zh-CN). My research interest includes Agent and RL Algorithm.

# 🔥 News

- _2025.09_: &nbsp;🎉🎉 [MetaFlowLLM](https://openreview.net/pdf?id=QsQGMijLhL) is accepted to NeurIPS 2025!

# 📝 Publications

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">NeurIPS 2025</div>
      <img src='images/MetaFlowLLM.png' alt="MetaFlowLLM: Generalizing Experience for Language Agents with Hierarchical MetaFlows" width="100%" height="500">
    </div>
  </div>

  <div class='paper-box-text' markdown="1">

  [Generalizing Experience for Language Agents with Hierarchical MetaFlows](https://openreview.net/pdf?id=QsQGMijLhL)

  **Shengda Fan**, Xin Cong, Zhong Zhang, Yuepeng Fu, Yesai Wu, Hao Wang, Xinyu Zhang, Enrui Hu, Yankai Lin

  <!-- [**Code**](#) <strong><span class='show_paper_citations' data='fan-etal-2025-metaflowllm'></span></strong>   -->

  - Proposed the framework *MetaFlowLLM*, a framework that builds a hierarchical exgitperience tree of previously completed tasks for language-agent workflows; it employs a hierarchical MetaFlow merging algorithm to enable experience reuse, leading to a higher success rate on AppWorld and WorkBench

  </div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICLR 2025</div>
      <img src='images/WorkflowLLM.png' alt="WorkflowLLM: Enhancing Workflow Orchestration Capability of Large Language Models" width="100%" height="500">
    </div>
  </div>

  <div class='paper-box-text' markdown="1">

  [WORKFLOWLLM: Enhancing Workflow Orchestration Capability of Large Language Models](https://openreview.net/pdf?id=3Hy00Wvabi)

  **Shengda Fan**, Xin Cong, Yuepeng Fu, Zhong Zhang, Shuyan Zhang, Yuanwei Liu, Yesai Wu, Yankai Lin†, Zhiyuan Liu, Maosong Sun

  [**Code**](https://github.com/OpenBMB/WorkflowLLM) 

  - Introduced *WorkflowLLM*, a data‑centric framework to improve the orchestration capabilities of large language models (LLMs) by constructing a large dataset (WorkflowBench) and fine‑tuning an LLM to yield strong performance on previously unseen APIs and instructions.

  </div>

</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">EMNLP 2024</div>
      <img src='images/LogicST.png' alt="LogicST: A Logical Self‑Training Framework" width="100%">
    </div>
  </div>

  <div class='paper-box-text' markdown="1">

  [LogicST: A Logical Self‑Training Framework for Document‑Level Relation Extraction with Incomplete Annotations](https://aclanthology.org/2024.emnlp-main.314/)  

  **Shengda Fan**, Yanting Wang, Shasha Mo, Jianwei Niu  

  [**Code**](https://github.com/XingYing-stack/LogicST) 

  - Introduced LogicST, a neural-logical self-training framework that diagnoses pseudo-label conflicts through logical rules, improving the performance of document-level relation extraction tasks.

  </div>

</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">EMNLP 2022</div>
      <img src='images/MILR.png' alt="Boosting Document‑Level Relation Extraction by Mining and Injecting Logical Rules" width="100%">
    </div>
  </div>

  <div class='paper-box-text' markdown="1">
  [Boosting Document‑Level Relation Extraction by Mining and Injecting Logical Rules](https://aclanthology.org/2022.emnlp-main.704/)  
  **Shengda Fan**, Shasha Mo, Jianwei Niu  
  [**Code**](https://github.com/XingYing-stack/MILR)  
  - Proposed MILR, a framework that mines logical rules from annotations and injects them into the training and inference process to improve consistency and F1 scores in Document Relation Extraction.
  </div>
</div>

- [MiniCPM4: Ultra-Efficient LLMs on End Devices.](https://arxiv.org/abs/2506.07900)

- [Key Mention Pairs Guided Document‑Level Relation Extraction](https://aclanthology.org/2022.coling-1.165/),  Feng Jiang, Jianwei Niu, Shasha Mo, **Shengda Fan**, **COLING 2022**

- [CETA: A Consensus Enhanced Training Approach for Denoising in Distantly Supervised Relation Extraction](https://aclanthology.org/2022.coling-1.197/), Ruri Liu, Shasha Mo, Jianwei Niu, **Shengda Fan**, **COLING 2022**

<!-- # 🎖 Honors and Awards

- _2021.10_ Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- _2021.09_ Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->

# 📖 Educations

- _2024.09 - now_, PHD student, Renmin University of China, Beijing.
- _2021.09 - 2024.06_, Mater, Beihang University, Beijing.
- _2017.09 - 2021.06_, Bachelor, Beihang University, Beijing.

<!-- # 💬 Invited Talks

- _2021.06_, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- _2021.03_, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. \| [\[video\]](https://github.com/) -->

# 💻 Internships

- _2023.09 – 2023.11_, Research Intern, E Fund Management Co., Ltd., Guangzhou.
- _2023.04 – 2023.10_, Algorithm Engineer, Tiktok Live, ByteDance, Beijing.
