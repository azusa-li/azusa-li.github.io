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

I am currently an intern at M-A-P community, working on Multi-agent systems and AI alignment research. Multimodal Art Projection (M-A-P) is an open-source AI research community. Recently I completed my M.Sc. in Big Data Technology from The Hong Kong University of Science and Technology (HKUST) in October 2024, and received my B.Eng. in Computer Science and Technology from Zhejiang University in September 2023. 

My research interests primarily focus on multi-agent systems, LLM agents, and Code LLMs. I am particularly passionate about developing intelligent systems that can collaborate effectively and understand complex programming tasks. Previously, I worked as a research intern at HKGAI, HKUST (December 2023 - May 2024) under the supervision of Professor [Jie Fu](https://bigaidream.github.io/).

I am currently seeking **<span style="color: red">PhD positions for 2025 Fall</span>**. If you are interested in my research work, or if you have any questions about potential collaboration, please feel free to reach out at [15071186776@163.com](mailto:15071186776@163.com). 
<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2024.10*: &nbsp;🎉🎉 Released AutoKaggle, a multi-agent framework for automated data science tasks.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/AutoKaggle.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AutoKaggle: A Multi-Agent Framework for Autonomous Data Science Competitions](https://arxiv.org/pdf/2410.20424)

**Ziming Li**, Qianbo Zang, David Ma, Jiawei Guo, Tuney Zheng, Minghao Liu, Xinyao Niu, Yue Wang, Jian Yang, Jiaheng Liu, Wanjun Zhong, Wangchunshu Zhou, Wenhao Huang, Ge Zhang

<!-- [**Project**](https://github.com/multimodal-art-projection/AutoKaggle) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
[**Project**](https://github.com/multimodal-art-projection/AutoKaggle) | <a href='https://github.com/multimodal-art-projection/AutoKaggle'><img src="https://img.shields.io/github/stars/multimodal-art-projection/AutoKaggle?style=social" alt="GitHub stars"></a> <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Existing automated data science systems are oversimplified, inflexible, and lack transparency, making them inadequate for complex real-world data science tasks. 
- We develop AutoKaggle, an end-to-end multi-agent framework that integrates phase-based workflows, iterative debugging, and comprehensive reporting systems to provide data scientists with efficient, reliable, and transparent automated solutions.
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/CodeEditorBench.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CodeEditorBench: Evaluating Code Editing Capability of Large Language Models](https://arxiv.org/pdf/2404.03543)

Jiawei Guo, **Ziming Li**, Xueling Liu, Kaijing Ma, Tianyu Zheng, Zhouliang Yu, Ding Pan, Yizhi LI, Ruibo Liu, Yue Wang, Shuyue Guo, Xingwei Qu, Xiang Yue, Ge Zhang, Wenhu Chen, Jie Fu

[**Project**](https://github.com/CodeEditorBench/CodeEditorBench) | <a href='https://github.com/CodeEditorBench/CodeEditorBench'><img src="https://img.shields.io/github/stars/CodeEditorBench/CodeEditorBench?style=social" alt="GitHub stars"></a> <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Existing frameworks focus heavily on code generation, lacking systematic evaluation of code editing abilities. Code editing is crucial in software development, requiring dedicated evaluation benchmarks.
- We establish CodeEditorBench as the first comprehensive framework for evaluating LLMs' code editing capabilities and advance code editing technology through open-source datasets and evaluation tools.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/Medagents.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MedAgents: Large Language Models as Collaborators for Zero-shot Medical Reasoning](https://arxiv.org/pdf/2311.10537)

Xiangru Tang, Anni Zou, Zhuosheng Zhang, **Ziming Li**, Yilun Zhao, Xingyao Zhang, Arman Cohan, Mark Gerstein

[**Project**](https://github.com/gersteinlab/MedAgents) | <a href='https://github.com/gersteinlab/MedAgents'><img src="https://img.shields.io/github/stars/gersteinlab/MedAgents?style=social" alt="GitHub stars"></a> <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Current LLMs face challenges in medical domains due to limited domain knowledge and reasoning capabilities, necessitating a solution that doesn't require additional training.
- We design a framework that simulates multi-disciplinary expert collaboration through role-playing and multi-round discussions to activate LLMs' latent medical knowledge and enhance their reasoning abilities.
</div>
</div>


<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2023.09 - 2024.10*, M.Sc. in Big Data Technology, The Hong Kong University of Science and Technology (HKUST)
- *2019.09 - 2023.06*, B.Eng. in Computer Science and Technology, College of Computer Science and Technology, Zhejiang University

# 💻 Internships
- *2024.06 - present*, M-A-P
- *2023.12 - 2024.05*, HKGAI, HKUST