---
permalink: /
title: ""
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

# 👨‍🎓 About me

I am currently a 2nd-Year Master student at [Tsinghua University](https://www.tsinghua.edu.cn/en/) <img src='./images/thu.png' style='width: 2em;'>. I got B.Eng. degree in Computer Science ([Yingcai Honors College](https://www.yingcai.uestc.edu.cn/en/index.htm)) at [University of Electronic Science and Technology of China](https://en.uestc.edu.cn/) <img src='./images/uestc.png' style='width: 2em;'> from 2020 to 2024. My current research interest is Generative AI, including Image/Video Generation, human-centric generation and effecient training methods.

I am looking for a Ph.D. position starting in Fall 2027. I'm always open to connecting and discussing my research interests!🤝🤝🤝

<br>

# 📰 News
*   **[2025-08-24]** The code of **CanonSwap** is released. Welcome to star it⭐⭐!
*   **[2025-07-26]** 🎉🎉 Our Paper "**Human Motion Video Generation: A Survey**" is accepted by `TPAMI`!
*   **[2025-06-26]** 🎉🎉 Our paper "**CanonSwap**" is accepted by `ICCV 2025`!
<br>

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI</div><img src='images/human.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://www.techrxiv.org/users/836049/articles/1228135-human-motion-video-generation-a-survey" style="font-size: 22px; color: #483D8B; text-decoration: none">**Human Motion Video Generation: A Survey**</a><br>
<span style="font-size: 18px;">Haiwei Xue, **Xiangyang Luo**, Zhanghao Hu, Xin Zhang, Xunzhi Xiang, Yuqin Dai, Jianzhuang Liu, Minglei Li, Jian Yang, Fei Ma, Changpeng Yang, Zonghong Dai, Fei Richard Yu </span><br>
<span style="font-size: 18px;">[**Paper**](https://www.techrxiv.org/users/836049/articles/1228135-human-motion-video-generation-a-survey) [**Page**](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation) </span>

<span style="font-size: 18px;">- This survey provides a comprehensive review of human motion video generation methods, covering the latest techniques, applications, and future directions.</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/CanonSwap.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://arxiv.org/abs/2407.06984" style="font-size: 22px; color: #483D8B; text-decoration: none">**CanonSwap: High-Fidelity and Consistent Video Face Swapping via Canonical Space Modulation**</a><br>
<span style="font-size: 18px;">**Xiangyang Luo** , Ye Zhu†, Yunfei Liu, Lijian Lin, Cong Wan, Zijian Cai, Shao-Lun Huang†, Yu Li</span><br>
<span style="font-size: 18px;">[**Paper**](https://arxiv.org/abs/2507.02691) [**Page**](https://luoxyhappy.github.io/CanonSwap/) [**Code**](https://github.com/Pixel-Talk/CanonSwap) </span>

<span style="font-size: 18px;">-  CanonSwap decouples motion information from appearance to enable high-fidelity and consistent video face swapping.</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2025</div><img src='images/OIA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://www.arxiv.org/pdf/2503.23353" style="font-size: 22px; color: #483D8B; text-decoration: none">**Object Isolated Attention for Consistent Story Visualization**</a><br>
<span style="font-size: 18px;">**Xiangyang Luo**, Junhao Cheng, Yifan Xie, Xin Zhang, Tao Feng, Zhou Liu, Fei Ma†, Fei Yu</span><br>
<span style="font-size: 18px;">[**Paper**](https://www.arxiv.org/pdf/2503.23353)</span>

<span style="font-size: 18px;">- We proposes a training-free method that uses isolated attention mechanisms to maintain character consistency and prevent feature confusion in story visualization.</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/GRID.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://arxiv.org/pdf/2412.10718" style="font-size: 22px; color: #483D8B; text-decoration: none">**Grid: Omni Visual Generation**</a><br>
<span style="font-size: 18px;">Cong Wan\*, **Xiangyang Luo\***, Hao Luo, Zijian Cai, Yiren Song, Yunlong Zhao, Yifan Bai, Fan Wang, Yuhang He, Yihong Gong</span><br>
<span style="font-size: 18px;">[**Paper**](https://arxiv.org/pdf/2412.10718)</span>

<span style="font-size: 18px;">- We introduces GRID, an omni-visual generation framework that reformulates temporal tasks like video into grid layouts, enabling a single powerful image model to efficiently handle image, video, and 3D generation.</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/CodeSwap.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://dl.acm.org/doi/10.1145/3664647.3681120" style="font-size: 22px; color: #483D8B; text-decoration: none">**CodeSwap: Symmetrically Face Swapping Based on Prior Codebook**</a><br>
<span style="font-size: 18px;"> **Xiangyang Luo**, Xin Zhang, Yifan Xie, Xinyi Tong, Weijiang Yu, Heng Chang, Fei Ma†, Fei Ricahrd Yu</span><br>
<span style="font-size: 18px;">[**Paper**](https://dl.acm.org/doi/10.1145/3664647.3681120)</span>

<span style="font-size: 18px;">-  CodeSwap achieves high-fidelity face swapping by symmetrically manipulating codes within a pre-trained, high-quality facial codebook. </span>

</div>
</div>



