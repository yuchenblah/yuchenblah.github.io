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

I am a Master's student at the Institute of Information Engineering, Chinese Academy of Sciences, advised by Prof. Peng Fu. Currently, I am a research intern at Baidu NLP. And I previously received my B.Sc. in Artificial Intelligence from Beijing Normal University.

My research interests include multimodal large language models (LLMs), model compression, Mixture-of-Experts (MoE), and related topics. Feel free to contact me at: fengyuchen@iie.ac.cn.


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025 Main</div><img src='images/dive.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DIVE into MoE: Diversity-Enhanced Reconstruction of Large Language Models from Dense into Mixture-of-Experts](https://arxiv.org/abs/2506.09351)

**Yuchen Feng**, Bowen Shen*, Naibin Gu, Jiaxuan Zhao, Peng Fu, Zheng Lin, Weiping Wang

[**Pdf**](https://arxiv.org/abs/2506.09351) / [**Code**](https://github.com/yuchenblah/DIVE) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Existing MoE reconstruction methods often overlook the diversity among experts, leading to potential redundancy. We present a Diversity-Enhanced reconstruction method named DIVE, based on the observation that a dense LLM exhibits notable diversity after being pruned on different calibration datasets. The recipe of DIVE includes domain affinity mining, pruning-based expert reconstruction, and efficient retraining, achieving high efficiency with minimal accuracy loss.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> EMNLP 2025 Main</div><img src='images/cbp-tuning.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CBP-Tuning: Efficient Local Customization for Black-box Large Language Models]()

Jiaxuan Zhao, Naibin Gu*, **Yuchen Feng**, Xiyu Liu, Peng Fu, Zheng Lin, Weiping Wang

[**Pdf**]() / [**Code**]() <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose Customized Black-box Prompt Tuning (CBP-Tuning), a novel framework that facilitates efficient local customization while preserving bidirectional privacy. It features a two-stage design: a server-side prompt generator for domain-aware initialization, and user-side gradient-free tuning. The evaluation in the commonsense reasoning, medical and financial domain settings demonstrates superior performance.
</div>
</div>


# 📖 Education
- *2023.09 - Present*, M.Sc. in Computer Science, Institute of Information Engineering, Chinese Academy of Sciences.
- *2019.06 - 2023.09*, B.Sc. in Electronic Information Science and Technology, School of Artificial Intelligence, Beijing Normal University. 


# 💻 Internships
- *2025.04 - Present*, Research Intern, NLP Department (ERNIE Bot), Baidu Inc.