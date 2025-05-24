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

<span class='anchor' id='about-me'></**span**>

I am a Ph.D. student at the HKU-MMLab, the University of Hong Kong, supervised by Prof. [Xihui Liu](https://xh-liu.github.io/). I received my B.Eng. degree at the Department of Automation, Tsinghua University.

My current research focuses on Generative models and Multimodal AI for Computer Vision. More specifically, I am looking into the development of visual tokenizers for better modeling of visual signals for generative AI models.

<!-- AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
 -->

# 🔥 News
- *2025.04*: &nbsp;🎉🎉  Proud to release [GigaTok](https://silentview.github.io/GigaTok/), the first work that successfully scales visual tokenizers to 3B parameters!
- *2024.10*: &nbsp;🎉🎉 (LVD-2M:
A Long-take Video Dataset with Temporally Dense Captions)[https://silentview.github.io/LVD-2M/] (NeurIPS 2024, D&B track) is released! 

# 📝 Publications 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/paper_imgs/LVD-2M.jpg' alt="LVD-2M" loading="lazy" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[LVD-2M: A Long-take Video Dataset with Temporally Dense Captions](https://arxiv.org/abs/2410.10816)

**Tianwei Xiong**, **Yuqing Wang**\*, Daquan Zhou, Zhijie Lin, Jiashi Feng, Xihui Liu


[**Project**](https://silentview.github.io/LVD-2M/) | [**Paper**](https://arxiv.org/abs/2410.10816) | [**Code**](https://github.com/SilentView/LVD-2M)
- This paper introduces LVD-2M, a large-scale long-take video dataset with temporally dense captions.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2024</div><video autoplay muted loop controls style="width: 100%; height: auto;"><source src="images/paper_imgs/EMCID.mov" type="video/quicktime">Your browser does not support the video tag.</video></div></div>
<div class='paper-box-text' markdown="1">

[Editing Massive Concepts in Text-to-Image Diffusion Models
](https://arxiv.org/abs/2403.13807)

**Tianwei Xiong**\*, Yue Wu\*, Enze Xie, Yue Wu, Zhenguo Li, Xihui Liu

[**Project**](https://silentview.github.io/EMCID/) | [**Paper**](https://arxiv.org/abs/2403.13807) | [**Code**](https://github.com/SilentView/EMCID)
- This paper introduces EMCID, a novel method for editing massive concepts in text-to-image diffusion models.
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->