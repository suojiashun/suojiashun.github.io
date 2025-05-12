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

I am currently pursuing a Ph.D. in Computer Science at Beihang University (2023 – present), under the supervision of Professor [Limin Xiao](https://scse.buaa.edu.cn/info/1078/2653.htm) and Professor [Xiaojian Liao](https://liaoxiaojian.github.io/). 
I received my M.Eng. degree from Yunnan University in 2022, under the supervision of Professor [Weisong Shi](https://weisongshi.org/) and Professor [Wei Zhou](http://www.sei.ynu.edu.cn/info/1023/1106.htm). 
I obtained my B.Eng. degree from Hubei Polytechnic University in 2019.

My research interests include **AI/ML Systems** and **Edge Computing**, focusing on performance optimization for AI inference systems and edge AI applications. 
I have published several conference and journal papers in venues such as **ASPLOS**, **IEEE IoT-J**, and **Scientific Data (Nature)**.

<span class='anchor' id='news'></span>

# 🔥 News
- *2025.01*: &nbsp;🎉🎉 CoServe has been accepted by ASPLOS'25.

<span class='anchor' id='research-interests'></span>

# 🔍 Research Interests
**- Efficient and Scalable Systems for AI**  
- CoE (Collaboration-of-Experts) inference/serving systems: [CoServe](https://arxiv.org/pdf/2503.02354) (ASPLOS'25)

**- Edge AI Applications**  
- UAV-based detection systems: [E³-UAV](https://arxiv.org/pdf/2308.04774) (IEEE IoT-J), [HIT-UAV](https://doi.org/10.1038/s41597-023-02066-6) (Scientific Data (Nature))

- Performance evaluation: [Analysis of ML deployment optimization methods](https://doi.org/10.1109/SWC50871.2021.00022) (UIC'21)

<span class='anchor' id='selected-publications'></span>

# 📝 Selected Publications
- [CoServe: Efficient Collaboration-of-Experts (CoE) Model Inference with Limited Memory](https://arxiv.org/pdf/2503.02354)  
**Jiashun Suo**, <span style="color:#8F8F8F">Xiaojian Liao, Limin Xiao, Li Ruan, Jinquan Wang, Xiao Su, Zhisheng Huo</span>  
*ACM International Conference on Architectural Support for Programming Languages and Operating Systems **(ASPLOS)***, 2025. <span style="color:red">(CCF-A)</span>

- [E³-UAV: An Edge-Based Energy-Efficient Object Detection System for Unmanned Aerial Vehicles](https://arxiv.org/pdf/2308.04774)  
Jiashun Suo, <span style="color:#8F8F8F">Xingzhou Zhang, Weisong Shi, Wei Zhou</span>  
*IEEE Internet of Things Journal **(IoT-J)***, 2023. <span style="color:red">(SCI Q1)</span>

- [HIT-UAV: A high-altitude infrared thermal dataset for Unmanned Aerial Vehicle-based object detection](https://doi.org/10.1038/s41597-023-02066-6)  
Jiashun Suo, <span style="color:#8F8F8F">Tianyi Wang, Xingzhou Zhang, Haiyang Chen, Wei Zhou, Weisong Shi</span>  
*Scientific Data (Nature)*, 2023. <span style="color:red">(SCI Q1, Citations 100+)</span>

- [Feasibility analysis of machine learning optimization on GPU-based low-cost edges](https://doi.org/10.1109/SWC50871.2021.00022)  
Jiashun Suo, <span style="color:#8F8F8F">Xingzhou Zhang, Shilei Zhang, Wei Zhou, Weisong Shi</span>  
*IEEE International Conference on Ubiquitous Intelligence and Computing **(UIC)***, 2021. <span style="color:red">(CCF-C)</span>
