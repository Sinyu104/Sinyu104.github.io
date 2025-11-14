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
I am a Ph.D. student in the Department of Electrical and Computer Engineering (ECE) at the University of British Columbia (UBC), supervised by Prof. [Vincent Wong](https://people.ece.ubc.ca/~vincentw/Homepage/Home.html). My research focuses on leveraging large language models to enhance wireless communication networks, with an emphasis on areas such as semantic communication and edge computing. Prior to joining UBC, I worked as a research assistant at the Research Center for Information Technology Innovation, Academia Sinica, Taiwan, in 2023, under the supervision of Dr. [Chih-Yu Wang](https://homepage.citi.sinica.edu.tw/pages/cywang/index_en.html), where I studied phase shift design for reconfigurable intelligent surfaces. I received my B.S. and M.S. degrees in Electrical Engineering from National Cheng Kung University, Tainan, Taiwan, in 2021 and 2022, respectively. During my master's studies, I was supervised by Prof. [Kuang-Hao Liu](https://www.ee.nthu.edu.tw/khliu/) and focused on cooperative communications and the age of information (AoI) for IoT devices.

<!-- My past research interest includes RIS and cooperative communications. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com.tw/citations?user=epYiVosAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=epYiVosAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.10*: We are going to submit a paper to *IEEE International Conference on Communications (ICC) 2026*!
- *2025.8*: My paper has been accepted by *IEEE Global Communications Conference (GlobeCom) 2025*! Looking forward to coming to Taiwan!
- *2025.6*: I'm serving as a reviewer for the *IEEE Journal on Selected Areas in Communications (JSAC)*!


# 📝 Publications 
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">Globecom 2025</div><img src='images/Globecompaper2025.jpg' alt="sym" width="100%"></div></div> -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Globecom 2025</div><img src='images/Globecompaper2025_visual.jpg' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

[Generalized User-Oriented Image Semantic Coding Empowered by Large Vision-Language Model](https://arxiv.org/abs/2509.08913) in *Proc. of IEEE Global Communications Conference (GLOBECOM)*, Taipei, Taiwan, Dec. 2025.

**Sin-Yu Huang** and Vincent W.S. Wong


- In this work, we propose a generalized user-oriented image semantic coding framework that leverages large vision-language models to capture and transmit task-relevant semantics conditioned on user intent. The system aligns image and text embeddings through CLIP-based representation learning and optimizes a user-intent relevance loss using a multimodal assistant model to preserve semantic consistency during transmission. Experimental results demonstrate that the proposed method achieves superior query alignment and semantic fidelity compared with traditional and existing quary-aware semantic coding schemes.

<!-- <strong><span class='show_paper_citations' data='epYiVosAAAAJ:u5HHmVD_uO8C'></span></strong>  -->
</div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICC 2025</div><img src='images/ICCpaper2025.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Leveraging MoE-based Large Language Model for Zero-Shot Multi-Task Semantic Communication](https://ieeexplore.ieee.org/document/11161303) in *Proc. of IEEE International Conference on Communications (ICC)*, Montreal, Canada, Jun. 2025.

**Sin-Yu Huang**, Renjie Liao, and Vincent W.S. Wong


- In this work, we propose a semantic communication system that employs a Mixture-of-Experts (MoE)-based large language model to support zero-shot multi-task transmission. The transmitter encodes source data into semantic representations conditioned on the receiver’s task prompt, while the MoE architecture selectively activates expert modules for efficient adaptation. Experiments show that the proposed system outperforms standard dense models in zero-shot multi-task semantic communication scenarios.

<!-- <strong><span class='show_paper_citations' data='epYiVosAAAAJ:u5HHmVD_uO8C'></span></strong>  -->
</div>
</div>

- **Sin-Yu Huang**, Jia-You Lin, Chih-Yu Wang and Ren-Hung Hwang, "[MSE Minimization for RIS-Assisted Wireless Networks with Phase Error and Phase-Dependent Amplitude Response](https://ieeexplore.ieee.org/abstract/document/10683024)", in *Proc. of IEEE Vehicular Technology Conference (VTC2024-Spring)*, Singapore, Jun. 2024.

- Wei-Yu Chen, Chih-Yu Wang, Ren-Hung Hwang, Wen-Tsuen Chen and **Sin-Yu Huang**, "[Impact of Hardware Impairment on the Joint Reconfigurable Intelligent Surface and Robust Transceiver Design in MU-MIMO System](https://ieeexplore.ieee.org/abstract/document/10149520)", in *IEEE Transactions on Mobile Computing*, vol. 23, no. 5, pp. 3993-4008, May 2024

- **Sin-Yu Huang**, Kuang-Hao Liu, "[Average AoI Minimization for Energy Harvesting Relay-Aided Status Update Network Using Deep Reinforcement Learning](https://ieeexplore.ieee.org/abstract/document/10130605)", in *IEEE Wireless Communications Letters*, vol. 12, no. 8, pp. 1464-1468, Aug. 2023.

- **Sin-Yu Huang**, Kuang-Hao Liu, "[Relay selection for energy harvesting relays with energy prioritization and inter-relay charging](https://ieeexplore.ieee.org/abstract/document/9805690)", in *IEEE Transactions on Vehicular Technology*, vol. 71, no. 10, pp. 10646-10655, Oct. 2022. [Source code](https://github.com/Sinyu104/EPRS-Relay-Selection-Scheme)

# 📚 Academic Services
- Journal reviewer:
  - *IEEE Journal on Selected Areas in Communications (JSAC)*  
  Special Issue: Large AI Models for Future Wireless Communication Systems
  - *IEEE Communications Magazine (COMMAG)*  
  Special Issue: Large AI Models for Communications
  - *IEEE Network Magazine*  
  Special Issue: Large AI Models for the Internet of Everything
- Conference TPC member:
  - *IEEE International Conference on Communications (ICC) 2026*  
  SAC: Machine Learning for Communication and Networking


# 🏛️ Educations
- *2023.09 - Now*, Ph.D., Electrical and Computer Engineering, University of British Columbia, Vancouver, Canada.
- *2021.09 - 2022.06*, M.S., Electrical Computer and Communication Engineering, Institute of Computer and Communication Engineering, National Cheng Kung University, Taiwan.
- *2017.09 - 2021.06*, B.S., Electrical Engineering, National Cheng Kung University, Taiwan. 

# 💻 Work Experiences
- Academic:
  - *2023.09 - Now*, Graduate Research Assistant, University of British Columbia, Vancouver, BC, Canada
  - *2025.01 - 2025.04*; *2025.09 - 2025.12*, Graduate Teaching Assistant for Computer Network ELEC 331, University of British Columbia, Vancouver, BC, Canada
  - *2022.09 - 2023.08*, Full-time Research Assistant, Research Center for Information Technology Innovation, Academia Sinica, Taipei, Taiwan
  - *2020.09 - 2021.01*, Teaching Assistant for Discrete Mathematics, Electrical Engineering, National Cheng Kung University, Tainan, Taiwan
- Industry:
  - *2021.07 - 2021.08*, WiFi Embedded Software Engineer Summer Intern, [MediaTek](https://www.mediatek.com), Hsinchu, Taiwan.

# 🎖 Honors and Awards
- *2023.09 - 2026.08*, President's Academic Excellence Initiative PhD, University of British Columbia. 
- *2023.09 - 2026.08*, International Tuition Award, University of British Columbia. 
- *2023.09 - 2026.08* Faculty of Applied Science Graduate Award, University of British Columbia. 
- *2017.09* Outstanding student for academic achievement, National Cheng Kung University. 

# 💬 Activities
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICC 2025</div><img src='images/Icc2025.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[Presenter at ICC 2025](https://icc2025.ieee-icc.org/)
8–12 June, Montreal, Canada


- I presented my work “Leveraging MoE-based Large Language Model for Zero-Shot Multi-Task Semantic Communication” at IEEE ICC 2025. The paper introduces a Mixture-of-Experts (MoE) LLM framework for zero-shot, task-oriented semantic communication across multiple tasks without fine-tuning. It shows how foundation models can enable flexible and efficient communication in dynamic wireless environments. I also enjoyed connecting with researchers in AI-driven wireless systems. It was a truly inspiring experience.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">INFOCOM 2024</div><img src='images/Infocom.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Student Voluteer in INFOCOM 2024](https://infocom2024.ieee-infocom.org)
20–23 May, Vancouver, Canada


- During INFOCOM 2024, I had the opportunity to serve as a student volunteer. I facilitated virtual presentations via Zoom, ensuring smooth transitions between speakers and resolving any technical issues. Additionally, I assisted with in-person duties such as working at the registration desk, where I greeted attendees and provided information, and checking badges during key events to maintain security and order. This experience enhanced my organizational and communication skills while giving me valuable insight into event coordination in a large-scale academic conference.

</div>
</div>

<center>Last update: November 14, 2025 </center> 