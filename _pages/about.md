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

Hi, I'm **Yongxi Feng (冯泳熙)**. I'm a senior undergraduate majoring in Statistics at **The Chinese University of Hong Kong, Shenzhen (CUHK-Shenzhen)**. In early 2026, I studied as an exchange student at the **University of British Columbia (UBC)**.

My research interests lie at the intersection of **machine learning reliability, clinical validity in healthcare data, and time-series modeling for wearable sensors**. I am particularly drawn to problems where statistical rigor meets real-world clinical interpretation — bridging anomaly detection and uncertainty quantification. I am actively preparing to apply for MS/PhD programs in Biostatistics for Fall 2027.

📄 **Full CV available upon request or [download here](Yongxi_Feng_PHD_Application.pdf)**. 

# 🔥 News
- *2026.05*: &nbsp;🎉 Started preparing MS/PhD applications in Biostatistics.
- *2026.04*: &nbsp;🎉 Completed exchange studies at University of British Columbia (Time Series Analysis).
- *2025.12*: &nbsp;🎉 Awarded Academic Performance Scholarship Class C.

# 📝 Selected Research 

- **Wearable Sensor Anomaly Detection – LLM-based Framework**, CUHK-Shenzhen (Advisor: Prof. Kaixin Zhou). Investigated clinical validity gaps in wearable health data; tokenized NHANES physiological signals (2,000+ participants) into LLM-compatible sequences; implemented teacher-student distillation with FRIM-based soft labels, benchmarking against statistical and deep learning baselines.

- **Decision Trajectory Modeling: TPP + Diffusion Models**, CUHK-Shenzhen (Advisor: Prof. Shuang Li). Designed dual-time architecture separating Hawkes process (event timing) from diffusion time (latent evolution), using an LLM as the score network for hazard-guided trajectory generation; contributed to paper "Hazards Guide Noise".

- **"Photo Stories": Visual-Guided Interview System**, Tencent Collaboration (Advisor: Prof. Zhongxiang Dai). Built multimodal RAG system for visually grounded oral history collection; designed question generation pipeline and cross-image context management; evaluated multiple LLMs (Gemini, Hunyuan, Tencent Yuanbao) on narrative coherence.

# 📚 Selected Course Projects

- **Time Series (STAT443): Forecasting Daily Influenza Incidence in Kawasaki City (2014-2025)**. Compared AR(1), SARIMA, and ARIMAX models under one-step-ahead framework; showed strong endogenous temporal structure limits marginal gains from meteorological covariates.

- **Machine Learning (DDA3020): Hybrid ML Trading Strategy for EMH Testing (Kaggle Competition)**. Decoupled prediction from execution: LightGBM for directional signals + PPO reinforcement learning agent for volatility-adaptive position sizing; demonstrated consistent excess returns over S&P 500 across market regimes.

- **Reinforcement Learning (DDA4230): Credit Assignment in Closed Cooperative Systems**. Systematic survey of MARL credit assignment paradigms (VDN, QMIX, QTRAN, COMA, MADDPG, TarMAC); analyzed theoretical assumptions and practical trade-offs in cooperative settings.

- **Deep Active Inference & Free Energy Principle（DDA2081）**, CUHK-Shenzhen (faculty reading group). Studied active inference, FEP, and deep learning architectures for cognitive modeling; contributed to paper draft "Deep Active Inference: Bridging the Free Energy Principle with Cognitive Modeling in Deep Learning Architectures".

# 🎖 Honors and Awards
- *AY2024-2025*: Academic Performance Scholarship – Class C
- *AY2023-2024, AY2024-2025, AY2025-2026*: **Dean's List Award** (three consecutive years)

# 📖 Educations
- *2023.08 - 2027.06 (expected)*, **B.S. in Statistics**, The Chinese University of Hong Kong, Shenzhen. CGPA 3.88/4.0 (Major 3.93/4.0), Rank 2/67.
- *2026.01 - 2026.04*, **Exchange Student**, University of British Columbia, Faculty of Science. Coursework: Time Series Analysis.

# 💬 Teaching & Service
- *2025 Fall*, **Undergraduate Teaching Assistant (USTF)** – MAT3007 Optimization, CUHK-Shenzhen.
- *AY2025-2026*, **Peer Advisor**, School of Data Science (SDS). Advised 20+ students on research and graduate applications.
- *Fall 2025*, **Panelist**, Undergraduate Academic Exchange Session (invited student speaker).
- *2024 Summer*, **Volunteer English Teacher**, Rural Primary School, Guangxi.

# ⚙️ Skills
- **Programming & Tools**: Python (PyTorch, scikit-learn, pandas), R (tidyverse), SQL, Git, LaTeX
- **Methods**: Statistical learning, time-series analysis, reinforcement learning, LLM fine-tuning, uncertainty quantification
- **Research Interests**: ML reliability in healthcare · wearable/sensor modeling · bridging anomaly detection and clinical interpretation · biostatistics methodology

# 📄 Full CV
For complete publication links, project details, verification records, and references, please download my full CV: **[Download PDF](Yongxi_Feng_PHD_Application.pdf)** 
