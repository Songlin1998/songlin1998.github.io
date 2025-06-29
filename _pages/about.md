---
permalink: /
title: "Songlin Yang"
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

I am an incoming PhD student. Currently, I work as a research associate at [MMLab@NTU](https://www.mmlab-ntu.com/index.html), S-Lab, Nanyang Technological University in Singapore, under the supervision of [Xingang Pan](https://xingangpan.github.io/index.html). I achieved my M.S. from [Institute of Automation, Chinese Academy of Sciences](http://www.ia.cas.cn/) and B.E. from [Nanjing University of Aeronautics and Astronautics](http://nuaa.edu.cn/) with Honors Distinction. I am the recipient of [BSIG Outstanding Thesis Award (Graduate)](http://www.bsig.org.cn/detail/2574), Jiangsu Outstanding Thesis Award (Bachelor), and China National Scholarship (Bachelor & Graduate). I am fortunate to have internships at several leading research institutions, including MicroSoft Research Asia and SenseTime Research. My research experience focuses on **controllable** multimodal content generation, with a particular emphasis on 3D-aware generative modeling.

<font color="blue">My previous research mainly focused on these aspects: </font>
  - **Multimodal AIGC**: Talking-Head Video, Text-to-Image/3D Generation, and Image-Driven Face Reenactment
  - **Trustworthy AIGC**: Machine Unlearning, Adversarial Attack, and Backdoor Attack  
  - **Robust Face Recognition System**: De-Identification, Anti-Spoofing, and Deepfake Detection
  

# 🔈**JOIN US!**

I embrace Richard Feynman's dictum, 'What I can not create, I do not understand.' This aligns with my technical roadmap of using generative AI to perceive, understand, and manipulate our world. I will continue conducting research at the intersection of computer vision and graphics, especially in **video** and **3D** generation, to create the 3D world from 2D pixels and realize creative human-centered AIGC.

<font color="red">Do not hesitate to drop me an email for any possible collaboration if you are interested in these directions:</font>
  - Generative Models: 2D (Images/Videos), 3D, and 4D Content
  - Creator-Machine Interaction: Interfaces, Personalization, and Feedback Adaptation
  - AIGC Safety: Robustness, Privacy, and Traceability 

# 🔥 News
- 2025/06: One paper is accepted by [ICCV 2025](https://iccv.thecvf.com/Conferences/2025).
- 2025/05: One paper is accepted by [ICML 2025](https://icml.cc/).
- 2025/02: We are organizing [the 6th Workshop on AI for Creative Visual Content Generation Editing and Understanding](https://cveu.github.io/) at CVPR 2025.
- 2024/07: <font color="red">I am awarded the 2024 Outstanding Thesis Award by </font> [BSIG](http://www.bsig.org.cn/detail/2574)!
- 2024/07: One paper is accepted by ACM TOMM.
- 2024/06: I am invited to give a talk about my Master's thesis ([slides](https://github.com/Songlin1998/songlin1998.github.io/raw/main/docs/Songlin%20Yang-Talk-20240611.pdf)).
- 2024/05: I have successfully defended my Master's thesis.  
- 2024/03: One paper is accepted by [ICME 2024](https://2024.ieeeicme.org/).  
- 2024/01: I am invited by AI TIME to give a [talk](https://www.bilibili.com/video/BV1xW4y1c7Sc/?spm_id_from=333.788&vd_source=619d95e534c3977d77a6e3f15a4d5d7e) (in Chinese) about [PlaneDict (AAAI 2024)](https://arxiv.org/pdf/2312.10422.pdf).
- 2023/12: One paper is accepted by [AAAI 2024](https://aaai.org/aaai-conference/).
- 2023/10: I am granted by National Scholarship (Graduate)!
- 2023/07: One paper is accepted by [MM 2023](https://www.acmmm2023.org/).

# 🧑‍🎓 Education

- **M.S. in Pattern Recognition and Intelligent Systems, [NLPR Department](http://cripac.ia.ac.cn/CN/model/index.htm), [CASIA Institute](http://www.ia.cas.cn/)**   
  Supervisor: [Wei Wang](https://people.ucas.edu.cn/~wwong) (Co-Supervised by [Jing Dong](https://people.ucas.edu.cn/~dongjing) and [Bo Peng](http://cripac.ia.ac.cn/en/EN/column/item139.shtml))  
  Thesis: Dynamic Facial Editing based on Neural Radiance Fields ([BSIG Outstanding Thesis Award](http://www.bsig.org.cn/detail/2574))  
  GPA: 3.82/4.0 (National Scholarship)  

- **B.E. in Automation Engineering, Nanjing University of Aeronautics and Astronautics**  
  Thesis: Face De-Identification based on Generative Adversarial Networks (Jiangsu Outstanding Thesis Award)  
  GPA: 4.4/5.0 (Rank: 1/204, Honors Distinction)  

# 💻 Work Experience

- **Research Associate, MMLab@NTU, S-Lab, Nanyang Technological University**  
  Supervised by [Xingang Pan](https://xingangpan.github.io/index.html).  

- **Research Intern, Content Generation Group, SenseTime Research**  
  Supervised by [Xiangyu Fan](https://events.keep.edu.hk/cuhk/engg5700/2017/team/fan-xiangyu/) and [Lei Yang](https://scholar.google.com/citations?hl=zh-CN&user=jZH2IPYAAAAJ).
  
 - **Research Intern, Machine Learning Group, MicroSoft Research Asia**  
  Supervised by [Xu Tan](https://scholar.google.com/citations?user=tob-U1oAAAAJ&hl=zh-CN&oi=ao) and [Jun Ling](https://scholar.google.com/citations?hl=zh-CN&user=XsfjhQ0AAAAJ).
  
 - **Research Intern, Identity Verification Group, SenseTime Research**   
  Supervised by Chenye Xu and [Yichao Wu](https://scholar.google.com/citations?hl=zh-CN&user=20Its9kAAAAJ).

# 📝 Selected Publications - Controllable Multimodal Generation

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/publications/morphing.gif' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
  
  **Textured 3D Regenerative Morphing with 3D Diffusion Prior**
  
  **Songlin Yang**, [Yushi Lan](https://nirvanalan.github.io/), [Honghua Chen](https://chenhonghua.github.io/clay.github.io/), [Xingang Pan](https://xingangpan.github.io/index.html)  
    
  [Paper](https://arxiv.org/pdf/2502.14316) [Project](https://songlin1998.github.io/Textured-3D-Morphing/)
  
  </div>
  </div>

  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/publications/cvpr24.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">

  **Beyond Inserting: Learning Subject Embedding for Semantic-Fidelity Personalized Diffusion Generation**
  
  [Yang Li](https://github.com/yangli-lab)\*, **Songlin Yang**\*, [Wei Wang](http://cripac.ia.ac.cn/people/wwang/index.html), [Jing Dong](http://cripac.ia.ac.cn/people/jdong/)  
  (\* Equal Contribution)  
  
  [Paper](https://arxiv.org/pdf/2402.00631.pdf) [Project](https://com-vis.github.io/SeFi-IDE/)  
  
  </div>
  </div>

  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/publications/AAAI2024.gif' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
  
  **Learning Dense Correspondence for NeRF-Based Face Reenactment**
  
  **Songlin Yang**, [Wei Wang](http://cripac.ia.ac.cn/people/wwang/index.html), [Yushi Lan](https://nirvanalan.github.io/), [Xiangyu Fan](https://events.keep.edu.hk/cuhk/engg5700/2017/team/fan-xiangyu/), [Bo Peng](http://cripac.ia.ac.cn/en/EN/column/item139.shtml), [Lei Yang](https://scholar.google.com/citations?hl=zh-CN&user=jZH2IPYAAAAJ), [Jing Dong](http://cripac.ia.ac.cn/people/jdong/)  
  
  [Proceedings of the AAAI Conference on Artificial Intelligence](https://aaai.org/aaai-conference/), 2024  
  [Paper](https://arxiv.org/pdf/2312.10422.pdf) [Project](https://songlin1998.github.io/planedict/) [Code](https://github.com/Songlin1998/Oneshot-Tri-plane-Face-Reenactment)  
  
  </div>
  </div>

  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2023</div><img src='images/publications/MM2023.gif' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
  
  **Context-Aware Talking-Head Video Editing**
  
  **Songlin Yang**, [Wei Wang](http://cripac.ia.ac.cn/people/wwang/index.html), [Jun Ling](https://scholar.google.com/citations?hl=zh-CN&user=XsfjhQ0AAAAJ), [Bo Peng](http://cripac.ia.ac.cn/en/EN/column/item139.shtml), [Xu Tan](https://scholar.google.com/citations?user=tob-U1oAAAAJ&hl=zh-CN&oi=ao), [Jing Dong](http://cripac.ia.ac.cn/people/jdong/)  
  
  [Proceedings of the 31st ACM International Conference on Multimedia](https://www.acmmm2023.org/), 2023  
  [Paper](https://dl.acm.org/doi/abs/10.1145/3581783.3611765) [Project](https://songlin1998.github.io/THEdit/) [Code](https://github.com/Songlin1998/Talking-Head-Video-Editing)  
  
  </div>
  </div>

  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2023</div><img src='images/publications/ICASSP.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
  
  **Designing a 3D-Aware StyleNeRF Encoder for Face Editing**
  
  **Songlin Yang**, [Wei Wang](http://cripac.ia.ac.cn/people/wwang/index.html), [Bo Peng](http://cripac.ia.ac.cn/en/EN/column/item139.shtml), [Jing Dong](http://cripac.ia.ac.cn/people/jdong/) 
  
  [IEEE International Conference on Acoustics, Speech, and Signal Processing](https://2023.ieeeicassp.org/), 2023 
  
  [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10094932) [Code](https://github.com/Songlin1998/StyleNeRF-Encoder-and-Editor)    
  
  </div>
  </div>

# 📖 Selected Publications - Trustworthy AIGC and AI Safety

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/publications/icml2025.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
  
  **Adaptive Median Smoothing: Adversarial Defense for Unlearned Text-to-Image Diffusion Models at Inference Time**

  [Xiaoxuan Han](https://github.com/hxxdtd), **Songlin Yang**, [Wei Wang](http://cripac.ia.ac.cn/people/wwang/index.html), [Yang Li](https://github.com/yangli-lab), [Jing Dong](http://cripac.ia.ac.cn/people/jdong/)  
[Forty-Second International Conference on Machine Learning](https://icml.cc/), 2025

  Paper Project  
  
  </div>
  </div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/publications/mm2024.jpg' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
  
  **Probing Unlearned Diffusion Models: A Transferable Adversarial Attack Perspective**
  
  [Xiaoxuan Han](https://github.com/hxxdtd), **Songlin Yang**, [Wei Wang](http://cripac.ia.ac.cn/people/wwang/index.html), [Yang Li](https://github.com/yangli-lab), [Jing Dong](http://cripac.ia.ac.cn/people/jdong/)  

  [Paper](https://arxiv.org/pdf/2404.19382) [Project](https://github.com/hxxdtd/PUND) [Survey](https://github.com/hxxdtd/Awesome-Diffusion-Model-Unlearning) [Code](https://github.com/hxxdtd/PUND)  
  
  </div>
  </div>

  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM TOMM 2024</div><img src='images/publications/tomm24.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
  
  **Exploiting Backdoors of Face Synthesis Detection with Natural Triggers**
  
  [Xiaoxuan Han](https://github.com/hxxdtd), **Songlin Yang**, [Wei Wang](http://cripac.ia.ac.cn/people/wwang/index.html), [Ziwen He](https://scholar.google.com/citations?user=PjkDK9cAAAAJ&hl=zh-CN&oi=sra), [Jing Dong](http://cripac.ia.ac.cn/people/jdong/)  
  ACM Transactions on Multimedia Computing Communications and Applications, 2024  

  [Paper](https://arxiv.org/pdf/2401.00414.pdf)  
  
  </div>
  </div>

  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2024</div><img src='images/publications/icme24.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
  
  **Counterfactual Explanations for Face Forgery Detection via Adversarial Removal of Artifacts**  
  
  [Yang Li](https://github.com/yangli-lab)\*, **Songlin Yang**\*, [Wei Wang](http://cripac.ia.ac.cn/people/wwang/index.html), [Ziwen He](https://scholar.google.com/citations?user=PjkDK9cAAAAJ&hl=zh-CN&oi=sra), [Bo Peng](http://cripac.ia.ac.cn/en/EN/column/item139.shtml), [Jing Dong](http://cripac.ia.ac.cn/people/jdong/)  
   (\* Equal Contribution)  

   [IEEE International Conference on Multimedia and Expo](https://2024.ieeeicme.org/), 2024  
   **Oral Presentation**  
   [Paper](https://arxiv.org/pdf/2404.08341.pdf) [Code](https://github.com/yangli-lab/Artifact-Eraser)  
  
  </div>
  </div>

  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR-W 2023</div><img src='images/publications/CVPRW23.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
  
  **Exposing Fine-Grained Adversarial Vulnerability of Face Anti-Spoofing Models**
  
  **Songlin Yang**, [Wei Wang](http://cripac.ia.ac.cn/people/wwang/index.html), Chenye Xu, [Ziwen He](https://scholar.google.com/citations?user=PjkDK9cAAAAJ&hl=zh-CN&oi=sra), [Bo Peng](http://cripac.ia.ac.cn/en/EN/column/item139.shtml), [Jing Dong](http://cripac.ia.ac.cn/people/jdong/) 
  
  [IEEE Conference on Computer Vision and Pattern Recognition](https://cvpr2023.thecvf.com/) [Workshop](https://www.vislab.ucr.edu/Biometrics2023/index.php), 2023  
  **Long Oral Presentation**  
  [Paper](https://arxiv.org/pdf/2205.14851.pdf) 
  
  </div>
  </div>

# 🎖️ Awards

- [BSIG Outstanding Thesis Award](http://www.bsig.org.cn/detail/2574). 2024
- National Scholarship (Graduate). 2023
- National Scholarship (Bachelor). 2018
- Provincial Outstanding Graduate. 2021
- Provincial Outstanding Bachelor Thesis Award. 2021
- President Scholarship of Nanjing University of Aeronautics and Astronautics. 2020
- Outstanding Graduate of Nanjing University of Aeronautics and Astronautics. 2021
- Outstanding Student of University of Chinese Academy of Sciences. 2022, 2023, 2024
- Scholarship of Aviation Industry Corporation of China. 2019, 2020
- First Class Scholarship for Academic Excellence. 2017, 2018, 2019, 2020
- Outstanding Reviewer for [CVPR Workshop](https://cveu.github.io/), 2025

# 🕴️ Professional Services
- Organizer for [CVEU Workshop](https://cveu.github.io/) at CVPR 2025.
- Publicity Chair for [IEEE Beijing Biometrics Council Chapter](https://r10.ieee.org/beijing-bio/) (2021-2024).
- IEEE Student Member (2021-Now).
- ACM Member (2024-Now).
- Conference Reviewer
  - AAAI (2023, 2024, 2025)
  - ICCV (2025)
  - SIGGRAPH (2025)
  - CVPR (2022, 2023, 2024, 2025)
  - MM (2024)
  - ECCV (2022, 2024)
- Journal Reviewer
  - IEEE Transactions on Multimedia (TMM)
  - IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)
  - ACM Transactions on Multimedia Computing, Communications, and Applications (TOMM)
  - Pattern Recognition (PR)


<script type='text/javascript' id='mapmyvisitors' src='https://mapmyvisitors.com/map.js?cl=ffffff&w=300&t=tt&d=7vdDMk61HlQEKQd8AYn5-S0oCuWHWu5PXdYVUfgjX4I&cmn=ff5353'></script>

