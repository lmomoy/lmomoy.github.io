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

I am pursuing Ph.D. degree in School of Mechanical Science and Engineering, Huazhong University of Science and Technology under the supervision of <a href="http://mse.hust.edu.cn/info/1145/1413.htm">Youping Chen</a>. Previously, I received my M.S. degree in School of Mechanical Science and Engineering, Huazhong University of Science and Technology under the supervision of <a href="http://mse.hust.edu.cn/info/1145/1415.htm">Jingming Xie</a> (2021), and B.S. degree in Hubei University of Technology (2019).

My current research interests is computer vision including object detection, image segmentation and multimodal fusion for autonomous driving.


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><img src='images/LF-YOLO.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[LF-YOLO: A Lighter and Faster YOLO for Weld Defect Detection of X-ray Image](https://arxiv.org/pdf/2110.15045.pdf)

**Moyun Liu**, Youping Chen, Lei He, Yang Zhang, Jingming Xie

**IEEE Sensors Journal, 2023** \| [![](https://img.shields.io/github/stars/lmomoy/LF-YOLO?style=social&label=Code Stars)](https://github.com/lmomoy/LF-YOLO)

- X-ray image plays an important role in manufacturing industry for quality assurance, because it can reflect the internal condition of weld region. However, the shape and scale of different defect types vary greatly, which makes it challenging for model to detect weld defects. In this paper, we propose a weld defect detection method based on convolution neural network, namely Lighter and Faster YOLO (LF-YOLO). 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/CII.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[A lightweight and accurate recognition framework for signs of X-ray weld images](https://arxiv.org/pdf/2110.09278.pdf)

**Moyun Liu**, Jingming Xie, Jing Hao, Yang Zhang, Xuzhan Chen, Youping Chen

**Computers in Industry, 2022**

- X-ray images are commonly used to ensure the security of devices in quality inspection industry. The recognition of signs printed on X-ray weld images plays an essential role in digital traceability system of manufacturing industry.  In this paper, we propose a signs recognition framework based on convolutional neural networks (CNNs) for weld images. The proposed framework firstly contains a shallow classification network for correcting the pose of images, and a narrow network for final weld information recognition.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/TII2021-paper.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[A Unified Light Framework for Real-time Fault Detection of Freight Train Images](https://arxiv.org/pdf/2102.00381.pdf)

Yang Zhang, **Moyun Liu\***, Yang Yang, Yanwen Guo, Huiming Zhang

**IEEE Transactions on Industrial Informatics, 2021**

- A unified light framework is designed to improve detection accuracy while supporting a real-time operation with a low resource requirement. We firstly design a novel lightweight backbone (RFDNet) to improve the accuracy and reduce computational cost. Then, we propose a multi region proposal network using multi-scale feature maps generated from RFDNet to improve the detection performance. Finally, we present multi level position-sensitive score maps and region of interest pooling to further improve accuracy with few redundant computations.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/TMM2021-paper.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Affinity fusion graph-based framework for natural image segmentation](https://arxiv.org/pdf/2006.13542.pdf)

Yang Zhang, **Moyun Liu**, Jingwu He, Fei Pan, Yanwen Guo

**IEEE Transactions on Multimedia, 2021** \| [![](https://img.shields.io/github/stars/Yangzhangcst/AF-graph?style=social&label=Code Stars)](https://github.com/Yangzhangcst/AF-graph)

- The proposed framework combines adjacency-graphs and kernel spectral clustering based graphs (KSC-graphs) according to a new definition named affinity nodes of multi-scale superpixels. These affinity nodes are selected based on a better affiliation of superpixels, namely subspace-preserving representation which is generated by sparse subspace clustering based on subspace pursuit. Then a KSC-graph is built via a novel kernel spectral clustering to explore the nonlinear relationships among these affinity nodes. Moreover, an adjacency-graph at each scale is constructed, which is further used to update the proposed KSC-graph at affinity nodes. The fusion graph is built across different scales, and it is partitioned to obtain final segmentation result.
</div>
</div>

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2021.09 - Now*, Ph.D. Student, School of Mechanical Science and Engineering, Huazhong University of Science and Technology.
- *2019.06 - 2021.06*, M.Eng., School of Mechanical Science and Engineering, Huazhong University of Science and Technology.
- *2015.09 - 2019.06*, B.Eng., School of Mechanical Engineering, Hubei University of Technology.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2022.07 - 2022.09*, [Huawei Intelligent Automotive Solution Business Unit](https://www.huawei.com/cn/giv/intelligent-automotive-solution-2030), Shanghai, China.