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

I am Zhaopeng Qiu (邱昭鹏), a Senior Deep Learning Solutions Architect in NVIDIA. Before joining NVIDIA, I worked as a Senior Researcher at Career Science Lab of BOSS Zhipin and Jarvis Lab of Tencent. I obtained Master in Computer Software and Theory from Peking University in 2018, under supervision of Prof. Yasha Wang. Before that, I obtained Bachelor in Software Engineering from Beihang University (BUAA) in 2014. My research works are focused on recommendation, NLP, and medical data mining.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2024.01*: &nbsp;🎉 Two papers are accepted by WWW 2024.
- *2023.12*: &nbsp;🎉 Two papers are accepted by AAAI 2024.
- *2023.09*: Join NVIDIA.
- *2023.08*: &nbsp;🎉 One paper is accepted by CIKM 2023.
- *2023.06*: Our [LLM4Rec survey]((https://arxiv.org/abs/2305.19860)) has been released. It is the first comprehensive and up-to-date review specifically dedicated to generative LLMs for recommender systems.

# 📝 Publications 

> *\* → Equal contribution; <span class="underlined">The intern under my supervision</span>*

- ``WWW 2024`` [Harnessing Large Language Models for Text-Rich Sequential Recommendation](/), Zhi Zheng, Wen Shuo Chao, **Zhaopeng Qiu**, Hengshu Zhu, Hui Xiong
- ``WWW 2024`` [Causally Debiased Time-aware Recommendation](/), Lei Wang, Chen Ma, Xian Wu, **Zhaopeng Qiu**, Yefeng Zheng, Xu Chen
- ``AAAI 2024`` [A Cross-View Hierarchical Graph Learning Hypernetwork for Skill Demand-Supply Joint Prediction](/), <span class="underlined">Wenshuo Zhao</span>, **Zhaopeng Qiu**, <span class="underlined">Likang Wu</span>, Zhuoning Guo, <span class="underlined">Zhi Zheng</span>, Hengshu Zhu, Hao Liu
- ``AAAI 2024`` [Exploring Large Language Model for Graph Data Understanding in Online Job Recommendations](https://arxiv.org/pdf/2307.05722), <span class="underlined">Likang Wu</span>, **Zhaopeng Qiu**, <span class="underlined">Zhi Zheng</span>, Hengshu Zhu, Enhong Chen
- ``CIKM 2023`` [REST: Drug-Drug Interaction Prediction via Reinforced Student-Teacher Curriculum Learning](/), <span class="underlined">Xinhang Li</span>, **Zhaopeng Qiu**, Xiangyu Zhao, Yong Zhang, Chunxiao Xing, Xian Wu
- ``SIGIR 2023`` [Distributionally Robust Sequential Recommnedation](/), Rui Zhou, Xian Wu, **Zhaopeng Qiu**, Yefeng Zheng and Xu Chen
- ``TOIS`` [Conditional Cross-Platform User Engagement Prediction](https://dl.acm.org/doi/pdf/10.1145/3589226), <span class="underlined">Xinhang Li</span>, **Zhaopeng Qiu**, Jiacheng Jiang, Yong Zhang, Chunxiao Xing and Xian Wu
- ``COLING 2022`` [DeltaNet: Conditional Medical Report Generation for COVID-19 Diagnosis](https://aclanthology.org/2022.coling-1.261.pdf), Xian Wu, Shuxin Yang, **Zhaopeng Qiu**, Shen Ge, Yangtian Yan, Xingwang Wu, Yefeng Zheng, S. Kevin Zhou and Li Xiao
- ``CIKM 2022`` [Gromov-Wasserstein Guided Representation Learning for Cross-Domain Recommendation](https://dl.acm.org/doi/pdf/10.1145/3511808.3557338), <span class="underlined">Xinhang Li</span>, **Zhaopeng Qiu**, Xiangyu Zhao, Zihao Wang, Yong Zhang, Chunxiao Xing and Xian Wu
- ``KDD 2022`` [DDR: Dialogue Based Doctor Recommendation for Online Medical Service](https://doi.org/10.1145/3534678.3539201), <span class="underlined">Zhi Zheng</span>, **Zhaopeng Qiu**, Hui Xiong, Xian Wu, Tong Xu, Enhong Chen, Xiangyu Zhao
- ``NAACL 2022`` (Findings) [Denoising Neural Network for News Recommendation with Positive and Negative Implicit Feedback](https://arxiv.org/pdf/2204.04397.pdf), <span class="underlined">Yunfan Hu</span>, **Zhaopeng Qiu**, Xian Wu
- ``TKDD`` [Graph Neural News Recommendation with User Existing and Potential Interest Modeling](https://doi.org/10.1145/3511708), **Zhaopeng Qiu**, <span class="underlined">Yunfan Hu</span>, Xian Wu
- ``WWW 2022`` [CBR: Context Bias aware Recommendation for Debiasing User Modeling and Click Prediction](https://doi.org/10.1145/3511708), <span class="underlined">Zhi Zheng</span>, **Zhaopeng Qiu**, Tong Xu, Xian Wu, Xiangyu Zhao, Enhong Chen, Hui Xiong
- ``WWW 2022`` [Conditional Generation Net for Medication Recommendation](http://dl.acm.org/citation.cfm?id=3511936), <span class="underlined">Rui Wu</span>, **Zhaopeng Qiu**, Jiacheng Jiang, Guilin Qi, Xian Wu
- ``AAAI 2021`` [U-BERT: Pre-training User Representations for Improved Recommendation](https://ojs.aaai.org/index.php/AAAI/article/download/16557/16364), **Zhaopeng Qiu**, Xian Wu, <span class="underlined">Jingyue Gao</span>, Wei Fan
- ``COLING 2020`` [Automatic Distractor Generation for Multiple Choice Questions in Standard Tests](https://www.aclweb.org/anthology/2020.coling-main.189.pdf), **Zhaopeng Qiu**, Xian Wu, Wei Fan
- ``CIKM 2019`` [Question Difficulty Prediction for Multiple Choice Problems in Medical Exams](https://dl.acm.org/doi/pdf/10.1145/3357384.3358013), **Zhaopeng Qiu**, Xian Wu, Wei Fan
- ``TMC 2018`` [HyTasker: Hybrid Task Allocation in Mobile Crowd Sensing](/), Jiangtao Wang, Feng Wang, Yasha Wang, Leye Wang, **Zhaopeng Qiu**, Daqing Zhang, Bin Guo, Q. Lv

## Pre-Prints
- [Generative Job Recommendations with Large Language Model](https://arxiv.org/pdf/2307.02157), <span class="underlined">Zhi Zheng</span>\*, **Zhaopeng Qiu\***, Xiao Hu, <span class="underlined">Likang Wu</span>, Hengshu Zhu, Hui Xiong
- [A Survey on Large Language Models for Recommendation](https://arxiv.org/abs/2305.19860), <span class="underlined">Likang Wu</span>\*, <span class="underlined">Zhi Zheng</span>\*, **Zhaopeng Qiu\***, Hao Wang, Hongchao Gu, Tingjia Shen, Chuan Qin, Chen Zhu, Hengshu Zhu, Qi Liu, Hui Xiong, Enhong Chen


# 🎖 Honors and Awards
- *2019.10* Second prize in **ICDM 2019 Knowledge Graph Contest**. 

# 📖 Educations
- *2015.09 - 2018.07*, Master, **Peking University**. 
- *2010.09 - 2014.06*, Bachelor, **Beihang University (BUAA)**. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Work Experience
- *2023.09 - present*, **NVIDIA**, Senior Deep Learning Solutions Architect @ AI/ML specialist team.
- *2023.04 - 2023.08*, **BOSS Zhipin**, Senior Researcher @ Career Science Lab.
- *2018.07 - 2023.04*, **Tencent**, Senior Researcher @ [Jarvis Lab](https://jarvislab.tencent.com/).
