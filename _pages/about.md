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

# About Me

I am currently a 2nd-Year Master student at [Tsinghua University](https://www.tsinghua.edu.cn/en/) <img src='./images/thu.png' style='width: 2em;'>. I got B.Eng. degree in Computer Science ([Yingcai Honors College](https://www.yingcai.uestc.edu.cn/en/index.htm)) at [University of Electronic Science and Technology of China](https://en.uestc.edu.cn/) <img src='./images/uestc.png' style='width: 2em;'> from 2020 to 2024.

My research interest includes: <span style="display:inline-block;padding:0.2em 0.7em;margin:0.15em 0.2em;background:#eef2f7;color:#4a6fa5;border-radius:20px;font-size:0.9em;font-weight:500;border:1px solid rgba(74,111,165,0.15);">Image & Video Generation</span> <span style="display:inline-block;padding:0.2em 0.7em;margin:0.15em 0.2em;background:#eef2f7;color:#4a6fa5;border-radius:20px;font-size:0.9em;font-weight:500;border:1px solid rgba(74,111,165,0.15);">Human-Centric Generation</span> <span style="display:inline-block;padding:0.2em 0.7em;margin:0.15em 0.2em;background:#eef2f7;color:#4a6fa5;border-radius:20px;font-size:0.9em;font-weight:500;border:1px solid rgba(74,111,165,0.15);">Reinforcement Learning</span>


<br>

# News

<div style="display:flex;align-items:baseline;padding:0.55em 0.5em;border-bottom:1px solid #f0f0f0;"><span style="display:inline-block;min-width:88px;padding:0.15em 0.6em;background:#eef2f7;color:#4a6fa5;border-radius:4px;font-size:0.82em;font-weight:600;margin-right:1em;text-align:center;flex-shrink:0;">2026-02</span><span>Our paper "<strong>Beyond the Golden Data</strong>" is accepted by <code>CVPR 2026</code>.</span></div>
<div style="display:flex;align-items:baseline;padding:0.55em 0.5em;border-bottom:1px solid #f0f0f0;"><span style="display:inline-block;min-width:88px;padding:0.15em 0.6em;background:#eef2f7;color:#4a6fa5;border-radius:4px;font-size:0.82em;font-weight:600;margin-right:1em;text-align:center;flex-shrink:0;">2025-11</span><span>Our Paper <strong>FilmWeaver</strong> is accepted by <code>AAAI 2026</code>.</span></div>
<div style="display:flex;align-items:baseline;padding:0.55em 0.5em;border-bottom:1px solid #f0f0f0;"><span style="display:inline-block;min-width:88px;padding:0.15em 0.6em;background:#eef2f7;color:#4a6fa5;border-radius:4px;font-size:0.82em;font-weight:600;margin-right:1em;text-align:center;flex-shrink:0;">2025-08</span><span>The code of <strong>CanonSwap</strong> is released. Welcome to star it!</span></div>
<div style="display:flex;align-items:baseline;padding:0.55em 0.5em;border-bottom:1px solid #f0f0f0;"><span style="display:inline-block;min-width:88px;padding:0.15em 0.6em;background:#eef2f7;color:#4a6fa5;border-radius:4px;font-size:0.82em;font-weight:600;margin-right:1em;text-align:center;flex-shrink:0;">2025-07</span><span>Our Paper "<strong>Human Motion Video Generation: A Survey</strong>" is accepted by <code>TPAMI</code>.</span></div>
<div style="display:flex;align-items:baseline;padding:0.55em 0.5em;"><span style="display:inline-block;min-width:88px;padding:0.15em 0.6em;background:#eef2f7;color:#4a6fa5;border-radius:4px;font-size:0.82em;font-weight:600;margin-right:1em;text-align:center;flex-shrink:0;">2025-06</span><span>Our paper "<strong>CanonSwap</strong>" is accepted by <code>ICCV 2025</code>.</span></div>
<br>

# Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/TQD2.png' alt="sym" width="100%" style="object-fit:contain;background:#fff;"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://arxiv.org/abs/2603.25527" style="font-size: 16px; color: #483D8B; text-decoration: none"><strong>Beyond the Golden Data: Resolving the Motion-Vision Quality Dilemma via Timestep Selective Training</strong></a><br>
<span style="font-size: 14px;"><strong>Xiangyang Luo</strong>, Qingyu Li, Yuming Li, Guanbo Huang, Yongjie Zhu, Wenyu Qin, Meng Wang, Pengfei Wan, Shao-Lun Huang</span><br>
<span style="font-size: 14px;">[**Paper**](https://arxiv.org/abs/2603.25527) </span>

<span style="font-size: 13px; color: #666;">We identify the Motion-Vision Quality Dilemma in video data curation and propose Timestep-aware Quality Decoupling (TQD), which skews the training data sampling distribution across timesteps to decouple motion and visual quality, enabling models trained on imbalanced data to surpass those trained on golden data.</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><video src='/images/filmweaver_demo.mp4' width="100%" autoplay loop muted playsinline style="border-radius:8px;"></video></div></div>
<div class='paper-box-text' markdown="1">

<a href="{{ '/FilmWeaver/' | relative_url }}" style="font-size: 16px; color: #483D8B; text-decoration: none"><strong>FilmWeaver: Weaving Consistent Multi-Shot Videos with Cache-Guided Autoregressive Diffusion</strong></a><br>
<span style="font-size: 14px;"><strong>Xiangyang Luo</strong>, Qingyu Li, Xiaokun Liu, Wenyu Qin, Miao Yang, Meng Wang, Pengfei Wan, Di Zhang, Kun Gai, Shao-Lun Huang</span><br>
<span style="font-size: 14px;">[**Paper**]() [**Page**](https://filmweaver.github.io) </span>

<span style="font-size: 13px; color: #666;">FilmWeaver generates consistent multi-shot videos of arbitrary length via an autoregressive diffusion paradigm, enforcing inter-shot consistency with a Shot Cache and intra-shot coherence with a Temporal Cache, and supports applications such as concept injection and video extension.</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI</div><img src='images/human.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://www.techrxiv.org/users/836049/articles/1228135-human-motion-video-generation-a-survey" style="font-size: 16px; color: #483D8B; text-decoration: none">**Human Motion Video Generation: A Survey**</a><br>
<span style="font-size: 14px;">Haiwei Xue, **Xiangyang Luo**, Zhanghao Hu, Xin Zhang, Xunzhi Xiang, Yuqin Dai, Jianzhuang Liu, Minglei Li, Jian Yang, Fei Ma, Changpeng Yang, Zonghong Dai, Fei Richard Yu </span><br>
<span style="font-size: 14px;">[**Paper**](https://www.techrxiv.org/users/836049/articles/1228135-human-motion-video-generation-a-survey) [**Page**](https://github.com/Winn1y/Awesome-Human-Motion-Video-Generation) </span>

<span style="font-size: 13px; color: #666;">This survey provides a comprehensive review of human motion video generation methods, covering the latest techniques, applications, and future directions.</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><video src='/images/canonswap_demo.mp4' width="100%" autoplay loop muted playsinline style="border-radius:8px;"></video></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://arxiv.org/abs/2407.06984" style="font-size: 16px; color: #483D8B; text-decoration: none">**CanonSwap: High-Fidelity and Consistent Video Face Swapping via Canonical Space Modulation**</a><br>
<span style="font-size: 14px;">**Xiangyang Luo** , Ye Zhu†, Yunfei Liu, Lijian Lin, Cong Wan, Zijian Cai, Shao-Lun Huang†, Yu Li</span><br>
<span style="font-size: 14px;">[**Paper**](https://arxiv.org/abs/2507.02691) [**Page**](https://luoxyhappy.github.io/CanonSwap/) [**Code**](https://github.com/Pixel-Talk/CanonSwap) </span>

<span style="font-size: 13px; color: #666;"> CanonSwap decouples motion information from appearance to enable high-fidelity and consistent video face swapping.</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/GRID.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://arxiv.org/pdf/2412.10718" style="font-size: 16px; color: #483D8B; text-decoration: none">**Grid: Omni Visual Generation**</a><br>
<span style="font-size: 14px;">Cong Wan\*, **Xiangyang Luo\***, Hao Luo, Zijian Cai, Yiren Song, Yunlong Zhao, Yifan Bai, Fan Wang, Yuhang He, Yihong Gong</span><br>
<span style="font-size: 14px;">[**Paper**](https://arxiv.org/pdf/2412.10718)[**Code**](https://github.com/Should-AI-Lab/GRID)</span>

<span style="font-size: 13px; color: #666;">We introduces GRID, an omni-visual generation framework that reformulates temporal tasks like video into grid layouts, enabling a single powerful image model to efficiently handle image, video, and 3D generation.</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2025</div><img src='images/OIA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://www.arxiv.org/pdf/2503.23353" style="font-size: 16px; color: #483D8B; text-decoration: none">**Object Isolated Attention for Consistent Story Visualization**</a><br>
<span style="font-size: 14px;">**Xiangyang Luo**, Junhao Cheng, Yifan Xie, Xin Zhang, Tao Feng, Zhou Liu, Fei Ma†, Fei Yu</span><br>
<span style="font-size: 14px;">[**Paper**](https://www.arxiv.org/pdf/2503.23353)</span>

<span style="font-size: 13px; color: #666;">We proposes a training-free method that uses isolated attention mechanisms to maintain character consistency and prevent feature confusion in story visualization.</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/CodeSwap.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a href="https://dl.acm.org/doi/10.1145/3664647.3681120" style="font-size: 16px; color: #483D8B; text-decoration: none">**CodeSwap: Symmetrically Face Swapping Based on Prior Codebook**</a><br>
<span style="font-size: 14px;"> **Xiangyang Luo**, Xin Zhang, Yifan Xie, Xinyi Tong, Weijiang Yu, Heng Chang, Fei Ma†, Fei Ricahrd Yu</span><br>
<span style="font-size: 14px;">[**Paper**](https://dl.acm.org/doi/10.1145/3664647.3681120)</span>

<span style="font-size: 13px; color: #666;"> CodeSwap achieves high-fidelity face swapping by symmetrically manipulating codes within a pre-trained, high-quality facial codebook. </span>

</div>
</div>


# Internships

<div style="margin-top:0.5em;">

<div style="display:flex;align-items:center;padding:1.2em 1em;margin-bottom:0.8em;border-radius:10px;box-shadow:0 2px 10px rgba(0,0,0,0.06);background:#fff;">
  <img src='/images/alibaba.png' style="width:52px;height:52px;border-radius:8px;object-fit:contain;flex-shrink:0;margin-right:1.2em;">
  <div style="flex:1;">
    <div style="display:flex;justify-content:space-between;align-items:baseline;flex-wrap:wrap;">
      <span style="font-size:15px;font-weight:700;color:#222;">Alibaba &nbsp;<span style="font-weight:400;font-size:13px;color:#888;">Research Intern (T-Star)</span></span>

    </div>
    <div style="margin-top:0.3em;font-size:13px;color:#555;">Topic: Human-Centric Video Generation, Reinforcement Learning</div>
  </div>
</div>

<div style="display:flex;align-items:center;padding:1.2em 1em;margin-bottom:0.8em;border-radius:10px;box-shadow:0 2px 10px rgba(0,0,0,0.06);background:#fff;">
  <img src='/images/kuaishou.png' style="width:52px;height:52px;border-radius:8px;object-fit:contain;flex-shrink:0;margin-right:1.2em;">
  <div style="flex:1;">
    <div style="display:flex;justify-content:space-between;align-items:baseline;flex-wrap:wrap;">
      <span style="font-size:15px;font-weight:700;color:#222;">Kuaishou &nbsp;<span style="font-weight:400;font-size:13px;color:#888;">Research Intern</span></span>

    </div>
    <div style="margin-top:0.3em;font-size:13px;color:#555;">Topic: Video Generation, Multi-Shot Generation, Training Strategies</div>
  </div>
</div>

<div style="display:flex;align-items:center;padding:1.2em 1em;margin-bottom:0.8em;border-radius:10px;box-shadow:0 2px 10px rgba(0,0,0,0.06);background:#fff;">
  <img src='/images/idea.jpeg' style="width:52px;height:52px;border-radius:8px;object-fit:contain;flex-shrink:0;margin-right:1.2em;">
  <div style="flex:1;">
    <div style="display:flex;justify-content:space-between;align-items:baseline;flex-wrap:wrap;">
      <span style="font-size:15px;font-weight:700;color:#222;">IDEA Research &nbsp;<span style="font-weight:400;font-size:13px;color:#888;">Research Intern</span></span>

    </div>
    <div style="margin-top:0.3em;font-size:13px;color:#555;">Topic: Video Face Swapping</div>
  </div>
</div>

</div>