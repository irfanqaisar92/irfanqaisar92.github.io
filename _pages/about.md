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

He is a Ph.D. candidate at Tsinghua University, supervised by Prof. Qianchuan Zhao. His research focuses on occupant-centric control strategies for smart buildings, combining energy simulation, real-time sensing, and machine learning techniques. He has developed Transformer- and LLM-based models for room occupancy detection, estimation, and HVAC control, with the goal of enhancing energy efficiency and indoor comfort. His broader interests include sensor fusion, intelligent automation, and sustainable building technologies.

View his publications and citation metrics on <a href='https://scholar.google.com/citations?user=KNz5cz4AAAAJ&hl=en'>Google Scholar <strong><span id='total_cit'></span></strong></a>. 


# 🔥 News
- **2025.06.26:** 🎉🎉 My article has been accepted for publication in the **Global Youth Roundtable** column: *"AGI & My Career Future: Personal Reflection Guide."* 

# 📝 Publications 

**Under Review Publications**

- **Exploring Large Language Models for Indoor Occupancy Detection and Estimation for Smart Buildings**  
  **Irfan Qaisar**, Kailai Sun, Qianchuan Zhao


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

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CEAI 2020</div>
      <img src='images/exponential.png' alt="OCC experiment" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[**Event-triggered H∞ consensus control for multi-agent systems under time-varying delay**](#)

**Irfan Qaisar**, Muhammad Shamrooz Aslam, Chuan Zhou  
*Control Engineering and Applied Informatics*, Vol. 22, No. 3, 2020, pp. 25–32  

This paper presents an event-triggered control strategy for multi-agent systems with directed communication topologies and time-varying delays. A new Lyapunov-based approach with linear matrix inequalities (LMIs) ensures H∞ consensus performance while reducing communication load. Simulation results confirm the effectiveness of the proposed method in achieving stability and reducing data transmissions.

  </div>
</div>

  <div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Asian Journal of Control 2022</div>
      <img src='images/fuzzy.png' alt="fuzzy control" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[**Adaptive event-triggered robust H∞ control for Takagi–Sugeno fuzzy networked Markov jump systems with time-varying delay**](https://doi.org/10.1002/asjc.2762)

Muhammad Shamrooz Aslam, **Irfan Qaisar**, Abdul Majid, Summera Shamrooz  
*Asian Journal of Control*, 2022, Volume 25, Issue 1, pp. 213–228  
This paper proposes an adaptive event-triggered robust H∞ controller for Takagi–Sugeno fuzzy Markov jump systems with time-varying delays. A novel stochastic Lyapunov–Krasovskii functional and a delay decomposition method are introduced to improve control performance while reducing communication costs. A truck-trailer application validates the proposed design.

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">NAHS 2020</div>
      <img src='images/quantized.png' alt="quantized fuzzy system" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[**Quantized event-triggered feedback control under fuzzy systems with time-varying delay and actuator fault**](https://doi.org/10.1016/j.nahs.2019.100823)

Muhammad Shamrooz Aslam, **Irfan Qaisar**, Muhammad Ahsan Saleem  
*Nonlinear Analysis: Hybrid Systems*, Volume 35, 2020, 100823  
This work proposes a robust H∞ controller for Takagi–Sugeno fuzzy networked control systems with actuator faults and time-varying delays. A co-designed quantization and event-triggered mechanism significantly reduces communication load while ensuring system stability. Simulation on a truck-trailer system validates the approach.

  </div>
</div>

**Conference Papers**

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CASE 2025</div>
      <img src='images/Methodcp.jpg' alt="multi-agent" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

***[Dynamic Occupancy Measurement for Smart Buildings: A Few-shot Large Language Model Approach](https://ieeexplore.ieee.org/abstract/document/11163957)**  
*Irfan Qaisar, Kailai Sun, Qianchuan Zhao*  
*2025 IEEE CASE, Los Angeles, USA*  

This paper presents an LLM-based framework for occupancy detection and estimation in smart buildings. Leveraging few-shot and in-context learning, LLMs (LLaMA 3.2, Gemini-Pro, DeepSeek-R1) outperform traditional models, achieving up to 95.8% accuracy.
  
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CCDC 2019</div>
      <img src='images/ccdc.png' alt="multi-agent" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[**Exponential Stability for Event-triggered Consensus Control of Heterogeneous Multi-Agent Systems**](#)  
**Irfan Qaisar**, Chuan Zhou, Zhengqing Shi, Wei Xu, Peng Xu  
*31st Chinese Control and Decision Conference (CCDC), 2019*  

This paper addresses the consensus control problem for heterogeneous multi-agent systems using dual event-triggered schemes. It proposes a novel exponential stability criterion based on Lyapunov methods and linear matrix inequalities (LMIs). Simulation results validate the effectiveness of the proposed approach in reducing communication overhead while maintaining stability.
  
  </div>
</div>

## 📝 Reviewer

**Journals Reviewed:**   
- *Building and Environment*
- *Energy & Buildings* 
- *Sustainable and Clean Buildings*  
- *Scientific Data*
- *Results in Control and Optimization*

# 🎖 Honors and Awards
- *2025.10* Awarded the **Tsinghua University Comprehensive Excellence Scholarship (Second Class)** for outstanding academic performance and moral conduct.
- *2024.12* Awarded the **Tsinghua University Comprehensive Excellence Scholarship (Second Class)** for outstanding academic performance and moral conduct.   
- *2024.12* Designated as a **Tsinghua-Nike Sustainability Ambassador** after completing the Tsinghua-Nike Sustainability Fellowship, in recognition of contributions to sustainable development.
- *2024.12* Received the **Logic Star Award** in the **ESG Innovation Case Analysis Roadshow** for outstanding logical clarity and structured argumentation in presenting an ESG case.
- *2021.09 – Present* Awarded the **Chinese Government Scholarship** — a fully-funded scholarship for Ph.D. studies at Tsinghua University.  
- *2016.09 – 2019.04* Awarded the **Nanjing Municipal Government Scholarship** — a fully-funded scholarship for postgraduate studies at Nanjing University of Science and Technology.  
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

# 💼 Work Experience

### Research Assistant  
**Center for Intelligent and Networked Systems (CFINS), Department of Automation, Tsinghua University** — *Beijing, China*  
*09/2021 – Present*  
- Conducting research on occupant-centric control strategies for smart buildings using machine learning and real-time sensor data.  
- Developing predictive models using Transformers and LLMs for energy-efficient HVAC control.  
- Collaborating on interdisciplinary projects related to building automation, sustainability, and AI applications.  
- Assisting with data analysis, academic writing, and publication preparation under the supervision of Prof. Qianchuan Zhao.

---
### Electrical Engineer  
**Wuxi Johnnywell Railway Equipment Technology Co., Ltd.** — *Wuxi, China*  
*06/2019 – 07/2021*  
- Programmed and commissioned PLCs, HMIs, VFDs, and industrial automation devices (e.g., sensors and actuators).  
- Diagnosed and troubleshot PLC systems and process instruments.  
- Collaborated across departments to identify workflow automation opportunities.  
- Gathered requirements from clients and end-users to design optimal automation solutions.

---

### Management Trainee  
**Design Line Architects** — *Multan, Pakistan*  
*06/2014 – 06/2016*  
- Managed responsibilities in both IT and project management departments.  
- Supported administrative and operational functions to improve efficiency.

---

### Trainee Engineer  
**Niagara Textile (Pvt) Ltd.** — *Pakistan*  
*05/2013 – 05/2014*  
- Repaired and maintained electronic control cards.  
- Designed and troubleshot electrical panels for manufacturing processes.

# 📞 Contact
E-mail:  
<a href="irfan21@mails.tsinghua.edu.cn">irfan21@mails.tsinghua.edu.cn</a>  
<a href="irfan21@ieee.org">irfan21@ieee.org</a>  

<!--# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)-->

<!--# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.-->
