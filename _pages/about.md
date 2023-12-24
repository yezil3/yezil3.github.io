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

I'm a third-year Ph.D. student at University of California Irvine. My research interests are Trustworthy AI, Graph Neural Networks, and Data-centric AI. 

Selected Publications
======
- Error Detection on Knowledge Graphs with Triple Embedding. [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10289852)
  - **Yezi Liu**, Qinggang Zhang, Mengnan Du, Xiao Huang, Xia Hu
  - EUSIPCO 2023.
- Contrastive knowledge graph error detection. [Paper](https://dl.acm.org/doi/pdf/10.1145/3511808.3557264)
  - Qinggang Zhang, Junnan Dong, Keyu Duan, Xiao Huang, **Yezi Liu**, Linchuan Xu
  - CIKM 2022.
- Explaining dynamic graph neural networks via relevance back-propagation. [Paper](https://arxiv.org/pdf/2207.11175.pdf)
  - **Yezi Liu**, Jiaxuan Xie, Yanning Shen
  - Under review.
