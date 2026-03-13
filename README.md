<div align="center">
  <img src="imagesPortfolio/profile.jpg" width="150" height="150" style="border-radius: 50%;">
  
  <h1>Hi, I'm Tomás Coelho 👋</h1>
  <h3>MSc Aerospace Engineering (Embedded Systems) @ ISAE-SUPAERO</h3>
  <h4>BSc Aerospace Engineering @ Instituto Superior Técnico</h4>
  
  <p>Computer Vision • Visual Localization • Feature Matching • Embedded Systems</p>

  <p>
    <a href="mailto:tomas.g.c.coelho@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
    <a href="https://www.linkedin.com/in/tom%C3%A1s-coelho-692a00227/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
    <a href="https://github.com/TomasCoelho23"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  </p>
</div>

---

## 👨‍💻 About Me

I am a Computer Vision engineer and researcher focused on **visual localization in GPS-denied environments**, with a strong interest in feature matching, aerial perception, synthetic data, and robust vision systems under domain shift. 

I combine an aerospace engineering background with hands-on experience building end-to-end ML systems, from research experiments to deployable benchmarking pipelines.

* 🎓 **ISAE-SUPAERO (MSc, Embedded Systems)** — CGPA: **3.86/4.0** *(Expected Dec 2026)*
* 🎓 **Instituto Superior Técnico (BSc, Aerospace Engineering)** — Final Grade: **15/20** *(Jun 2024)*
* 📍 **Location:** Toulouse, France
* 💼 **Open to:** Research collaborations, internships, and applied CV/ML opportunities

---

## 🎯 Current Focus
* Visual localization for **GPS-denied drone navigation**
* **Drone-to-satellite matching** and aerial georegistration
* Learned local feature matching with **ELoFTR / LoFTR-style pipelines**
* Synthetic data generation with **ControlNet**
* Segmentation pipelines for agricultural and remote perception tasks

---

## 🚀 Featured Work

### Visual Localization for GPS-Denied Drone Navigation
*Worked on feature-matching systems and benchmarking for a Series A startup focused on localization in GPS-denied environments.*

* Built a real-flight benchmark for **drone-to-satellite visual localization**.
* Evaluated multiple matchers including **POLARIS, ELoFTR, RoMa, and XFeat**.
* Used downstream metrics such as **SR@75, recall, localization error, latency, and FPS**.
* Adapted **EfficientLoFTR** for aerial localization with homography-based supervision and temporal satellite pair mining.
* **Result:** Achieved internal **SOTA** with 65.0% SR@75 at ~35 FPS, outperforming ELoFTR by 39% and XFeat by 142% on SR@75 at comparable throughput, and running 12x faster than RoMa.

### Synthetic Data for Hierarchical Panoptic Segmentation
*ISAE-SUPAERO* | [![GitHub](https://img.shields.io/badge/Code-GitHub-blue?style=flat-square&logo=github)](https://github.com/TomasCoelho23/hierarchical-segmentation-with-synthetic-data)

* Benchmarked a 3-stage **Mask2Former** pipeline on **PhenoBench**.
* Built a **ControlNet-based augmentation workflow** for generating synthetic image-mask pairs.
* Integrated synthetic samples into the training pipeline for low-label agricultural perception.
* **Result:** Reduced validation loss from 9.91 to 9.85 and improved PQ+ from 82.95 to ~83.0.

### ControlNet + Semantic Segmentation Pipeline
*Designed a unified experimentation pipeline for comparing synthetic-data strategies on PhenoBench.*

* Built a pipeline with 2 augmentation modes: **ControlNet-based generative augmentation** and **Classic copy-paste augmentation**.
* Automated the full workflow: mask/caption generation, ControlNet training, dataset preparation, DeepLabv3+ training, and validation/testing.
* Ran scaling studies across 25 synthetic-data configurations from 110 to 2000 added samples.
* **Result (on a 266-image training set):** Baseline 0.8349 mIoU. Best copy-paste: 0.8686 mIoU. Best ControlNet: 0.8644 mIoU. Hardest class IoU improved from 0.5837 to 0.6675.

### ATLAS UAV — Air Cargo Challenge 2024
* Led the **Tail & Fuselage Structures** department for a 12-person team.
* Coordinated structural design, simulation, and manufacturing.
* Balanced weight, manufacturability, and compliance with competition rules in a multidisciplinary environment.

---

## 💻 Technical Skills

**Languages** <br>
![Python](https://img.shields.io/badge/python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=flat-square&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/sql-%23336791.svg?style=flat-square&logo=sqlite&logoColor=white)
![MATLAB](https://img.shields.io/badge/matlab-%230076A8.svg?style=flat-square&logo=mathworks&logoColor=white)

**Computer Vision & ML** <br>
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=flat-square&logo=PyTorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=flat-square&logo=opencv&logoColor=white)
`Kornia` `PyTorch Lightning` `DeepLabv3+` `Mask2Former` `ControlNet` `Image Segmentation` `Local Feature Matching` `Homography Estimation` `RANSAC`

**Tools & Infrastructure** <br>
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![ROS](https://img.shields.io/badge/ros-%230A0FF9.svg?style=flat-square&logo=ros&logoColor=white)
`Weights & Biases` `SolidWorks`

**Domains** <br>
`Visual Localization` `Drone-to-Satellite Matching` `GPS-Denied Navigation` `Aerial Image Registration` `Synthetic Data Generation` `Domain Shift Perception`

---

## 📜 Certifications

* 🏅 [Machine Learning Specialization](https://www.coursera.org/account/accomplishments/specialization/2SNHSVNZKBVZ)
* 🏅 [Advanced Learning Algorithms](https://www.coursera.org/account/accomplishments/verify/JW4185DGSYPO)
* 🏅 [Supervised ML: Regression & Classification](https://www.coursera.org/account/accomplishments/verify/YQO9TBAD5WPC)
* 🏅 [Unsupervised Learning, Recommenders & Reinforcement Learning](https://www.coursera.org/account/accomplishments/verify/MGC6NJR0SNLN)

---

## 🔭 Interests

* Visual localization and navigation
* Feature matching for real-world robotics
* Computer vision for aerospace and remote sensing
* Robust perception in low-data environments
* Research-to-engineering workflows in ML systems
