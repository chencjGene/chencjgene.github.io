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

I received my Ph.D. degree from <a href="http://www.tsinghua.edu.cn/publish/then/index.html">Tsinghua University</a>, advised by Prof. <a href="http://shixialiu.com/">Shixia Liu</a>. 
Before that, I reveived my B.S. in Electronic Engineering from <a href="https://www.ustc.edu.cn/">University of Science and Technology of China</a>.
My research interest focuses on visual analytics and machine learning, especially visual analysis methods to improve training data quality.


<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2023.08*: &nbsp;🎉🎉 Three papers are accepted by IEEE VIS. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE VIS 2023</div><img src='images/unievaluator.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Unified Interactive Model Evaluation for Classification, Object Detection, and Instance Segmentation in Computer Vision](https://arxiv.org/abs/2308.05168)

**Changjian Chen**, Yukai Guo, Fengyuan Tian, Shilong Liu, Weikai Yang, Zhaowei Wang, Jing Wu, Hang Su, Hanspeter Pfister, Shixia Liu. 

IEEE VIS (to be appear).

[Video](http://uni-evaluator.thuvis.org/) \| [Code](http://uni-evaluator.thuvis.org/)
</div>
</div>

<!-- ----------------------------------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE VIS 2023</div><img src='images/CA-Grid.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Cluster Aware Grid Layout](https://arxiv.org/abs/2308.03651)

Yuxing Zhou*, Weikai Yang*, Jiashu Chen, **Changjian Chen**, Zhiyang Shen, Xiaonan Luo, Lingyun Yu, Shixia Liu. 

IEEE VIS (to be appear).

[Video](https://repo.vicayang.cc/Cluster_Aware_Grid_Layout/video.html) \| [Code](https://github.com/thu-vis/Cluster-Aware-Grid-Layout)
</div>
</div>

<!-- ----------------------------------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE VIS 2023</div><img src='images/videopro.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[VideoPro: A Visual Analytics Approach for Interactive Video Programming](https://arxiv.org/abs/2308.00401)

Jianben He, Xingbo Wang, Kam Kwai Wong, Xijie Huang, **Changjian Chen**, Zixin Chen, Fengjie Wang, Min Zhu, Huamin Qu. 

IEEE VIS (to be appear).

</div>
</div>

<!-- ----------------------------------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CAD/CG 2023</div><img src='images/data_survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[基于可视分析的训练数据质量提升研究](http://shixialiu.com/publications/dataqualitycadcg/paper.pdf)

杨维铠, **陈长建**, 朱江宁, 李磊, 刘鹏, 刘世霞. 

CCF CAD/CG (to be appear). 


</div>
</div>

<!-- ----------------------------------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TVCG 2022</div><img src='images/MutualDetector.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Better Caption Supervision for Object Detection](https://ieeexplore.ieee.org/document/9664269/)

**Changjian Chen**, Jing Wu, Xiaohan Wang, Shouxing Xiang, Song-Hai Zhang, Qifeng Tang, Shixia Liu. 

IEEE Transactions on Visualization and Computer Graphics, 2022 Vol. 28(4): 1941-1954.

[Video](https://youtu.be/_Ksp9stN6bw) \| [Code](https://github.com/thu-vis/MutualDetector)

</div>
</div>

<!-- ----------------------------------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TVCG 2021</div><img src='images/DataLinker.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Interactive Graph Construction for Graph-Based Semi-Supervised Learning](https://ieeexplore.ieee.org/document/9444198/)

**Changjian Chen**, Zhaowei Wang, Jing Wu, Xiting Wang, Lan-Zhe Guo, Yu-Feng Li, Shixia Liu. 

IEEE Transactions on Visualization and Computer Graphics, 2021 Vol. 27(9): 3701-3716.

[Video](https://youtu.be/LLDzHn9qyc4) \| [Code](https://github.com/thu-vis/DataLinker)

</div>
</div>

<!-- ----------------------------------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TVCG 2021</div><img src='images/OoDAnalyzer.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OoDAnalyzer: Interactive Analysis of Out-of-Distribution Samples](https://ieeexplore.ieee.org/document/8994105)

**Changjian Chen\***, Jun Yuan\*, Yafeng Lu, Yang Liu, Hang Su, Songtao Yuan, and Shixia Liu. (* = equal contribution). 

IEEE Transactions on Visualization and Computer Graphics, 2021 Vol. 27(7): 3335-3349.

[Video](https://youtu.be/13G4RCOoiAU) \| [Code](https://github.com/thu-vis/OoDAnalyzer) \| [Slides](https://docs.google.com/presentation/d/1CoJEfQ7-y2QqpeQVFtTvFJh5Ea08x6N2/edit?usp=sharing&ouid=105845032781922238860&rtpof=true&sd=true)

</div>
</div>

<!-- ----------------------------------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVM 2021</div><img src='images/ML_survey.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Survey of Visual Analytics Techniques for Machine Learning](https://link.springer.com/article/10.1007/s41095-020-0191-7)

Jun Yuan, **Changjian Chen**, Weikai Yang, Mengchen Liu, Jiazhi Xia, Shixia Liu. 

Computational Visual Media, 2021, vol. 7(1): 3-36.

</div>
</div>

<!-- ----------------------------------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SCIENTIA 2020</div><img src='images/feature_selection.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An Interactive Feature Selection Method Based on Learning-from-Crowds](http://engine.scichina.com/doi/10.1360/SSI-2019-0208)

**Changjian Chen**, Liu Jiang, Na Lei, Shixia Liu. 

SCIENTIA SINICA Informationis, 2020 vol. 50(6): 794-812.

</div>
</div>

<!-- ----------------------------------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JoV 2019</div><img src='images/Recent_research.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Recent Research Advances on Interactive Machine Learning](https://link.springer.com/article/10.1007/s12650-018-0531-1)

Liu Jiang, Shixia Liu, **Changjian Chen**. 

Journal of Visualization, 2019 Vol. 22: 401-417.

</div>
</div>

<!-- ----------------------------------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE VIS 2018</div><img src='images/LabelInspect.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An Interactive Method to Improve Crowdsourced Annotations](https://ieeexplore.ieee.org/document/8440116/)

Shixia Liu, **Changjian Chen**, Yafeng Lu, Fangxin Ouyang, Bin Wang. 

IEEE Transactions on Visualization and Computer Graphics, 2019 Vol. 25(1): 235-245.

[Video](https://youtu.be/gg9PC1366ss) 
</div>
</div>


<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- *2022.06* Outstanding Graduates, School of Software, Tsinghua University.
- *2021.09* First-class outstanding student scholarship, Tsinghua University.
- *2020.09* First-class outstanding student scholarship, Tsinghua University.
- *2019.09* Second-class outstanding student scholarship, Tsinghua University.
- *2016.09* Seagate outstanding student scholarship, USTC.
- *2015.09* Outstanding student scholarship (top-5 in Class of Excellence for Info. Tech.), USTC.
- *2014.09* First-class outstanding student scholarship of USTC, USTC.

<!-- # 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Services
- **PC member**
  - PacificVis (Journal Track, 2023)
  - IEEE VIS (2023)
  - ChinaVis (2022, 2023)
- **Reviewer** AIIM (2022), IEEE TVCG (2022, 2023), IUI (2022), IEEE VIS (2021, 2022), JoVI (2020), ChinaVis (2018, 2019)
- **Teach assistant** Information Visualization and Visual Analytics (2018, 2019, 2020, 2021) 

# 💬 Invited Talks
- *2023.05*, Guest talks @GAMES \| [\[video\]](https://games-cn.org/games-webinar-20230518-277/). 

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->