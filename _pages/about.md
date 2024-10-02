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

I work at BIGAI as a senior research engineer now in Beijing, advised by [Zilong Zheng (郑子隆)](https://zilongzheng.github.io/). I am now working on diffusion language model, long context and long sequence generation research.

I graduated from Computer Technology,  Tsinghua University (清华大学) with a master’s degree and from Computer Science and Technology, Beijing Institute and Technology (北京理工大学) with a bachelor’s degree.



My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- *2024.09*: &nbsp;🎉🎉 Our paper is accepted by NIPS 2024 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/cream.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Never Miss A Beat: An Efficient Recipe for Context Window Extension of Large Language Models with Consistent "Middle" Enhancement](https://arxiv.org/abs/2406.07138)

**Tong Wu**, Yanpeng Zhao, Zilong Zheng

[**Github**](https://github.com/wutong4012/CREAM)
- CREAM can not only fine-tune within the pre-training context window size, but also alleviate the issue of the model easily getting lost in the middle. e.g., CREAM-YaRN outperforms PoSE-YaRN by over 20% on average in the “Lost in the Middle” task.
- CREAM can further be enhanced by integrating novel designs on positional interpolation frequencies (such as Linear, NTK, Yarn, etc.), and can be extended to context window sizes of up to 256K or beyond.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/ar_diffusion.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AR-Diffusion: Auto-Regressive Diffusion Model for Text Generation](https://proceedings.neurips.cc/paper_files/paper/2023/hash/7d866abba506e5a56335e4644ebe18f9-Abstract-Conference.html)

**Tong Wu^**, Zhihao Fan^, Xiao Liu, Hai-Tao Zheng, Yeyun Gong, yelong shen, Jian Jiao, Juntao Li, zhongyu wei, Jian Guo, Nan Duan, Weizhu Chen

[**Github**](https://github.com/wutong4012/AR-Diffusion)
- AR-Diffusion ensures that the generation of tokens on the right depends on the generated ones on the left, a mechanism achieved through employing a dynamic number of denoising steps that vary based on token position. This results in tokens on the left undergoing fewer denoising steps than those on the right, thereby enabling them to generate earlier and subsequently influence the generation of tokens on the right. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECAI 2023 Oral</div><img src='images/consis.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Enhancing Text Generation with Cooperative Training](https://www.semanticscholar.org/paper/Enhancing-Text-Generation-with-Cooperative-Training-Wu-Wang/6098dfceda1f9f6d60a20f25a180c4fb70c02c2b)

**Tong Wu^**, Hao Wang^, Zhongshen Zeng, Wei Wang, Hai-Tao Zheng, Jiaxing Zhang

[**Github**](https://github.com/wutong4012/Self-Consistent-Learning)
- We introduce a self-consistent learning framework in the text field that involves training a discriminator and generator cooperatively in a closed-loop manner until a scoring consensus is reached. By learning directly from selected samples, our framework are able to mitigate training instabilities such as mode collapse and non-convergence. 
</div>
</div>

- [Text Generation with Diffusion Language Models: A Pre-training Approach with Continuous Paragraph Denoise](https://proceedings.mlr.press/v202/lin23d.html), Zhenghao Lin, Yeyun Gong, Yelong Shen, **Tong Wu**, Zhihao Fan, Chen Lin, Nan Duan, Weizhu Chen, **ICML 2023**
- [DeepSeek LLM: Scaling Open-Source Language Models with Longtermism](https://arxiv.org/abs/2401.02954)

# 📖 Educations
- *2021.09 - 2024.06*, Master, Tsinghua University, Beijing. 
- *2017.08 - 2021.06*, Bachelor, Beijing Institute and Technology, Beijing. 

# 💻 Internships
- *2024.02 - 2024.06*, BIGAI, NLCo, Beijing.
- *2023.07 - 2023.11*, Deepseek, Beijing.
- *2022.11 - 2023.07*, MSRA, NLC, Beijing.
- *2022.04 - 2022.10*, IDEA, CCNL, Shenzhen.
- *2021.10 - 2022.02*, SenseTime, Shenzhen.
- *2021.01 - 2021.06*, Xizi, Beijing.
- *2020.01 - 2020.05*, X-Tech, Beijing.




