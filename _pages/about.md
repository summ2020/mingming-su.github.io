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

Hi, my name is Mingming Su. I'm a Ph.D. student in Department of Civil Engineering, Zhejiang University, supervised by [Prof. Ning Guo](https://person.zju.edu.cn/nguo). I major in Geotechnical Engineering.

I am majoring in solid mechanics and have rich experience in physical theory, computation, and experiment. I mainly focus on solving Partial Differential Equations of solid mechanics based on the physics-informed neural networks(PINNs), operator learning and deep energy method. My research interest is AI4Science, specifically AI for mechanics.


# 🔥 News
- *2023.09*: &nbsp;🎉🎉 Past PH.D. program in Tsinghua University! I will come to be a first-year Ph.D in Stepember, 2024.
- *2023.08*: &nbsp;🎉🎉 Complete [my second paper](https://arxiv.org/abs/2302.01538) and submit to CMAME!
- *2023.08*: &nbsp;🎉🎉 I have an oral presentation at [CCCM2023](http://www.cccm2023.org/) conference!
- *2023.07*: &nbsp;🎉🎉 I coorperate with my friend [Dr. Liu](https://scholar.google.com/citations?user=vRhyKQoAAAAJ&hl=en) for [the combination between RVE and PINNs](https://arxiv.org/abs/2307.16785).
- *2023.07*: &nbsp;🎉🎉 I participate in [DACOMA-23](http://dacoma.org.cn/) conference and meet with Prof. Rabczuk!
- *2023.05*: &nbsp;🎉🎉 I participate in [DDCM2023](https://www.d-dcm.cn/) and have an oral presentation!
- *2023.03*: &nbsp;🎉🎉 [BINN](https://www.sciencedirect.com/science/article/pii/S0045782523001366) is accepted by CMAME!
- *2022.11*: &nbsp;🎉🎉 I join Microsoft Research as a Research Assistant for [AI4Science](https://www.microsoft.com/en-us/research/lab/microsoft-research-ai4science/)!
- *2022.09*: &nbsp;🎉🎉 I participate in ([DACOMA-22](http://dacoma.org.cn/)) and win the best paper award!
- *2022.08*: &nbsp;🎉🎉 [CENN](https://www.sciencedirect.com/science/article/pii/S0045782522005096) is accepted by CMAME!
- *2022.06*: &nbsp;🎉🎉 I receive my master degree from Tsinghua University!
# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CMAME</div><img src='images/CENN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CENN: Conservative energy method based on neural networks with subdomains for solving variational problems involving heterogeneous and complex geometries](https://www.sciencedirect.com/science/article/pii/S0045782522005096)

**Yizheng Wang**, Jia Sun, Wei Li, Zaiyuan Lu, Yinghua Liu

[**PDF**](https://arxiv.org/pdf/2110.01359.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A deep energy method with subdomains, suitable to solve non-uniform problems with complex boundaries. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CMAME</div><img src='images/BINN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BINN: A deep learning approach for computational mechanics problems based on boundary integral equations](https://www.sciencedirect.com/science/article/pii/S0045782523001366)

Jia Sun, Yinghua Liu, **Yizheng Wang**, Zhenhan Yao, and Xiaoping Zheng

[**PDF**](https://arxiv.org/pdf/2301.04480.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Combine boundary element method with PINNs for the first time. 
</div>
</div>
# 📝 Under Review
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CMAME</div><img src='images/DCEM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A deep complementary energy method for solid mechanics using minimum complementary energy principle](https://arxiv.org/abs/2302.01538)

**Yizheng Wang**, Jia Sun, Timon Rabczuk, and Yinghua Liu

[**PDF**](https://arxiv.org/pdf/2302.01538.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  We propose the deep complementary energy method (DCEM) based on the principle of minimum complementary energy for the first time.   DCEM outperforms DEM in terms of stress accuracy and efficiency and has an advantage in dealing with complex displacement boundary conditions. A deep complementary energy operator method (DCEM-O) by combining operator learning with physical equations is proposed.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Renewable Energy</div><img src='images/RVEPINNs.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multi-scale modeling in thermal conductivity of Polyurethane incorporated with Phase Change Materials using Physics-Informed Neural Networks](https://arxiv.org/abs/2307.16785)

Bokai Liu, **Yizheng Wang**, Timon Rabczuk, Thomas Olofsson, Weizhuo Lu

[**PDF**](https://arxiv.org/pdf/2307.16785.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose a hierarchical multi-scale model RVE utilizing Physics-Informed Neural Networks (PINNs).
</div>
</div>
# 🎖 Honors and Awards
- *2021/2022* Academic Scholarship, Zhejiang University.
- *2020.06* Excellent Graduate and Graduation Thesis, Dalian University of Technology.
- *2017/2018/2019* First-class Academic (top 5%) Scholarship, Dalian University of Technology.
# 📖 Educations
- *2020.09 - future*, Ph.D in Department of Civil Engineering, Zhejiang University, Hangzhou, China
- *2016.09 - 2020.06*, Bachelor from Department of Civil Engineering, Dalian University of Technology, Dalian, China
# 💬 Conference
- *2022.10*, [CMGM-2022](http://www.cmgm.net.cn/), Hangzhou, China: Mingming Su, Ning Guo, Yang Yu and Zhongxuan Yang. “A neural network constitutive model for granular materials based
on thermodynamics”, Oral Presentation.


# 💻 PROFESSIONAL EXPERIENCE
- *2022.06 - 2018.08*, Quantitative Research Assistant at [Nanhua Futures Co., Ltd.](https://www.nanhua.net/), Hangzhou, China.

# [My CV](https://github.com/yizheng-wang/yizheng-wang.github.io/blob/main/docs/YizhengWangCV.pdf) 
