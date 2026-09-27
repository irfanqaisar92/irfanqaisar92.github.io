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

Irfan Qaisar received his Ph.D. in Control Science and Engineering from Tsinghua University, Beijing, China, in October 2026. His research focuses on artificial intelligence for smart and sustainable built environments, with particular interests in occupant sensing and behavior modeling, occupancy forecasting, multimodal AI, large language models and agentic AI, occupant-centric HVAC control, building energy management, and data-driven environmental modeling.

His work integrates machine learning, deep learning, computer vision, large language models, building simulation, and intelligent control to develop energy-efficient, human-centered, and autonomous building systems.

View his complete publication record and citation metrics on <a href='https://scholar.google.com/citations?user=KNz5cz4AAAAJ&hl=en'>Google Scholar <strong><span id='total_cit'></span></strong></a>.


# 🔥 News

- **2026.10:** 🎓 Completed Ph.D. in **Control Science & Engineering** at **Tsinghua University**.
- **2026.09:** 🎉 Our article, *“Experimental study on surveillance video-based indoor occupancy measurement for occupant-centric control,”* was published in **Building and Environment**.
- **2026:** 🎉 Our article, *“OCC-Mamba: A Mamba-based deep learning approach for indoor occupancy prediction,”* was published in **Building and Environment**.
- **2026:** 🎉 Our article, *“Exploring large language models for indoor occupancy measurement in smart office buildings,”* was published in **Building and Environment**.
- **2025:** 🎉 Presented *“Dynamic Occupancy Measurement for Smart Buildings: A Few-shot Large Language Model Approach”* at **IEEE CASE 2025**, Los Angeles, USA.
- **2026:** 🏅 Awarded the **Tsinghua University Comprehensive Excellence Scholarship (Second Class)**.
- **2026:** 🎖 Awarded the **Belt and Road Ambassador Scholarship** by the Overseas Chinese Charity Foundation of China.


# 📝 Publications

## Selected Publications

### 1. OCC-Mamba: A Mamba-based deep learning approach for indoor occupancy prediction

