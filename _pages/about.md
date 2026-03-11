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

Hi, I'm Xiongzhi Wang(王雄智, born in September 1995). I am currently pursuing my Ph.D. degree (combined Master–Ph.D. program) at the School of Aerospace Science and Technology, Xidian University, Xi'an, China. I have also studied as an exchange student at the School of Future Technology, University of Chinese Academy of Sciences in Beijing, and the College of Computer Science at Nankai University in Tianjin.

My research focuses on 3D reconstruction and stereo depth estimation, with applications in endoscopic vision and medical image analysis. I am particularly interested in advancing deep learning-based perception for minimally invasive surgical environments.

# 🔥 News
- *2025.11*: &nbsp;🎉🎉 May God bless me. 

# 📝 Publications 

[//]: #	"FasterDiffusion"

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/papers/stereonet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep convolutional network for stereo depth mapping in binocular endoscopy](https://ieeexplore.ieee.org/document/9064889/)

<span style="color: #0000FF;"><strong>Xiongzhi Wang</strong></span>, Yunfeng Nie, Shaoping Lu, Jingang Zhang

- A thorough empirical study of the features of the UNet in the diffusion model showing that encoder features vary minimally (whereas decoder feature vary significantly)
- An encoder propagation scheme to accelerate the diffusion sampling without requiring any training or fine-tuning technique
- ~1.8x acceleration for stable diffusion, 50 DDIM steps, ~1.8x acceleration for stable diffusion, 20 Dpm-solver++ steps, and ~1.3x acceleration for DeepFloyd-IF

<div style="display: inline">
        <a href="https://arxiv.org/abs/2312.09608"> [paper]</a>|<a href="https://drive.google.com/file/d/1NEgrFM3kxLoPs2dWubAbYuqqFL4EDoOx/view?usp=sharing">[中译版]</a>
        <a href="https://sen-mao.github.io/FasterDiffusion/">[code]</a>
        <a class="fakelink" onclick="$(this).siblings('.abstract').slideToggle()" >[abstract]</a>
        <div class="abstract"  style="overflow: hidden; display: none;">  
            <p> One of the key components within diffusion models is the UNet for noise prediction. While several works have explored basic properties of the UNet decoder, its encoder largely remains unexplored. In this work, we conduct the first comprehensive study of the UNet encoder. We empirically analyze the encoder features and provide insights to important questions regarding their changes at the inference process. In particular, we find that encoder features change gently, whereas the decoder features exhibit substantial variations across different time-steps. This finding inspired us to omit the encoder at certain adjacent time-steps and reuse cyclically the encoder features in the previous time-steps for the decoder. Further based on this observation, we introduce a simple yet effective encoder propagation scheme to accelerate the diffusion sampling for a diverse set of tasks. By benefiting from our propagation scheme, we are able to perform in parallel the decoder at certain adjacent time-steps. Additionally, we introduce a prior noise injection method to improve the texture details in the generated image. Besides the standard text-to-image task, we also validate our approach on other tasks: text-to-video, personalized generation and reference-guided generation. Without utilizing any knowledge distillation technique, our approach accelerates both the Stable Diffusion (SD) and the DeepFloyd-IF models sampling by 41% and 24% respectively, while maintaining high-quality generation performance. </p>
        </div>
        <a href="https://drive.google.com/file/d/1sQiDenlGU7TElFTn64Zthtf-dwAphM4T/view?usp=sharing">[slide]</a>
        <a href="https://drive.google.com/file/d/1RHed-AwYGuMPT-RSEgo57HYWixqWSFbC/view?usp=sharing">[poster]</a>
</div>

</div>
</div>

Deep convolutional network for stereo depth mapping in binocular endoscopy  
**Xiongzhi Wang**, Yunfeng Nie, Shaoping Lu, Jingang Zhang  
*IEEE Access*, 2020, 8: 73241–73249  

Multi-scale, multi-dimensional binocular endoscopic image depth estimation network  
**Xiongzhi Wang**, Yunfeng Nie, Wenqi Ren, Min Wei, Jingang Zhang  
*Computers in Biology and Medicine*, 2023, 164: 107305  

Deep learning for endoscopic depth estimation: A review  
**Xiongzhi Wang**, Boyu Yang, Min Wei, Liangfa Liu, Jingang Zhang, Yunfeng Nie  
*Displays*, 2025: 103086  

Endo-E2E-GS: End-to-end 3D reconstruction of endoscopic scenes using Gaussian Splatting  
**Xiongzhi Wang**, Boyu Yang, Min Wei, Yu Chen, Jingang Zhang, Yunfeng Nie  
*Displays*, 2026: 103353  

# 📚 Books & Book Chapters

Research and Exploration of Endoscopic Image Big Data Technology Serving Precision Medicine   
Jingang Zhang, Liang Zong, Min Wei, Wenqi Ren, **Xiongzhi Wang**, Yanbo Dong, Kun Liu, Liangfa Liu, Shiming Yang  
*China’s e-Science Blue Book 2023*, Springer Nature, 2024: 397–413  

计算工程光学(Python版),西安电子科技大学出版社,2023.07  
张金刚,聂云峰,付强,**王雄智**

<p hidden>
# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</p>

# 📖 Educations
- *2021.03 - 2026.06*, Instrument Science and Technology, School of Aerospace Science and Technology, Xidian University, Xi'an, China. 
- *2018.09 - 2021.03*, Computer Technology, School of Computer Science and Technology, Xidian University, Xi'an, China.
- *2014.09 - 2018.06*, Information and Technology Science, College of Science, China University of Petroleum (East China), Qingdao, China. 

<p hidden>
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
</p>

# 💻 Teaching
- Intelligent Image Processing with Python, Teaching Assistant - Fall 2021-2025

# 📄 Academic Service
- Npj Digital Surgery, Scientific Reports, Scientific Data
