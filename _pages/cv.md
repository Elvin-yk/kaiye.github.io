---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p>
<a class="btn btn--primary" href="/assets/Kye_s_Resume.pdf" target="_blank">下载 PDF 简历</a>
</p>

Education
======
* The Chinese University of Hong Kong, Shenzhen — M.Phil, Computer & Information Engineering, Jan. 2024 - Now (Supervisor: Prof. Rui Huang)
* Lanzhou University — B.S., Computer Science & Technology, Sept. 2018 - July 2022 (Supervisor: Prof. Minqiang Yang)

Work experience
======
* Algorithm Engineer, YITU, Shanghai — Jul. 2022 - Jun. 2023
  * Autonomous Driving Perception (Jul. 2022 - Aug. 2022): 雷达替代单帧遮挡检测方案研发与路测
  * Motion Prediction (Sept. 2022 - Dec. 2022): 数据增强/架构优化/损失设计使指标较基线下降 10%，解决 44.05% 实车问题
  * Mapless Driving (Jan. 2023 - Jun. 2023): 路网结构预测数据工程，提升数据多样性与准确性

Research experience
======
* UAIS Lab, Lanzhou University — Research Assistant, Mar. 2019 - Sept. 2021 (Advisors: Bin Hu, Minqiang Yang)
  * Independent Encoder for Deep Hierarchical Unsupervised I2I Translation：重构网络缓解语义不一致，性能优于当时 SOTA [2]
  * Retinal Vessel Segmentation：多尺度注意力 + 对抗学习 + 拼接增强提升分割性能 [3,4]
  * Eyeglasses Try-On 平台：I2I 去镜框 + AR 试戴，产出国家发明专利 [5]

* Shenzhen Institute of Artificial Intelligence and Robotics — Research Assistant, Jun. 2024 - Now (Advisor: Rui Huang)
  * Multi-View 3D Visual Grounding：CVPR 2024 竞赛 5/64；
  * Dexterous Hand Grasping：语音+视觉多模态抓取系统；优秀奖与媒体报道；论文 [1]
  
Skills
======
* Python, PyTorch, Linux
* 视觉/多模态/嵌入式工程实现
* 英语（IELTS 6.5）

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* 篮球爱好者
