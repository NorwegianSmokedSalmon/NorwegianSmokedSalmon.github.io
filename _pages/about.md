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

I am currently a first-year master's student majoring in robotics at Zhejiang University, under the supervision of <a href='https://scholar.google.com/citations?hl=en&user=4RObDv0AAAAJ&view_op=list_works&sortby=pubdate'>Pro. Fei Gao<strong><span id='total_cit'></span></strong></a>. Also, I am fortunate to be guided by <a href='https://scholar.google.com/citations?hl=en&user=DvrngV4AAAAJ'>Pro. Xieyuanli Chen<strong><span id='total_cit'></span></strong></a>. My research interests now lie in World Model, Manipulation, 3D Geometry and diffusion policy, specially focusing on Physics Modeling in Real World. Previously, I studied Multi-Sensor Fusion and Robot Mapping with a concentration on Multi-Session Mapping and LiDAR Visual Fusion.

I obtained my Bachelor Degree of Engineering majoring in **Robotics Engineering** with an honor degree at **Chu Kochen Honors College**, **Zhejiang University** in 2025.
During my undergraduate years, I participate in research and competitions, closely collaborating with <a href='https://scholar.google.com/citations?user=tpOOC4zBfZ8C&hl=en'>Pro. Yu Zhang<strong><span id='total_cit'></span></strong></a>, <a href='https://scholar.google.com/citations?hl=en&user=1hI9bqUAAAAJ'>Pro. Rong Xiong<strong><span id='total_cit'></span></strong></a>, and <a href='https://scholar.google.com/citations?user=N543LSoAAAAJ&hl=en'>Pro. Yue Wang<strong><span id='total_cit'></span></strong></a>. In competitions, I'm the team leader of <a href='https://github.com/ZJUNlict'>ZJUNlict<strong><span id='total_cit'></span></strong></a>, Zhejiang University's team in the <a href='https://ssl.robocup.org/'>RoboCup Soccer Small Size League (SSL)<strong><span id='total_cit'></span></strong></a> from 2024 to 2025, and work as a mentor in 2026. As a core member, I have worked with the team to achieve multiple awards.

