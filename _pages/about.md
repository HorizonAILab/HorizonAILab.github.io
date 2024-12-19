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

<br> **Biography**: Hi, I am Associate Professor with the [College of Sciences](https://www.nudt.edu.cn/xysz/wlxy/index.htm), [National University of Defense Technology (NUDT)](https://www.nudt.edu.cn/), Changsha, Hunan, China. He has received his B.Eng. and Ph.D degree (advised by [Prof. Dongyun Yi](https://www.researchgate.net/profile/Dongyun-Yi)) from NUDT. He was a visiting Ph.D. student (advised by [Prof. Jieping Ye](http://www.yelabs.net/)) with the University of Michigan from 2015 to 2017. He has authored more than 60 papers in journals and conferences, such as IEEE TPAMI, IEEE TKDE, TCYB, Pattern Recognition and KDD etc. His research interests focus on machine learning, multi-media analysis, data mining and scene understanding. Dr. Luo received Outstanding Doctoral Dissertation Award of SESC and Hunan Province in 2020. He has served as AC/SPC/PC of several conferences including NeurIPS, ICLR, ICML and CVPR etc. <br> 

**简介**: 罗廷金现任[国防科技大学](https://www.nudt.edu.cn/)[理学院](https://www.nudt.edu.cn/xysz/wlxy/index.htm)副教授。于2018年获博士学位，已在顶级期刊或会议上发表60余篇学术论文，主要包括IEEE TPAMI，IEEE TKDE, IEEE TIP, IEEE TCYB, KDD, AAAI, ICME, PAKDD等。目前担任IEEE TIP、IEEE TKDE、中国科学等10余家国际权威期刊审稿人，并受邀担任ICML、IJCAI、AAAI、ICDM、ICPR等多个国际会议的PC Member。主持基础加强重点项目课题、国家自然科学基金等6项。获中国系统工程学会优秀博士学位论文奖、湖南省优秀博士学位论文、学校秀青年创新奖等荣誉。入选湖南省湖湘青年英才计划和高层次卓越人才计划等。

# Research (研究领域)
My research interests lie in machine learning, data mining, and learning-based vision problems. Particularly, I'm interested in weakly-supervised learning and its applications, such as semi-supervised learning, multi-label learning, label noise learning, partial label learning, etc. 

I have published 50+ papers <a href='https://scholar.google.com/citations?user=w0YDfhcAAAAJ&hl=zh-CN'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FHorizonAILab%2Fhorizonailab.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> at the top international AI conferences such as KDD, AAAI and ACM MM etc. 

我的研究方向主要为机器学习、数据挖掘及基于学习的计算机视觉问题。特别地，我关注多视图学习、弱监督学习方法及其应用，比如半监督学习、标签噪声学习、偏标记学习等。

# 📝 Representative Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2019</div><img src='images/android-chrome-192x192.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FastSpeech: Fast, Robust and Controllable Text to Speech](https://papers.nips.cc/paper/8580-fastspeech-fast-robust-and-controllable-text-to-speech.pdf) \\
**Yi Ren**, Yangjun Ruan, Xu Tan, Tao Qin, Sheng Zhao, Zhou Zhao, Tie-Yan Liu

[**Project**](https://speechresearch.github.io/fastspeech/) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:qjMakFHDy7sC'></span></strong>

- FastSpeech is the first fully parallel end-to-end speech synthesis model.
- **Academic Impact**: This work is included by many famous speech synthesis open-source projects, such as [ESPNet ![](https://img.shields.io/github/stars/espnet/espnet?style=social)](https://github.com/espnet/espnet). Our work are promoted by more than 20 media and forums, such as [机器之心](https://mp.weixin.qq.com/s/UkFadiUBy-Ymn-zhJ95JcQ)、[InfoQ](https://www.infoq.cn/article/tvy7hnin8bjvlm6g0myu).
- **Industry Impact**: FastSpeech has been deployed in [Microsoft Azure TTS service](https://techcommunity.microsoft.com/t5/azure-ai/neural-text-to-speech-extends-support-to-15-more-languages-with/ba-p/1505911) and supports 49 more languages with state-of-the-art AI quality. It was also shown as a text-to-speech system acceleration example in [NVIDIA GTC2020](https://resources.nvidia.com/events/GTC2020s21420).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/pub_figs/middle_layers.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Devils in Middle Layers of Large Vision-Language Models: Interpreting, Detecting and Mitigating Object Hallucinations via Attention Lens](http://arxiv.org/abs/2411.16724), Submitted to Conference \\
Zhangqi Jiang, Junkai Chen, Beier Zhu, **Tingjin Luo#**, Yankun Shen, Xu Yang


- We address how LVLMs process visual information and whether this process causes hallucination.
- First, we identify the middle layers are crucial for handling visual data in LVLMs, which can be further divided into two stages: **visual information enrichment** and **semantic refinement**.
- Second, we find that real tokens consistently receive higher attention weights than hallucinated ones, serving as a strong indicator of hallucination.
- Third, we observe that hallucination tokens often result from attention heads interacting with inconsistent objects.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/pub_figs/DIMvLN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Incomplete Multi-View Learning Network with Insufficient Label Information](https://ojs.aaai.org/index.php/AAAI/article/view/29189), _AAAI_, 2024, \[[**code**](https://github.com/ZhangqiJiang07/code_DIMvLN)\]\\
**Zhangqi Jiang**, Tingjin Luo, Xinyan Liang
-  To tackle the double missing of features and labels problem, we propose a novel deep incomplete multi-view learning network (DIMvLN) to tackle the problem of insufficient label information in multi-view learning.
- DIMvLN integrates graph neural networks and semi-supervised learning into a unified framework to effectively handle incomplete multi-view data and insufficient label information.
- Extensive experiments on real-world datasets demonstrate the effectiveness of DIMvLN in improving the performance of multi-view learning tasks.
</div>
</div>

# Projects

- Robust Multiple Instance Learning via Sparse Optimization, [National Science Foundation of China](https://www.nsfc.gov.cn/), 2020–2022, Principal Investigator.

- Dynamic Multi-label Learning Theory and Methods for Open-source Intelligence Analysis, [National Science Foundation of China](https://www.nsfc.gov.cn/), 2024–2027, Principal Investigator.

- Provincial NSF Project for Distinguished Young Scholars， [National Science Foundation of Hunan Province](https://kjt.hunan.gov.cn/kjt/zxgz/zkjj/index.html), 2025–2027, Principal Investigator.


# 🎖 Honors and Awards
- Outstanding Talents Program of NUDT, 07/2021
- Fund for NUDT Young Innovator Awards, 12/2020
- Outstanding Doctoral Dissertation Award of SESC, 10/2020 (4 in China)
- Outstanding Doctoral Dissertation Award of Hunan Province, 08/2020
- NUDT Postgraduate Academic Innovation Star, 10/2017 (10 out of 300+)
- NUDT ZhouMingXi Scholarship, 12/2017
- CSC Scholarship, 10/2015-09/2017

-  中国系统工程学会优秀博士学位论文奖，10/2020
-  湖南省优秀博士学位论文，08/2020

# 📖 Educations and Work Experience

- 09/2007-06/2011: National University of Defense Technology (NUDT,国防科技大学), B.E.

- 09/2011-12/2013: National University of Defense Technology (NUDT,国防科技大学), Ph.D.

- 03/2014-06/2018: National University of Defense Technology (NUDT,国防科技大学), Ph.D.

- 10/2015-09/2017: University of Michigan, Ann Arbor (UMich,美国密歇根大学安娜堡分校), Ph.D.

- 06/2020-Now: National University of Defense Technology (NUDT), Associate Professor in College of Sciences

- 07/2018-12/2020: National University of Defense Technology (NUDT), Assistant Professor in College of Sciences

# 💬 Invited Talks

- 08/2017: Functional Annotation of Human Protein Coding Isoforms via Non-convex Multi-Instance Learning, _Proceedings of the 23rd ACM SIGKDD International Conference on Knowledge Discovery & Data Mining_, **Halifax, Canada** (Oral)\| [\[video\]](https://videolectures.net/videos/kdd2017_luo_human_protein_coding)
- 10/2020: "基于非凸稀疏优化的鲁棒多示例学习方法", _中国系统工程学会第21届学术年会 2020_, **中国陕西西安**,  大会报告
- 01/2019: "高维数据特征分析方法", _学校量子交叉学术年会 2018_, **中国湖南长沙**,  小组报告

# Teaching Experience

- Probability and Mathematical Statistics(概率论与梳理统计，春季学期，面向工科专业) -- 2020-2022，NUDT

- Mathematical Modeling(数学建模，春季学期，面向工科专业) -- 2023-Now，NUDT

- Statistical Forecasting and Decision Making(统计预测与决策，秋季学期，面向应用统计学专业) -- 2019-Now, NUDT

- Multivariate Statistical Analysis(多元统计分析，秋季学期，面向应用统计学专业) -- 2020 Fall, NUDT

# Contact

Office: Room S481, College of Sciences, National University of Defense Technology
办公地址： 国防科技大学理学院应用数学研究中心S481室

Address: College of Liberal Arts and Sciences, National University of Defense Technology: No.1 Fuyuan Road, Kaifu District, Changsha, Hunan, China, 410073
通讯地址： 湖南省长沙市开福区福元路一号国防科技大学理学院应用数学研究中心