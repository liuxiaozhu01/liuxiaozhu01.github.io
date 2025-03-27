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

Hi there 👋. This is Liu Zujing(刘祖靖), a Master student at [Captain](http://www.captain-whu.com/en/team/) in Wuhan University, China since 2023, advised by [Prof.Gui-song Xia](http://www.captain-whu.com/zh/person/xiaguisong.html) and [Prof.Yuan Gao](https://yuan-gao.net/). I obtained my bachelor degree in Computer Science and Technology also in Wuhan University and got the Honor Degree from Hongyi Honor College.

I’m currently working on model compression and inference acceleration on LLMs and MLLMs, including:
- 🔭 Structural Pruning, Knowledge Distillation and Quantization.
- 🖥️ KV Cache Optimization and Implicit Chain of Thought (CoT) Inference

# 💻 Internships
<p style="font-size: 1.2em; margin-top: 15px"><b>I'm actively seeking internship and visiting opportunities 🥺🤗</b></p>

# 🔥 News
- *2024.06*: &nbsp;🎉🎉 Our paper on optimization-based structural pruning is available on [Arxiv](https://arxiv.org/abs/2406.10576), with latest update on 2024.10.
- *2023.09*: &nbsp;🎉🎉 Back to WHU and start to work towards a Masters Degree.
- *2023.06*: &nbsp;🎉🎉 Got my bachelor degree from WHU! Farewell all my friends!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='https://arxiv.org/html/2406.10576v1/extracted/5669159/imgs/overview5.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[(🎈NEW)**Bypass Back-propagation: Optimization-based Structural Pruning for Large Language Models via Policy Gradient**](https://arxiv.org/abs/2406.10576)

Yuan Gao<sup>*</sup>, **Zujing Liu**<sup>*</sup>, Weizhong Zhang, Bo Du, Gui-Song Xia

- A novel optimization-based structural pruning method for LLM that optimizes directly for model loss.
- Learning pruning mask using Bernoulli distribution via policy gradient estimator to avoid back-propagation.
- Superior performance compared to existing techniques, with efficient computation on a single GPU.


<p style="margin-top: 20px; font-size: 0.9em"><sup>*</sup> Equal contribution</p>
<!-- <sup>*</sup> Equal contribution -->
</div>
</div>


# 🎖 Honors and Awards
- *2019-2023(B.Eng.)* Second-Class Academic Scholarship of Wuhan University (Top 10%), Outstanding Students of Wuhan University (Top 10%)

# 📖 Educations
- *2023.09 - (now)*, M.Eng. in Computer Science, School of Computer, Wuhan University
- *2019.09 - 2023.06*, B.Eng. in Computer Science, School of Computer, Wuhan University

<!-- # 💻 Internships
**I'm actively seeking internship and visiting opportunities 🥺🤗** -->