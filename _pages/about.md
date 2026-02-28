---
permalink: /
title: "Boyu Guan (管博宇) - NLP and Multimodal LLM Research"
description: "Ph.D. student at CASIA working on NLP, multimodal large language models, and video-guided machine translation."
author_profile: true
layout: single
redirect_from: 
  - /about/
  - /about.html
---



<!-- ## **Boyu Guan (管博宇)** -->

I am currently a Ph.D. student at the **Institute of Automation, Chinese Academy of Sciences**, and a member of the **State Key Laboratory of Multimodal Artificial Intelligence Systems**, where I am advised by [**Prof. Chengqing Zong (宗成庆)**](https://nlpr.ia.ac.cn/cip/cqzong.htm) and [**Assoc. Prof. Yang Zhao (赵阳)**](https://yzhaoiacas.netlify.app/).


My research lies at the intersection of **Natural Language Processing (NLP)** and **Multimodal Large Language Models (MLLMs)**, with a current focus on **Video-Guided Machine Translation (VMT)**. In this line of work, I explore how visual and linguistic signals can be effectively fused to enhance translation performance and efficiency.

Looking ahead, I am particularly interested in expanding my research to **video question answering** and broader topics in **multimodal understanding**.

<!-- You can find my CV here: [**Boyu Guan's Curriculum Vitae**](../../files/CV_BoyuGuan.pdf). -->
If you're interested in collaboration or would like to chat, feel free to reach out to me at *guanboyu2022[at]ia.ac.cn*.

<!-- # 🔥<span style="color:red; font-weight:bold;">Seeking internship opportunities in NLP and Multimodal LLMs.</span>🔥 -->


---


# 📚 Education:
- **2022.09 – 2027.06 (Expected)** Ph.D. in Computer Science at the *Institute of Automation, Chinese Academy of Sciences*, Beijing, China
  - Research interests: **Multimodal Large Language Models, Video Understanding, and Multilingual (Machine Translation)**
  - Conducted research under [**Prof. Chengqing Zong (宗成庆)**](https://nlpr.ia.ac.cn/cip/cqzong.htm) at the **State Key Laboratory of Multimodal Artificial Intelligence Systems**.

- **2018.09 – 2022.06** B.Sc. in Mathematics, *School of Science, Northeastern University*, Shenyang, China
  - GPA: 3.76 / 5.00, Rank 3 / 31; admitted to a direct PhD program via top-10% recommendation.



---

# 📰 News:
- **2025.09**: 👨‍🏫 I will serve as a teaching assistant for the Fall 2025 undergraduate course Practical Natural Language Processing at the University of Chinese Academy of Sciences (UCAS).
- **2025.08**: 🎉🎉 Our paper was accepted to **EMNLP 2025 main conference**, looking forward to seeing you in Suzhou.
- **2025.03**: 👨‍🏫 I will serve as a teaching assistant for the Spring 2025 Natural Language Processing course for Ph.D. students at Zhongguancun Academy.
- **2024.12**: 🎉🎉 Our paper was accepted to **COLING 2025 (oral)**! Looking forward to seeing you in Abu Dhabi.
- **2024.09**: 👨‍🏫 I will serve as a teaching assistant for the Fall 2024 undergraduate course Practical Natural Language Processing at the University of Chinese Academy of Sciences (UCAS).



---

# Publications {#publications}

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>. <sup>*</sup> Equal contribution. <sup>#</sup> Corresponding author. </div>
{% endif %}

{% include base_path %}


<!-- <br> -->
<!-- <br> -->

## Video-guided Machine Translation

{% assign post = site.publications | where: "slug", "2025-08-SHIFT" | first %}
{% include archive-single-paper-box.html %}

--- 

{% assign post = site.publications | where: "slug", "2025-01-TriFine" | first %}
{% include archive-single-paper-box.html %}


---


## Patent

### 1. A Video Machine Translation Method and Device Integrating Fine-Grained Multimodal Information
*(Invention Patent Under Substantive Examination)*  
&nbsp;&nbsp;&nbsp;&nbsp;**Authors:** Yang Zhao (Advisor), **Boyu Guan**, Yining Zhang, Chengqing Zong


### 2. An Adaptive Key Frame Selection Method for Video Machine Translation

*(Invention Patent Under Substantive Examination)*  
&nbsp;&nbsp;&nbsp;&nbsp;**Authors:** Yang Zhao (Advisor), **Boyu Guan**, Chuang Han, Chengqing Zong



# 💻 Internships
- **2023.02 – 2023.08** Software Engineering Intern, *Biren Technology (壁仞科技)*, Beijing, China.  
  - Participated in adapting and optimizing large-scale model pre-training and inference pipelines, including porting key mechanisms such as activation checkpointing and 3D parallelism, and integrating training frameworks DeepSpeed and Megatron-DeepSpeed.
  - Conducted operator extraction, migration, and end-to-end pipeline optimization for mainstream LLMs (e.g., LLaMA, LLaMA2, Qwen), improving overall training and inference performance.
 <!-- Worked on the migration and optimization of pre-training and inference pipelines for large language models (LLMs), including **LLaMA**, **LLaMA2**, and **ChatGLM**. Responsibilities included architecture adaptation and efficiency improvements such as **activation checkpointing**. -->