[**OCC-Mamba: A Mamba-based deep learning approach for indoor occupancy prediction**](https://doi.org/10.1016/j.buildenv.2025.114085)

**Irfan Qaisar**, Kailai Sun, Dianyu Zhong, Xu Yang, Xi Miao, Qianchuan Zhao  
*Building and Environment*, Volume 289, 2026, Article 114085

This study proposes OCC-Mamba, a state-space deep learning model for indoor occupancy prediction. The model is validated on heterogeneous real-world datasets from China, Singapore, and Italy and is further evaluated for occupant-centric HVAC control using EnergyPlus.

👉 [Code and implementation](https://github.com/irfanqaisar92/OCCMamba)


### 2. Experimental study on surveillance video-based indoor occupancy measurement for occupant-centric control

[**Experimental study on surveillance video-based indoor occupancy measurement for occupant-centric control**](https://doi.org/10.1016/j.buildenv.2026.115200)

**Irfan Qaisar**, Kailai Sun, Qingshan Jia, Qianchuan Zhao  
*Building and Environment*, Volume 305, 2026, Article 115200

This study evaluates detection-, tracking-, and reasoning-enhanced surveillance-video pipelines for indoor occupancy measurement. It integrates computer vision, large language models, and vision-language models with occupant-centric HVAC control and demonstrates the benefits of reasoning-enhanced occupancy estimation for energy-efficient building operation.


### 3. Exploring large language models for indoor occupancy measurement in smart office buildings

[**Exploring large language models for indoor occupancy measurement in smart office buildings**](https://doi.org/10.1016/j.buildenv.2025.113860)

**Irfan Qaisar**, Kailai Sun, Qianchuan Zhao  
*Building and Environment*, Volume 287, 2026, Article 113860

This study presents an LLM-based framework for real-time indoor occupancy measurement using few-shot learning, chain-of-thought reasoning, and in-context learning. The framework is evaluated on real-world office datasets from China and Singapore and is further connected with occupant-centric control simulations.

👉 [Code and implementation](https://github.com/kailaisun/LLM-occupancy)


### 4. An experimental comparative study of energy saving based on occupancy-centric control in smart buildings

[**An experimental comparative study of energy saving based on occupancy-centric control in smart buildings**](https://doi.org/10.1016/j.buildenv.2024.112322)

**Irfan Qaisar**, Wei Liang, Kailai Sun, Tian Xing, Qianchuan Zhao  
*Building and Environment*, Volume 268, 2025, Article 112322

This study investigates occupancy-centric HVAC control in a multi-zone smart building using real-world occupancy data and OpenStudio-EnergyPlus simulations. It evaluates multiple operational intervals to study their effects on energy efficiency and occupant comfort.

👉 [Dataset and implementation](https://github.com/irfanqaisar92/OCC-in-Buildings)


### 5. Dynamic Occupancy Measurement for Smart Buildings: A Few-shot Large Language Model Approach

[**Dynamic Occupancy Measurement for Smart Buildings: A Few-shot Large Language Model Approach**](https://ieeexplore.ieee.org/abstract/document/11163957)

**Irfan Qaisar**, Kailai Sun, Qianchuan Zhao  
*2025 IEEE 21st International Conference on Automation Science and Engineering (CASE)*, Los Angeles, USA, 2025

This conference paper presents an LLM-based framework for indoor occupancy detection and estimation using few-shot and in-context learning. The study compares LLMs with conventional machine-learning models using real-world datasets and evaluates the potential of LLM-based occupancy information for energy-efficient building control.


### 6. Building occupancy number prediction: A Transformer approach

[**Building occupancy number prediction: A Transformer approach**](https://doi.org/10.1016/j.buildenv.2023.110807)

Kailai Sun, **Irfan Qaisar**, Muhammad Arslan Khan, Tian Xing, Qianchuan Zhao  
*Building and Environment*, Volume 244, 2023, Article 110807

This study develops a Transformer-based approach for multi-zone building occupancy number prediction using real-world multi-sensor data. The model is compared with conventional machine-learning and deep-learning baselines and demonstrates strong predictive performance.


### 7. Multi-Sensor-Based Occupancy Prediction in a Multi-Zone Office Building with Transformer

[**Multi-Sensor-Based Occupancy Prediction in a Multi-Zone Office Building with Transformer**](https://doi.org/10.3390/buildings13082002)

**Irfan Qaisar**, Kailai Sun, Qianchuan Zhao, Tian Xing, Hu Yan  
*Buildings*, Volume 13, 2023, Article 2002

This study introduces a Transformer-based occupancy prediction network using multi-sensor information, including occupancy, indoor environmental conditions, and HVAC operation. The model is evaluated across multiple prediction horizons and compared with conventional machine-learning and deep-learning approaches.


### 8. Energy baseline prediction for buildings: A review

[**Energy baseline prediction for buildings: A review**](https://doi.org/10.1016/j.rico.2022.100129)

**Irfan Qaisar**, Qianchuan Zhao  
*Results in Control and Optimization*, Volume 7, 2022, Article 100129

This review summarizes physics-based, data-driven, and hybrid approaches for building energy baseline prediction. It discusses model development, important input variables, performance evaluation, and the role of energy baselines in estimating building energy savings.


**For the complete publication list and citation information, please visit my [Google Scholar](https://scholar.google.com/citations?user=KNz5cz4AAAAJ&hl=en) profile.**


## Manuscripts Under Review

### Hierarchical Control Framework Integrating Large Language Models with Reinforcement Learning for Decarbonized HVAC Operation

Dianyu Zhong, Tian Xing, Kailai Sun, Xu Yang, Heye Huang, **Irfan Qaisar**, Tinggang Jia, Shaobo Wang, Qianchuan Zhao  
*Under Review*

This work develops a hierarchical HVAC control framework in which a fine-tuned large language model generates state-dependent feasible action masks and a reinforcement-learning controller performs constrained optimization within the reduced action space.


### Closed-Loop Agentic LLMs for Occupant-Centric HVAC Supervisory Control in Smart Buildings

**Irfan Qaisar**, Kailai Sun, Qianchuan Zhao  
*Under Review*

This study develops an evaluator-guided agentic LLM framework for closed-loop occupant-centric HVAC supervisory control. The system combines LLM-generated zone-level actions, evaluator-based refinement, deterministic validation, and EnergyPlus-based closed-loop simulation.


### Additional manuscript on multi-agent LLM-guided occupant-centric HVAC control

*Under double-blind review*

This manuscript investigates a multi-agent LLM-guided model predictive control framework for occupant-centric HVAC systems. The manuscript title, authorship, and venue are omitted here while the anonymous review process is active.


# 📝 Academic Service

## Peer Reviewer

- *Applied Energy*
- *Automation in Construction*
- *Building and Environment*
- *Energy and Buildings*
- *Engineering Applications of Artificial Intelligence*
- *Expert Systems with Applications*
- *ISA Transactions*
- *Journal of Building Engineering*
- *MethodsX*
- *Results in Control and Optimization*


# 🎖 Honors and Awards

- *2026* Awarded the **Belt and Road Ambassador Scholarship** by the Overseas Chinese Charity Foundation of China.
- *2026, 2025, 2024* Awarded the **Tsinghua University Comprehensive Excellence Scholarship (Second Class)**.
- *2024* Designated as a **Tsinghua-Nike Sustainability Ambassador** after completing the Tsinghua-Nike Sustainability Fellowship.
- *2024* Received the **Logic Star Award** in the **ESG Innovation Case Analysis Roadshow**.
- *2021.09 – 2026.10* Awarded the **Chinese Government Scholarship**, a fully funded scholarship for Ph.D. studies at Tsinghua University.
- *2016.09 – 2019.04* Awarded the **Nanjing Municipal Government Scholarship**, a fully funded scholarship for postgraduate studies at Nanjing University of Science and Technology.
- *2021.07* Recognized as part of the **Technical Innovation Team** for *Hack 11: “How AI Can Help Us Build an Intelligent and Sustainable Future?”* during the **Tsinghua Global Summer School 2021 (SDG Hack)**.


# 📖 Education

- *2021.09 – 2026.10*  
  **Ph.D. in Control Science & Engineering**  
  Tsinghua University （清华大学）, Beijing, China  
  **Supervisor:** Prof. Qianchuan Zhao  
  **Dissertation:** *Multi-Sensor Occupancy Sensing for Occupant-Centric Control in Smart Buildings*

- *2016.09 – 2019.04*  
  **M.S. in Control Theory & Control Engineering**  
  Nanjing University of Science and Technology （南京理工大学）, Nanjing, China

- *2009.01 – 2013.05*  
  **B.E. in Electronic Engineering**  
  Dawood University of Engineering and Technology, Karachi, Pakistan


# 💼 Research and Professional Experience

### Research Assistant

**Center for Intelligent and Networked Systems (CFINS), Department of Automation, Tsinghua University** — *Beijing, China*  
*09/2021 – 09/2026*

- Conducted research on artificial intelligence for smart and sustainable buildings, with a focus on occupancy sensing, prediction, occupant-centric control, and building energy management.
- Developed Transformer-, Mamba-, LLM-, and agentic-AI-based methods for occupancy modeling and intelligent HVAC control.
- Integrated real-world sensor and video data with EnergyPlus and OpenStudio for closed-loop building-control and energy-performance evaluation.
- Investigated computer-vision and vision-language-model pipelines for surveillance-video-based indoor occupancy measurement.
- Contributed to research on large language models, multimodal AI, reinforcement learning, and model predictive control for smart-building applications.
- Conducted data analysis, experimental validation, academic writing, and collaborative research under the supervision of Prof. Qianchuan Zhao.


### Electrical Engineer

**Wuxi Johnnywell Railway Equipment Technology Co., Ltd.** — *Wuxi, China*  
*06/2019 – 07/2021*

- Programmed and commissioned PLCs, HMIs, VFDs, sensors, actuators, and industrial automation systems.
- Diagnosed and troubleshot PLC systems, electrical control systems, and process instruments.
- Collaborated across departments to identify workflow and automation opportunities.
- Gathered technical requirements from clients and end users to support automation-system design and implementation.


### Management Trainee

**Design Line Architects** — *Multan, Pakistan*  
*06/2014 – 06/2016*

- Supported IT, project management, administrative, and operational activities.
- Assisted with process coordination and workflow improvement.


### Trainee Engineer

**Niagara Textile (Pvt) Ltd.** — *Pakistan*  
*05/2013 – 05/2014*

- Repaired and maintained electronic control cards.
- Designed, assembled, and troubleshot electrical panels for manufacturing processes.


# 📜 Patent

**Waste Heat Recovery Optimization Control System and Method**  
Chinese Patent Application **CN 2024105441305**, filed April 30, 2024.  
Co-inventor with Tsinghua University and Hitachi Ltd.


# 📞 Contact

E-mail:  
<a href="mailto:irfanqaisar92@gmail.com">irfanqaisar92@gmail.com</a>  
<a href="mailto:irfan21@ieee.org">irfan21@ieee.org</a>  
<a href="mailto:irfan21@mails.tsinghua.edu.cn">irfan21@mails.tsinghua.edu.cn</a>

Google Scholar:  
<a href="https://scholar.google.com/citations?user=KNz5cz4AAAAJ&hl=en">Irfan Qaisar</a>

ORCID:  
<a href="https://orcid.org/0000-0002-4831-977X">0000-0002-4831-977X</a>

GitHub:  
<a href="https://github.com/irfanqaisar92">irfanqaisar92</a>

LinkedIn:  
<a href="https://www.linkedin.com/in/irfan-qaisar-a87951371/">Irfan Qaisar</a>