# 🔥 News
- *2026.06*: &nbsp;🎉🎉 Our paper "High-Speed Vision-Based Flight in Clutter with Safety-Shielded Reinforcement Learning" is accepted to RA-L.
- *2026.05*: &nbsp;🎉🎉 I won the Zhejiang Provincial Competition championship as the mentor of ZJUNlict.
- *2026.02*: &nbsp;🎉🎉 Our paper LiDAR-VGGT is accepted to 2026 RA-L!
- *2026.02*: &nbsp;🎉🎉 The firstly proposed color point cloud evaluation tool from RISED is open-sourced [**repo**](https://github.com/changjianjiang01/RISED).
- *2025.02*: &nbsp;🎉🎉 Our paper RISED is accepted to 2025 ICRA!
- *2024.07*: &nbsp;🎉🎉 We win the second place in the small size league at the Robocup international competition in Eindhoven, the Netherlands!
- *2024.05*: &nbsp;🎉🎉 We win two championships in the small size league in the Robocup China Series in Quanzhou, Fujian!
- *2024.03*: &nbsp;🎉🎉 We win the third place in the small size league in the Robocup Japan Open!

# 📝 Publications 
**\* denotes equal contribution.**
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2025</div><img src='images/graphicAbstract.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RISED: Accurate and Efficient RGB-Colorized Mapping Using Image Selection and Point Cloud Densification](https://ieeexplore.ieee.org/abstract/document/11127540)

Changjian Jiang\*, **Lijie Wang**\*, Zeyu Wan, Ruilan Gao, Yue Wang, Rong Xiong, Yu Zhang

[**Project**](https://changjianjiang01.github.io/rised-homepage/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A offline system for high-precision dense color point cloud reconstruction, which provides a different approach from the current method and proposes a comprehensive and quantitative evaluation standard for colorized point clouds.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv, T-ASE Underreview</div><img src='images/tmech.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[🍋🍋LEMON-Mapping: Loop-Enhanced Large-Scale Multi-Session Point Cloud Merging and Optimization for Globally Consistent Mapping](https://www.arxiv.org/abs/2505.10018)

**Lijie Wang**, Xiaoyi Zhong, Ziyi Xu, Kaixin Chai, Anke Zhao, Tianyu Zhao, Changjian Jiang, Qianhao Wang, Fei Gao

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=ZS1QXCIAAAAJ&citation_for_view=ZS1QXCIAAAAJ:9yKSN-GCB0IC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A multi-robot point cloud map fusion and optimization system that can generate locally accurate and globally consistent multi-robot maps, effectively eliminating blur and divergence of the map.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L 2026</div><img src='images/lidarvggt.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LiDAR-VGGT: Cross-Modal Coarse-to-Fine Fusion for Globally
Consistent and Metric-Scale Dense Mapping](https://arxiv.org/abs/2511.01186)

**Lijie Wang**, Lianjie Guo, Ziyi Xu, Qianhao Wang, Fei Gao, Xieyuanli Chen

[**Project**](https://github.com/NorwegianSmokedSalmon/Color-Map-Evaluation) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A novel framework that integrates LiDAR with VGGT to achieve large-scale, dense, metric-accurate, and globally consistent reconstruction.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv, RA-L Underreview</div><img src='images/rl_flight.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[High-Speed Vision-Based Flight in Clutter with Safety-Shielded Reinforcement Learning](https://arxiv.org/abs/2602.08653)

Jiarui Zhang, Chengyong Lei, Chengjiang Dai, Kenghou Hoi, **Lijie Wang**, Zhichao Han and Fei Gao

[**Project**](https://arxiv.org/abs/2602.08653) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- End-to-end high-speed safe flight based on depth map reinforcement learning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Robocup SSL ETDP</div><img src='images/zjunlict2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ZJUNlict Extended Team Paper for Robocup Competition in Salvador, Brazil, 2025.7](https://arxiv.org/abs/2511.01186)

Zifei Wu, **Lijie Wang**, Zhe Yang, Shijie Yang, Liang Wang, Haoran Fu, Yinliang Cai and Rong Xiong

[**Project**](https://github.com/ZJU-RoboCup) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- ZJUNlict’s advancements in robot hardware and software for 2025, developed for participation in the RoboCup competition held in Salvador, Brazil.
</div>
</div>

# ✏️ Academic services
- Reviewer of RSS, CVPR, RA-L, ICRA, Iros.

# 🎖 Honors and Awards
- *2024.12* , Scholarship of <a href='https://cn.a4x.io/'>a4x<strong><span id='total_cit'></span></strong></a>.
- *2025.3* , Ordos academic rising stars.

# 📖 Educations
- *2021.09 - 2025.06*, B.Eng. in Robotics Engineering at Zhejiang University with an honor degree at Chu Kochen Honor College.
- *2025.09 - 2028.06*, M.Sc. in Control Engineering at Zhejiang University.

# 💬 Competitions
- *2024.07*, the second place in the small size league at the Robocup international competition in Eindhoven, the Netherlands. 
- *2024.05*, two championships in the small size league in the Robocup China Series in Quanzhou, Fujian.
- *2024.03*, the third place in the small size league in the Robocup Japan Open.

# 💻 Hobbies
-  Texas Hold'em, Table Tennis, Swimming and Sleeping.


<div style="text-align: center; margin-top: 20px;">
  <span id="busuanzi_container_site_pv" style="display: inline;">
    👀 Total Views: <span id="busuanzi_value_site_pv"></span>
  </span>
  &nbsp;&nbsp;
  <span id="busuanzi_container_site_uv" style="display: inline;">
    🧍 Visitors: <span id="busuanzi_value_site_uv"></span>
  </span>
</div>

<script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>

