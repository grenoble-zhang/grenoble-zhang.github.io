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

# 🥳 About Me
I am a first-year Ph.D student of ***SILab*** at ***The Chinese University of Hong Kong, Shenzhen (CUHKSZ)***, under the supervision of Prof. ***Li Jiang*** [-- homepage](https://llijiang.github.io/). I obtained my M.S. in Computer Science at ***the University of Chinese Academy of Sciences (UCAS)*** in 2024 and B.S at ***Shandong University (SDU)*** in 2021. I was also fortunate to be an internship at Tsinghua AIR <img src="./images/Tsinghua.png" style="height: 1em; vertical-align: text-bottom; object-fit: contain;">, Huawei <img src="./huawei_icon.png" style="height: 1em; vertical-align: text-bottom; object-fit: contain;">, TeleAI <img src="./teleai_icon.png" style="height: 1em; vertical-align: text-bottom; object-fit: contain;">.
<!-- , Kuaishou-Kling <img src="./Kuaishou_icon.png" style="height: 1em; vertical-align: text-bottom; object-fit: contain;"><img src="./Kling_icon.png" style="height: 1em; vertical-align: text-bottom; object-fit: contain;">, Tecent-Hunyuan. -->

My research interests lie in the intersection of ***Computer Vision and Machine Learning***. Now, I focus on designing novel applications for ***image/video generation, World model, autoregressive-generation*** and other downstream AIGC tasks.

<span style="color:red;">I am actively looking for internship opportunities and coauthors!</span>

<span class='anchor' id='-educations'></span>

# 📖 Educations
- *2024.10 - up-to-now, Phd, School of Data Science,*  ***The Chinese University of Hong Kong, Shenzhen.*** <img src="./images/cuhk_1em.jpg" style="height: 1em; vertical-align: text-bottom; object-fit: contain;">
- *2021.09 - 2024.06, M.S.  degree, School of Computer Science and Technology,* ***University of Chinese Academy of Sciences.*** <img src="./images/ucas_1em.png" style="height: 1em; vertical-align: text-bottom; object-fit: contain;">
- *2017.09 - 2021.06, B.S.  degree, School of Mechanical, Electrical & Information Engineering,* ***Shandong University.*** <img src="./images/SDU_1em.jpg" style="height: 1em; vertical-align: text-bottom; object-fit: contain;">

<span class='anchor' id='-publications'></span>

# 📝 Publications/Preprints - main contribution
*Equal contribution

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGGRAPH Asia 2025</div><img src='images/ProteusID.jpg' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[Proteus-ID: ID-Consistent and Motion-Enhanced Video Customization](https://arxiv.org/abs/2506.23729)

**Guiyu Zhang**, Chen Shi, Zijian Jiang, Xunzhi Xiang, Jingjing Qian, Shaoshuai Shi, Li Jiang.

[**Paper**](https://arxiv.org/abs/2506.23729) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Project**](https://grenoble-zhang.github.io/Proteus-ID/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Code**](https://github.com/grenoble-zhang/Proteus-ID) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/Ctrl-U.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[Ctrl-U: Robust Conditional Image Generation via Uncertainty-aware Reward Modeling](https://arxiv.org/abs/2410.11236)

**Guiyu Zhang**, Huan-ang Gao, Zijian Jiang, Hao Zhao, Zhedong Zheng

[**Paper**](https://arxiv.org/abs/2410.11236) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Project**](https://grenoble-zhang.github.io/Ctrl-U-Page/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Code**](https://github.com/grenoble-zhang/Ctrl-U) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv 2025</div><img src='images/MMPL.jpg' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[Macro-from-Micro Planning for High-Quality and Parallelized Autoregressive Long Video Generation](https://nju-xunzhixiang.github.io/Anchor-Forcing-Page/)

Xunzhi Xiang<sup>*</sup>, Yabo Chen<sup>*</sup>, <strong>Guiyu Zhang</strong><sup>*</sup>, Zhongyu Wang, Zhe Gao, Quanming Xiang, Gonghu Shang, Junqi Liu, Haibin Huang, Yang Gao, Chi Zhang, Qi Fan, et al.

[**Paper**](https://arxiv.org/abs/2508.03334) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'>
[**Project**](https://nju-xunzhixiang.github.io/Anchor-Forcing-Page/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Code**](https://github.com/Tele-AI/MMPL) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2024 (Spotlight)</div><img src='images/FairDiff.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[FairDiff: Fair Segmentation with Point-Image Diffusion](https://arxiv.org/abs/2407.06250)

Wenyi Li<sup>*</sup>, Haoran Xu<sup>*</sup>, <strong>Guiyu Zhang</strong><sup>*</sup>, Huan-ang Gao, Mingju Gao, Mengyu Wang, Hao Zhao

[**Paper**](https://arxiv.org/abs/2407.06250) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Code**](https://github.com/wenyi-li/FairDiff) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

# 🔥 Publications/Preprints - participating contribution
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv 2026</div><img src='images/TTO.jpg' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[Few-Step Video Diffusion Plans Semantics Early: Pathwise Test-Time Optimization along the Sampling Trajectory](https://arxiv.org/abs/2511.12633)

Xunzhi Xiang, Zixuan Duan, **Guiyu Zhang**, Haiyu Zhang, Zhe Gao, Junta Wu, Shaofeng Zhang, Tengfei Wang, Qi Fan, Chunchao Guo.

[**Paper**](https://arxiv.org/abs/2511.12633) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv 2025</div><img src='images/DenoisingVAE.jpg' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[Denoising Vision Transformer Autoencoder with Spectral Regularization](https://arxiv.org/abs/2511.12633)

Xunzhi Xiang, Xingye Tian, **Guiyu Zhang**, Yabo Chen, Shaofeng Zhang, Xuebo Wang, Xin Tao, Qi Fan.

[**Paper**](https://arxiv.org/abs/2511.12633) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<span class='anchor' id='-honors-and-awards'></span>

# 🎖 Honors and Awards
- *2020.8* Nation College Student Intelligent Car Competition First Prize.
- *2020.8* National University Student Contest on Energy Saving & Emission Reduction Second Prize.