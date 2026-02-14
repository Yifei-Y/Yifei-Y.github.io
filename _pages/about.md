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

I am a fourth-year PhD (Sep. 2022 - ) student in Control Science and Engineering department at <a href="https://www.zju.edu.cn/english/">Zhejiang University</a>. I belong to Robotics Lab, advised by Prof. <a href="https://ywang-zju.github.io/">Yue Wang</a> and <a href="https://person.zju.edu.cn/en/rongxiong">Rong Xiong</a>. I obtained my B.Eng (Sep. 2018 - Jun. 2022) in Control Science and Engineering from Zhejiang University with an honor degree at Chu Kochen Honor College.

My current research interests lie in robotic manipulation and embodied AI. My prior work also includes computer vision.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2026.01*: &nbsp;🎉 <a href="https://arxiv.org/abs/2509.14630">E2VLA</a> is accepted by ICRA 2026. 
- *2025.08*: &nbsp;🎉 <a href="https://arxiv.org/abs/2503.09423">A2</a> is accepted by TASE 2025.
- *2025.06*: &nbsp;🎉 <a href="https://arxiv.org/abs/2503.23835">PTDGS</a> is accepted by IROS 2025.

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2025</div><img src='images/2025PseudoTactile_yang.gif' alt="sym" width="200%"></div></div>
<div class='paper-box-text' markdown="1">

**Disambiguate Gripper State in Grasp-Based Tasks: Pseudo-Tactile as Feedback Enables Pure Simulation Learning**

**Yifei Yang**, Lu Chen, Zherui Song, Yenan Chen, Wentao Sun, Zhongxiang Zhou, Rong Xiong, Yue Wang

[**arXiv**](https://arxiv.org/abs/2503.23835) /
[**IEEE**](https://ieeexplore.ieee.org/document/11246513) /
[**project**](https://yifei-y.github.io/project-pages/Pseudo-Tactile-Feedback/)
[**video**](https://www.bilibili.com/video/BV1DZZxYGEk6/?vd_source=16bffa885f8d40c0678b340384dd56db)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L 2024</div><img src='images/2024DORec_wu.jpg' alt="sym" width="200%"></div></div>
<div class='paper-box-text' markdown="1">

**DORec: Decomposed Object Reconstruction and Segmentation Utilizing 2D Self-Supervised Features**

Jun Wu, Sicheng Li, Sihui Ji, **Yifei Yang**, Yue Wang, Rong Xiong, Yiyi Liao

[**arXiv**](https://arxiv.org/abs/2310.11092) /
[**IEEE**](https://ieeexplore.ieee.org/document/10777610)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2024</div><img src='images/2024nuDBA_mao.png' alt="sym" width="200%"></div></div>
<div class='paper-box-text' markdown="1">

**$\nu$-DBA: Neural Implicit Dense Bundle Adjustment Enables Image-Only Driving Scene Reconstruction**

Yunxuan Mao, Bingqi Shen, **Yifei Yang**, Kai Wang, Rong Xiong, Yiyi Liao, Yue Wang

[**arXiv**](https://arxiv.org/abs/2404.18439) /
[**IEEE**](https://ieeexplore.ieee.org/document/10801847)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L 2024</div><img src='images/2024SemSeg_yang.png' alt="sym" width="200%"></div></div>
<div class='paper-box-text' markdown="1">

**Class Semantics Modulation for Open-Set Instance Segmentation**

**Yifei Yang**, Zhongxiang Zhou, Jun Wu, Yue Wang, Rong Xiong

[**IEEE**](https://ieeexplore.ieee.org/document/10388394) /
[**project**](https://yifei-y.github.io/project-pages/SemSeg/) /
[**code**](https://github.com/Yifei-Y/SemSeg)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L 2023</div><img src='images/2023OpensetRCNN_zhou.gif' alt="sym" width="200%"></div></div>
<div class='paper-box-text' markdown="1">

**Open-Set Object Detection Using Classification-free Object Proposal and Instance-level Contrastive Learning**

Zhongxiang Zhou, **Yifei Yang**, Yue Wang, Rong Xiong

[**arXiv**](https://arxiv.org/abs/2211.11530) /
[**IEEE**](https://ieeexplore.ieee.org/document/10035923) /
[**project**](https://sites.google.com/view/openset-rcnn/) /
[**code**](https://github.com/Yifei-Y/Openset-RCNN)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/2023UrbanGIRAFFE_yang.gif' alt="sym" width="200%"></div></div>
<div class='paper-box-text' markdown="1">

**UrbanGIRAFFE: Representing Urban Scenes as Compositional Generative Neural Feature Fields**

Yuanbo Yang, **Yifei Yang**, Hanlei Guo, Rong Xiong, Yue Wang, Yiyi Liao

[**arXiv**](https://arxiv.org/abs/2303.14167) /
[**project**](https://lv3d.github.io/urbanGIRAFFE) /
[**code**](https://github.com/freemty/urbanGIRAFFE)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/2022ControlVAE_shao.png' alt="sym" width="200%"></div></div>
<div class='paper-box-text' markdown="1">

**Rethinking Controllable Variational Autoencoders**

Huajie Shao\*, **Yifei Yang**\*, Haohong Lin\*, Longzhong Lin, Yizhuo Chen, Qinmin Yang, Han Zhao

[**pdf**](https://openaccess.thecvf.com/content/CVPR2022/papers/Shao_Rethinking_Controllable_Variational_Autoencoders_CVPR_2022_paper.pdf)

</div>
</div>


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
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.