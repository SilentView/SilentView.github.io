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

I am a Ph.D. student at [MMLab@HKU](https://mmlab.hk/), the University of Hong Kong, supervised by Prof. [Xihui Liu](https://xh-liu.github.io/). I received my B.Eng. degree at the Department of Automation, Tsinghua University.

My research focuses on Generative models and Multimodal AI in Computer Vision. More specifically, I am currently dedicated to the development of visual tokenizers for better modeling of visual signals for generative AI models.

<!-- AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
 -->

# 🔥 News
- *2026.02*: [EVATok](https://silentview.github.io/EVATok/) is accepted by CVPR 2026!
- *2025.06*: [GigaTok](https://silentview.github.io/GigaTok/) is accepted by ICCV 2025!
- *2025.04*: &nbsp;🎉🎉  Proud to release [GigaTok](https://silentview.github.io/GigaTok/), the first work that successfully scales visual tokenizers to 3B parameters!
- *2024.10*: &nbsp;🎉🎉 [LVD-2M: A Long-take Video Dataset with Temporally Dense Captions](https://silentview.github.io/LVD-2M/) (NeurIPS 2024, D&B track) is released! 


# 💻 Internships
- *2023.07 - 2023.09*, Research Assistant, [HKU-IDS](https://datascience.hku.hk/)
- *2024.02 - 2025.12*, Research Intern, [ByteDance-Seed](https://seed.bytedance.com/en/)
- *2026.02 - now*, Research Intern, [Tencent Hunyuan](https://github.com/Tencent-Hunyuan)

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/paper_imgs/EVATok.jpg' alt="GigaTok" loading="lazy" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[EVATok: Adaptive Length Video Tokenization for Efficient Visual Autoregressive Generation](https://arxiv.org/abs/2603.12267)

**Tianwei Xiong**, Jun Hao Liew, Zilong Huang, Zhijie Lin, Jiashi Feng, Xihui Liu


[**Project**](https://silentview.github.io/EVATok/) | [**Paper**](https://arxiv.org/abs/2603.12267) | [**Code**](https://github.com/HKU-MMLab/EVATok)
- We propose an adaptive length video tokenization scheme to improve the efficiency of visual autoregressive generation.
- EVATok achieves significant speedup while maintaining high reconstruction quality and generation performance.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/paper_imgs/GigaTok.jpg' alt="GigaTok" loading="lazy" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[GigaTok: Scaling Visual Tokenizers to 3 Billion Parameters for Autoregressive Image Generation
](https://arxiv.org/abs/2504.08736)

**Tianwei Xiong**, Jun Hao Liew, Zilong Huang, Jiashi Feng, Xihui Liu

[**Project**](https://silentview.github.io/GigaTok/) | [**Paper**](https://arxiv.org/abs/2504.08736) | [**Code**](https://github.com/SilentView/GigaTok)
- We propose solutions for reconstruction vs. generation delimma for scaling tokenizers.
- GigaTok is the first work that successfully scales visual tokenizers to 3 billion parameters!
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/paper_imgs/LVD-2M.jpg' alt="LVD-2M" loading="lazy" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[LVD-2M: A Long-take Video Dataset with Temporally Dense Captions](https://arxiv.org/abs/2410.10816)

**Tianwei Xiong**\*, Yuqing Wang\*, Daquan Zhou, Zhijie Lin, Jiashi Feng, Xihui Liu


[**Project**](https://silentview.github.io/LVD-2M/) | [**Paper**](https://arxiv.org/abs/2410.10816) | [**Code**](https://github.com/SilentView/LVD-2M)
- We pay special attention to long-take videos without cuts.
- We propose a data pipeline for filtering high-quality long-take videos and the temporally dense captioning of the videos.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2024</div><img src='images/paper_imgs/EMCID.gif' alt="EMCID" loading="lazy" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[Editing Massive Concepts in Text-to-Image Diffusion Models
](https://arxiv.org/abs/2403.13807)

**Tianwei Xiong**\*, Yue Wu\*, Enze Xie, Yue Wu, Zhenguo Li, Xihui Liu

[**Project**](https://silentview.github.io/EMCID/) | [**Paper**](https://arxiv.org/abs/2403.13807) | [**Code**](https://github.com/SilentView/EMCID)
- EMCID can edit massive concepts in text-to-image diffusion models, with limited costs and minimal negative effects on the performances.  
</div>
</div>


# 🎖 Honors and Awards
-  HKU Presidential PhD Scholarship (HKU-PS) and Hong Kong PhD Fellowship (HKPF). 2024-2025

<!-- # 📖 Educations
- *2020.09 - 2024.06*, 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 💬 Academic Services
- I served as a reviewer for CVPR and NeurIPS.


