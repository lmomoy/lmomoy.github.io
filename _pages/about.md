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

I am pursuing Ph.D. degree in School of Mechanical Science and Engineering, Huazhong University of Science and Technology. Previously, I received my M.S. degree in School of Mechanical Science and Engineering, Huazhong University of Science and Technology (2021), and B.S. degree in Hubei University of Technology (2019).

Now, I am a visiting student in A*STAR Centre for Frontier AI Research (CFAR), Singapore, supervised by [Joey Tianyi Zhou](https://joeyzhouty.github.io/) and [Jiawei Du](https://scholar.google.com/citations?user=WrJKEzEAAAAJ&hl=zh-CN&oi=ao). 

My current research interest is computer vision including object detection, image segmentation, and multimodal fusion for autonomous driving.


# 🔥 News
- *2024.11*: &nbsp;🎉 Our work "SGIFormer: Semantic-guided and Geometric-enhanced Interleaving Transformer for 3D Instance Segmentation" has been accepted by **IEEE TCSVT** ! [Paper](https://arxiv.org/pdf/2407.11564)
- *2024.10*: &nbsp;🎉 Our work "GEM: Boost Simple Network for Glass Surface Segmentation via Vision Foundation Models" has been accepted by **IEEE TMM** ! [Paper](https://arxiv.org/pdf/2307.12018)
- *2024.10*: &nbsp;🎉 We got 6th place in ToothFairy2 : Semi-supervised Teeth Segmentation hold on MICCAI2024 !
- *2024.05*: &nbsp;🎉 Our work "Towards Better Unguided Depth Completion via Cross-Modality Knowledge Distillation in the Frequency Domain" has been accepted by **IEEE TIV** ! [Paper](https://ieeexplore.ieee.org/document/10517614)
- *2024.04*: &nbsp;🎉 Our work "MENet: Multi-Modal Mapping Enhancement Network for 3D Object Detection in Autonomous Driving" has been accepted by **IEEE TITS** ! [Paper](https://ieeexplore.ieee.org/document/10510171)

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2023.05 - Now*, Visiting Ph.D. Student, A*STAR Centre for Frontier AI Research (CFAR).
- *2021.09 - Now*, Ph.D. Student, School of Mechanical Science and Engineering, Huazhong University of Science and Technology.
- *2019.06 - 2021.06*, M.Eng., School of Mechanical Science and Engineering, Huazhong University of Science and Technology.
- *2015.09 - 2019.06*, B.Eng., School of Mechanical Engineering, Hubei University of Technology.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2022.07 - 2022.09*, [Huawei Intelligent Automotive Solution Business Unit](https://www.huawei.com/en/giv/intelligent-automotive-solution-2030), Shanghai, China.

<!-- # 📝 Under Review or Revision

**Towards Better Unguided Depth Completion via Cross-Modality Distillation Knowledge in the Frequency Domain**

**Moyun Liu**, Bing Chen, Youping Chen, Jingming Xie, Lei Yao, Yang Zhang et al.

*IEEE Transactions on Intelligent Vehicles (Minor Revision)* -->


# 📝 Selected Publications 
<div class='paper-box'><div class='paper-box-image'><img src='images/BUNet.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Towards Better Unguided Depth Completion via Cross-Modality Knowledge Distillation in the Frequency Domain](
https://ieeexplore.ieee.org/document/10517614)

<span style="color:red; font-weight:bold;">Moyun Liu</span>, Bing Chen, Youping Chen, Jingming Xie, Lei Yao, Yang Zhang, Qin Hu, Jiawei Du, Joey Tianyi Zhou

**IEEE Transactions on Intelligent Vehicles, 2024**

- We analyze the contribution of camera image for depth completion and propose a better unguided depth completion framework. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/MENet.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[MENet: Multi-Modal Mapping Enhancement Network for 3D Object Detection in Autonomous Driving](https://ieeexplore.ieee.org/document/10510171)

<span style="color:red; font-weight:bold;">Moyun Liu</span>, Youping Chen, Jingming Xie, Yijie Zhu, Yang Zhang, Lei Yao, Zhenshan Bing, Genghang Zhuang, Kai Huang, Joey Tianyi Zhou

**IEEE Transactions on Intelligent Transportation Systems, 2024**

- We propose a multi-modal mapping enhancement network named MENet for 3D object detection. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/CHNet.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[A Concise but High-performing Network for Image Guided Depth Completion in Autonomous Driving](https://www.sciencedirect.com/science/article/pii/S0950705124005112)

<span style="color:red; font-weight:bold;">Moyun Liu</span>, Bing Chen, Youping Chen, Jingming Xie, Lei Yao, Yang Zhang, Joey Tianyi Zhou

**Knowledge-Based Systems, 2024** \| [![](https://img.shields.io/github/stars/lmomoy/CHNet?style=social&label=Code Stars)](https://github.com/lmomoy/CHNet)

- We propose a fast and effective depth completion network based on the image guidance. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/GEM.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[GEM: Boost Simple Network for Glass Surface Segmentation via Vision Foundation Models](https://arxiv.org/pdf/2307.12018)

Jing Hao\*, <span style="color:red; font-weight:bold;">Moyun Liu\*</span>, Jinrong Yang, Kuo Feng Hung

**IEEE Transactions on Multimedia, 2024** \| [![](https://img.shields.io/github/stars/isbrycee/GEM?style=social&label=Code Stars)](https://github.com/isbrycee/GEM)

- The first to propose exploring to the solution of glass surface segmentation by fully harnessing the capabilities of existing VFMs. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/LF-YOLO.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[LF-YOLO: A Lighter and Faster YOLO for Weld Defect Detection of X-ray Image](https://arxiv.org/pdf/2110.15045.pdf)

<span style="color:red; font-weight:bold;">Moyun Liu</span>, Youping Chen, Jingming Xie, Lei He, Yang Zhang

**IEEE Sensors Journal, 2023** \| [![](https://img.shields.io/github/stars/lmomoy/LF-YOLO?style=social&label=Code Stars)](https://github.com/lmomoy/LF-YOLO)

- We propose a weld defect detection method based on convolution neural network, namely Lighter and Faster YOLO (LF-YOLO). 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/AFAG.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Adaptive fusion affinity graph with noise-free online low-rank representation for natural image segmentation](https://arxiv.org/pdf/2110.11685.pdf)

Yang Zhang, <span style="color:red; font-weight:bold;">Moyun Liu</span>, Huiming Zhang, Guodong Sun, and Jingwu He

**Pattern Recognition, 2023** 
- We propose an adaptive fusion affinity graph (AFA-graph) with noise-free low-rank representation in an online manner for natural image segmentation
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/CII.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[A lightweight and accurate recognition framework for signs of X-ray weld images](https://arxiv.org/pdf/2110.09278.pdf)

<span style="color:red; font-weight:bold;">Moyun Liu</span>, Jingming Xie, Jing Hao, Yang Zhang, Xuzhan Chen, Youping Chen

**Computers in Industry, 2022**

- We propose a signs recognition framework based on convolutional neural networks (CNNs) for weld images. The proposed framework firstly contains a shallow classification network for correcting the pose of images, and a narrow network for final weld information recognition.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/TII2021-paper.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[A Unified Light Framework for Real-time Fault Detection of Freight Train Images](https://arxiv.org/pdf/2102.00381.pdf)

Yang Zhang, <span style="color:red; font-weight:bold;">Moyun Liu\*</span>, Yang Yang, Yanwen Guo, Huiming Zhang

**IEEE Transactions on Industrial Informatics, 2021**

- We propose a unified light framework to improve detection accuracy while supporting a real-time operation with a low resource requirement.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/TMM2021-paper.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Affinity fusion graph-based framework for natural image segmentation](https://arxiv.org/pdf/2006.13542.pdf)

Yang Zhang, <span style="color:red; font-weight:bold;">Moyun Liu</span>, Jingwu He, Fei Pan, Yanwen Guo

**IEEE Transactions on Multimedia, 2021** \| [![](https://img.shields.io/github/stars/Yangzhangcst/AF-graph?style=social&label=Code Stars)](https://github.com/Yangzhangcst/AF-graph)

- We propose an affinity fusion graph framework to effectively connect different graphs with highly discriminating power and nonlinearity for natural image segmentation.
</div>
</div>


<!-- <div class='paper-box'><div class='paper-box-image'><img src='images/TIM-2020.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Real-time vision-based system of fault detection for freight trains](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8911418)

Yang Zhang, <span style="color:red; font-weight:bold;">Moyun Liu</span>, Yunian Chen, Hongjie Zhang, Yanwen Guo

**IEEE Transactions on Instrumentation and Measurement, 2020**

- We propose a real-time vision-based system of fault detection (RVBS-FD) for freight trains aims to complete routine maintenance tasks efficiently for ensuring railway transportation security.
</div>
</div> -->
<!-- 
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 📝 Other Publications 

[Multiple prior representation learning for self-supervised monocular depth estimation via hybrid transformer](
https://www.sciencedirect.com/science/article/pii/S0952197624009485)

**Engineering Applications of Artificial Intelligence, 2024**

Guodong Sun, Junjie Liu, Mingxuan Liu, <span style="color:red; font-weight:bold;">Moyun Liu</span>, Yang Zhou


[Efficient Visual Fault Detection for Freight Train via Neural Architecture Search With Data Volume Robustness](
https://ieeexplore.ieee.org/document/10570157)

**IEEE Transactions on Industrial Informatics, 2024**

Yang Zhang, Mingying Li, Huilin Pan, <span style="color:red; font-weight:bold;">Moyun Liu</span>, Yang Zhang


[SGIFormer: Semantic-guided and Geometric-enhanced Interleaving Transformer for 3D Instance Segmentation](
https://arxiv.org/pdf/2407.11564)

**Arxiv, 2024** \| [![](https://img.shields.io/github/stars/RayYoh/SGIFormer?style=social&label=Code Stars)](https://github.com/RayYoh/SGIFormer)


Lei Yao, Yi Wang, <span style="color:red; font-weight:bold;">Moyun Liu</span>, Lap-Pui Chau

<!-- [GEM: Boost Simple Network for Glass Surface Segmentation via Segment Anything Model and Data Synthesis](
https://arxiv.org/pdf/2401.15282)

**Arxiv, 2024** \| [![](https://img.shields.io/github/stars/isbrycee/GEM?style=social&label=Code Stars)](https://github.com/isbrycee/GEM)

<span style="color:red; font-weight:bold;">Jing Hao\*</span>, <span style="color:red; font-weight:bold;">Moyun Liu\*</span>, Kuo Feng Hung -->

[BF3D: Bi-directional fusion 3D detector with semantic sampling and geometric mapping](
https://www.sciencedirect.com/science/article/pii/S0262885623002093)

**Image and Vision Computing, 2023**

Yijie Zhu, Jingming Xie, <span style="color:red; font-weight:bold;">Moyun Liu</span>, Lei Yao, Youping Chen

[Real-time vision-based system of fault detection for freight trains](
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8911418)

**IEEE Transactions on Instrumentation and Measurement, 2020**

Yang Zhang, <span style="color:red; font-weight:bold;">Moyun Liu</span>, Yunian Chen, Hongjie Zhang, Yanwen Guo

# 👬 Competition
<div class='paper-box'><div class='paper-box-image'><img src='images/certificate.jpg' alt="sym" width="70%"></div>
<div class='paper-box-text' markdown="1">

The 6th place in ToothFairy2 : Semi-supervised Teeth Segmentation hold on **MICCAI2024**. Many thanks to our team leader, [Jing HAO](https://isbrycee.github.io/).
</div>
</div>

# 👨‍🎓 Academic Service

 - **Reviewer**

IEEE Transactions on Intelligent Vehicles

IEEE Transactions on Industrial Informatics

IEEE Transactions on Automation Science and Engineering

IEEE Transactions on Artificial Intelligence

IEEE Sensors Journal

International Conference on Learning Representations (ICLR)

Pattern Recognition

Computers in Industry

Engineering Applications of Artificial Intelligence

- **Conference Service**

Program Committees of 2023 the 1st International Conference on AI-generated Content (AIGC2023)


<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=utH4ywUXvDZarENPjRcCDiGKVLCHBKGMoqhVBRvDpKw"></script>