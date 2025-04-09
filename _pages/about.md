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

I am a Ph.D. student at Tsinghua University, supervised by Prof. Qianchuan Zhao. My research focuses on occupant-centric control strategies for smart buildings, aiming to optimize energy consumption and enhance indoor environmental quality through advanced machine learning approaches.

My work integrates building energy simulation, data-driven modeling, and real-time sensing systems. I have explored and applied techniques such as deep learning, transformer architectures, and large language models (LLMs) for room occupancy detection, estimation, and prediction. In particular, I have developed LLM-based models that process structured sensor data using natural language prompts to accurately forecast occupancy patterns in real-time.

Building on this foundation, I am now extending my research to integrate LLMs with occupant-centric control strategies for HVAC systems. The goal is to create intelligent, adaptive building environments that reduce energy usage while maintaining occupant comfort.

I have conducted multiple case studies using real-world datasets, contributing to the development of advanced predictive models and control strategies for smart, energy-efficient buildings. My broader academic interests include camera-based occupancy sensing, sensor fusion, and intelligent building automation.

Beyond research, I am dedicated to academic collaboration, mentoring, and sharing knowledge through teaching and international exchange.

You can view my publication record and citation metrics on <a href='https://scholar.google.com/citations?user=KNz5cz4AAAAJ&hl=en'>Google Scholar <strong><span id='total_cit'></span></strong></a>.  


<!--# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->

# 📝 Publications 
**Journal Papers**

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Results in Control and Optimization, 2022</div>
      <img src='images/baseline.png' alt="paper image" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[**Energy baseline prediction for buildings: A review**](https://doi.org/10.1016/j.rico.2022.100129)

**Irfan Qaisar**, Qianchuan Zhao  
*Results in Control and Optimization*, Volume 7, 2022, Article 100129  
This paper presents a comprehensive review of energy baseline prediction approaches in buildings, highlighting data-driven, physical, and hybrid modeling methods.

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Buildings 2023</div>
      <img src='images/buildings.png' alt="optnet paper" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[**Multi-Sensor-Based Occupancy Prediction in a Multi-Zone Office Building with Transformer**](https://doi.org/10.3390/buildings13082002)

**Irfan Qaisar**, Kailai Sun, Qianchuan Zhao, Tian Xing, Hu Yan  
*Buildings*, Volume 13, 2023, Article 2002  
This study presents OPTnet, a Transformer-based deep learning model that uses multi-sensor data (occupancy, environmental conditions, and HVAC control) to predict room occupancy in real time. The model outperforms decision trees, LSTM, and MLP across various time horizons, offering a robust solution for occupant-centric building control.

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Building and Environment 2023</div>
      <img src='images/transformer.png' alt="transformer occ paper" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[**Building occupancy number prediction: A Transformer approach**](https://doi.org/10.1016/j.buildenv.2023.110807)

Kailai Sun, **Irfan Qaisar**, Muhammad Arslan Khan, Tian Xing, Qianchuan Zhao  
*Building and Environment*, Volume 244, 2023, 110807  
This paper proposes a Transformer-based deep learning model for multi-zone building occupancy number prediction using real-world multi-sensor data. It outperforms traditional ML methods (RF, DT, XGBoost, LSTM) and provides valuable insights for developing occupant-centric control strategies for energy-efficient buildings.

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Building and Environment 2025</div>
      <img src='images/occ.png' alt="OCC experiment" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[**An experimental comparative study of energy saving based on occupancy-centric control in smart buildings**](https://doi.org/10.1016/j.buildenv.2024.112322)

**Irfan Qaisar**, Wei Liang, Kailai Sun, Tian Xing, Qianchuan Zhao  
*Building and Environment*, Volume 268, 2025, Article 112322  
This study investigates the real-world performance of occupancy-centric HVAC control in a multi-zone smart building. By leveraging real-time camera-based occupancy data and simulating control strategies with various update intervals (5–60 minutes) using EnergyPlus and OpenStudio, the study demonstrates significant energy savings and improved thermal comfort. The work provides valuable insight into optimizing operational schedules and integrating OCC systems into real buildings.  
👉 [Dataset link](https://github.com/irfanqaisar92/OCC-in-Buildings)

  </div>
</div>

<!--[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>
- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- *2021.09 – Present* Awarded the **Chinese Government Scholarship** — a fully-funded scholarship for Ph.D. studies at Tsinghua University.  
- *2016.09 – 2019.04* Awarded the **Nanjing Municipal Government Scholarship** — a fully-funded scholarship for postgraduate studies at Nanjing University of Science and Technology.  
- *2024.12* Awarded the **Tsinghua University Comprehensive Excellence Scholarship (Second Class)** for outstanding academic performance and moral conduct.  
- *2024.12* Designated as a **Tsinghua-Nike Sustainability Ambassador** after completing the Tsinghua-Nike Sustainability Fellowship, in recognition of contributions to sustainable development.  
- *2024.12* Received the **Logic Star Award** in the **ESG Innovation Case Analysis Roadshow** for outstanding logical clarity and structured argumentation in presenting an ESG case.  
- *2021.07* Recognized as part of the **Technical Innovation Team** for *Hack 11: "How AI Can Help Us Build an Intelligent and Sustainable Future?"* during the **Tsinghua Global Summer School 2021 (SDG Hack)**. Contributed to the project *"AI to Track Down and Delete Illegal Contents on the Internet."*

# 📖 Education
- *2021.09 – Present*  
  **Ph.D. in Control Science & Engineering**  
  Tsinghua University （清华大学）, Beijing, China  

- *2016.09 – 2019.04*  
  **M.S. in Control Theory & Control Engineering**  
  Nanjing University of Science and Technology （南京理工大学）, Nanjing, China  

- *2009.01 – 2013.05*  
  **B.E. in Electronic Engineering**  
  Dawood University of Engineering and Technology, Karachi, Pakistan

# 📞 Contact
E-mail:  
<a href="irfan21@mail.tsinghua.edu.cn">irfan21@mail.tsinghua.edu.cn</a>  

<!--# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)-->

<!--# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.-->
