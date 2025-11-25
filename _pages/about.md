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

Hi, I am Hongduan Tian, a second-year Ph.D. student at Trustworthy Machine Learning and Reasoning (TMLR) Group in Department of Computer Science, Hong Kong Baptist University, advised by [Dr. Bo Han](https://bhanml.github.io/) and [Dr. Feng Liu](https://fengliu90.github.io/index.html). Before that, I got my master degree from Nanjing University of Information Science and Technology (NUIST) and fortunately supervised by [Prof. Xiao-Tong Yuan](https://sites.google.com/site/xtyuan1980/home?authuser=0) and [Prof. Qingshan Liu](https://scholar.google.com/citations?user=2Pyf20IAAAAJ&hl=en).

Previously, my research topics mainly focused on **few-shot/meta learning, cross-domain generalization**. Currently, my research interests mainly focus on **trustworthy efficient post-training/fine-tuning/inference of foundation models** and **foundation model agents**. Moreover, I am also interested in **learning dynamics of foundation models** (see topics of [Yi Ren](https://joshua-ren.github.io/)) and **model knowledge transfer** (such as model merging etc.).

*Please feel free to [email me](mailto:hongduan.tian@gmail.com) for research, collaborations, or a casual chat.* 

<!-- *Please consider giving me [anonymous feedback](https://docs.google.com/forms/d/e/1FAIpQLSeE4_y14QlUtJ8MhltnGnWwco7J1sWprXnlGoFWFo002k26lw/viewform?usp=sf_link).* -->

# 📣 News
- **$\frak{2025.11}$**: Our paper "Cross-domain Few-shot Classification via Invariant-content Feature Reconstruction" is accepted by [IJCV](https://link.springer.com/journal/11263).
- **$\frak{2024.09}$**: Our paper "Mind the gap between prototypes and images in cross-domain finetuning" is accepted by [NeurIPS 2024](https://neurips.cc/).
- **$\frak{2024.05}$**: Our paper "MOKD: Cross-domain finetuning for few-shot classification via maximizing optimized kernel dependence" is accepted by [ICML 2024](https://icml.cc/virtual/2024/poster/33444).

# 📖 Educations
- *2023.09 - present*, Hong Kong Baptist University (HKBU), Ph.D. in Computer Science.
- *2018.09 – 2021.06*, Nanjing University of Information Science and Technology (NUIST), M.E. in Control Engineering.
- *2014.09 - 2018.06*, Nanjing University of Information Science and Technology (NUIST), B.E. in Automation.

<!-- # 📝 Featured Publications
TODO -->

# 📝 Publications on Few-shot / Meta Learning
✉️ Corresponding author.

<div class='paper-box'><div class='paper-box-image'><div>
<img src='/_pages/data/figures/ijcv_ifr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[![Static Badge](https://img.shields.io/badge/Journal-IJCV-orange)]() **Cross-domain Few-shot Classification via Invariant-content Feature Reconstruction**.  

**Hongduan Tian**, Feng Liu, Ka Chun Cheung, Zhen Fang, Simon See, Tongliang Liu, Bo Han✉️.

<!--[[paper]](https://arxiv.org/pdf/2410.12474)
[[code]](https://github.com/HongduanTian/CoPA)
[[slides]](./data/slides/NeurIPS24_CoPA.pdf)
[[poster]](./data/poster/neurips24_CoPA.pdf)
[[CN-video]](https://www.bilibili.com/video/BV1vaUNYTEr3/?spm_id_from=333.999.0.0&vd_source=a1aae47e2835186f922fa2e1c94933c9)
[[EN-video]](https://recorder-v3.slideslive.com/?share=93487&s=0f9f72ed-d9ad-4f34-a0aa-154e07b6f3d7)-->   
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div>
<img src='/_pages/data/figures/copa_poster.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[![Static Badge](https://img.shields.io/badge/Conference-NeurIPS'24-blue)]() **Mind the Gap Between Prototypes and Images in Cross-domain Finetuning**.  

**Hongduan Tian**, Feng Liu, Zhanke Zhou, Tongliang Liu, Chengqi Zhang, Bo Han✉️.

[[paper]](https://arxiv.org/pdf/2410.12474)
[[code]](https://github.com/HongduanTian/CoPA)
[[slides]](./data/slides/NeurIPS24_CoPA.pdf)
[[poster]](./data/poster/neurips24_CoPA.pdf)
[[CN-video]](https://www.bilibili.com/video/BV1vaUNYTEr3/?spm_id_from=333.999.0.0&vd_source=a1aae47e2835186f922fa2e1c94933c9)
[[EN-video]](https://recorder-v3.slideslive.com/?share=93487&s=0f9f72ed-d9ad-4f34-a0aa-154e07b6f3d7)   
  
</div>
</div>
<!--<details>
<summary>Quick Introduction</summary>
 In cross-domain few-shot classification (CFC), recent works mainly focus on adapting a simple transformation head on top of a frozen pre-trained backbone with few labeled data to project embeddings into a task-specific metric space where classification can be performed by measuring similarities between image instance and prototype representations. Technically, an assumption implicitly adopted in such a framework is that the prototype and image instance embeddings share the same representation transformation. However, in this paper, we find that there naturally exists a gap, which resembles the modality gap, between the prototype and image instance embeddings extracted from the frozen pre-trained backbone, and simply applying the same transformation during the adaptation phase constrains exploring the optimal representation distributions and shrinks the gap between prototype and image representations. <br><br>
 To solve this problem, we propose a simple yet effective method, contrastive prototype-image adaptation (CoPA), to adapt different transformations for prototypes and images similarly to CLIP by treating prototypes as text prompts. <br><br>
Extensive experiments on Meta-Dataset demonstrate that CoPA achieves the state-of-the-art performance more efficiently. Meanwhile, further analyses also indicate that CoPA can learn better representation clusters, enlarge the gap, and achieve the minimum validation loss at the enlarged gap.
</details>-->



<div class='paper-box'><div class='paper-box-image'><div>
<img src='/_pages/data/figures/mokd_poster.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[![Static Badge](https://img.shields.io/badge/Conference-ICML'24-blue)]() **MOKD: Cross-domain Finetuning via Maximizing Optimized Kernel Dependence**. 

**Hongduan Tian**, Feng Liu, Tongliang Liu, Bo Du, Yiu-ming Cheung, Bo Han✉️. 

[[paper]](https://arxiv.org/pdf/2405.18786)
[[code]](https://github.com/HongduanTian/MOKD)
[[slides]](./data/slides/ICML24_MOKD.pdf)
[[poster]](./data/poster/icml24_mokd.pdf)
[[CN-video]](https://www.bilibili.com/video/BV1k4421X7zK/?spm_id_from=333.1007.top_right_bar_window_dynamic.content.click&vd_source=a1aae47e2835186f922fa2e1c94933c9)
[[EN-video]](https://www.youtube.com/watch?v=uWMM63Sv0ZI&t=110s)   
  
</div>
</div>
<!--<details>
<summary>Quick Introduction</summary>
 In cross-domain few-shot classification, nearest centroid classifier (NCC) aims to learn representations to construct a metric space where few-shot classification can be performed by measuring the similarities between samples and the prototype of each class. An intuition behind NCC is that each sample is pulled closer to the class centroid it belongs to while pushed away from those of other classes. However, in this paper, we find that there exist high similarities between NCC-learned representations of two samples from different classes.<br><br>
In order to address this problem, we propose a bi-level optimization framework, maximizing optimized kernel dependence (MOKD) to learn a set of class-specific representations that match the cluster structures indicated by labeled data of the given task. 
 Specifically, MOKD first optimizes the kernel adopted in Hilbert-Schmidt independence criterion (HSIC) to obtain the optimized kernel HSIC (opt-HSIC) that can capture the dependence more precisely. Then, an optimization problem regarding the opt-HSIC is addressed to simultaneously maximize the dependence between representations and labels and minimize the dependence among all samples.<br><br> 
Extensive experiments on Meta-Dataset demonstrate that MOKD can not only achieve better generalization performance on unseen domains in most cases but also learn better data representation clusters.
</details>-->


<div class='paper-box'><div class='paper-box-image'><div>
<img src='/_pages/data/figures/meta_prune.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[![Static Badge](https://img.shields.io/badge/Conference-ECCV'20-blue)]() **Meta-learning with network pruning**.  
**Hongduan Tian**✉️, Bo Liu, Xiao-Tong Yuan✉️, Qingshan Liu.

[[paper]](https://arxiv.org/pdf/2007.03219)
[[code]](https://github.com/HongduanTian/Dense-Sparse-Dense-Reptile)
<!--[[slides]](/_pages/data/slides-neural-atoms.pdf)
[[poster]](/_pages/data/poster-neural-atoms.pdf)
[[EN-video]](https://recorder-v3.slideslive.com/?share=92308&s=8e966150-4ba4-41b7-97d3-8ed0c1a1cd0c)
[[CN-video]](https://www.bilibili.com/video/BV1qH4y1L7mb/?share_source=copy_web&vd_source=65ec14228a98f635bf0406f14c7f8660&t=5342)-->  
  
</div>
</div>
<!-- <details>
<summary>Quick Introduction</summary>
 Meta-learning is a powerful paradigm for few-shot learning. Although with remarkable success witnessed in many applications, the existing optimization based meta-learning models with over-parameterized neural networks have been evidenced to ovetfit on training tasks.<br><br> 
 To remedy this deficiency, we propose a network pruning based meta-learning approach for overfitting reduction via explicitly controlling the capacity of network. A uniform concentration analysis reveals the benefit of network capacity constraint for reducing generalization gap of the proposed meta-learner. We have implemented our approach on top of Reptile assembled with two network pruning routines: Dense-Sparse-Dense (DSD) and Iterative Hard Thresholding (IHT).<br><br>
 Extensive experimental results on benchmark datasets with different over-parameterized deep networks demonstrate that our method not only effectively alleviates meta-overfitting but also in many cases improves the overall generalization performance when applied to few-shot classification tasks.
</details>-->

# 💻 GitHub Repositories

- [CoPA](https://github.com/HongduanTian/CoPA)
<img src="https://img.shields.io/github/stars/HongduanTian/CoPA?color=yellow&label=Origin" alt="Stars" >
<img src="https://img.shields.io/github/stars/tmlr-group/CoPA?color=yellow&label=Official" alt="Original Stars" >
- [MOKD](https://github.com/HongduanTian/MOKD)
<img src="https://img.shields.io/github/stars/HongduanTian/MOKD?color=yellow&label=Origin" alt="Stars" >
<img src="https://img.shields.io/github/stars/tmlr-group/MOKD?color=yellow&label=Official" alt="Stars" >
- [Dense-Sparse-Dense-Reptile](https://github.com/HongduanTian/Dense-Sparse-Dense-Reptile)
<img src="https://img.shields.io/github/stars/HongduanTian/Dense-Sparse-Dense-Reptile?color=yellow&label=Origin" alt="Stars" >


# 🎖 Awards
- *2024.11*, Research Performance Award, HKBU CS Department.
- *2024.10*, NeurIPS Scholar Award.

<!--💬 Talks
- *2024.06*, Youth PhD Talk on Trustworthy Machine Learning @AI Time, Online.
[[Video]](https://www.bilibili.com/video/BV1ag4y1Q7ye/?t=7945)-->

# 💻 Services
- Conference Reviewer for ICML, NeurIPS, ICLR, AISTATS.
- Journal Reviewer for TPAMI, TNNLS, TMLR, NEUNET.

# 🎤 Invited Talks
- *2024.11*, Mind the Gap Between Prototypes and Images in Cross-domain Finetuning @[AI TIME](https://www.aitime.cn/), Online. [[Video]](https://www.bilibili.com/video/BV1vaUNYTEr3/?spm_id_from=333.999.0.0&vd_source=a1aae47e2835186f922fa2e1c94933c9)
- *2024.06*, MOKD: Cross-domain finetuning for few-shot classification via maximizing optimized kernel dependence @[AI TIME](https://www.aitime.cn/), Online. [[Video]](https://www.bilibili.com/video/BV1k4421X7zK/?spm_id_from=333.1007.top_right_bar_window_dynamic.content.click&vd_source=a1aae47e2835186f922fa2e1c94933c9)



# 🏫 Teaching
- **COMP7015** (G) Artificial Intelligence, Sem. 1, 2025 - 2026
- **COMP7250** (G) Machine Learning, Sem. 2, 2024 - 2025
- **COMP7180** (G) Quantitative Methods for Data Analytics and Artificial Intelligence, Sem. 1, 2024 - 2025
- **COMP7940** (G) Cloud Computing, Sem. 2, 2023 - 2024

# 📖 Academic Experiences
- *2023.09 - present*, PhD student @HKBU-[TMLR Group](https://bhanml.github.io/group.html), advised by Dr. Bo Han.
- *2022.07 - 2023.05*, Research intern @HKBU-[TMLR Group](https://bhanml.github.io/group.html), advised by Dr. Bo Han and Dr. Feng Liu.


# 🏢 Industrial Experiences
- *2022.07 - Present*, Research Intern @NVIDIA [NVAITC](https://resources.nvidia.com/en-us-gps-ai-capacity-building/nvaitc-research), host by Charles Cheung.
- *2024.11 - Now*, Remote Research Intern @WeChat, supervised by Xiangyu Zhu and Rolan Yan
- *2024.06 - 2024.08*, Research Intern @WeChat, host by Xiangyu Zhu and Rolan Yan
- *2023.07 - 2023.08*, Research Intern @Alibaba.
- *2021.07 - 2022.07*, Algorithm Engineer @ZTE Nanjing Research and Development Center.


  
<!-- <div align=center> -->
<!-- <a href='https://clustrmaps.com/site/1byjf'  title='Visit tracker'><img src='//clustrmaps.com/map_v2.png?cl=080808&w=400&t=tt&d=EuVM39DBt0G0cQJh20EJFBL7BHU5A5hzsTXUdCbe7Ic&co=ffffff&ct=808080'/></a> -->
<!--<a href='https://clustrmaps.com/site/1byjf'  title='Visit tracker'><img src='//clustrmaps.com/map_v2.png?cl=080808&w=a&t=m&d=EuVM39DBt0G0cQJh20EJFBL7BHU5A5hzsTXUdCbe7Ic&co=ffffff&ct=808080'/></a>-->
<a href="https://clustrmaps.com/site/1bztd" title="Visit tracker"><img src="//www.clustrmaps.com/map_v2.png?d=9WmKAuGZx-jp_Cqemh_qyo-Fhw-l77tju_9bukYAC-o&cl=ffffff"></a>
<!-- </div> -->
