# Hi, I'm Tomás Coelho

**MSc Aerospace Engineering (Embedded Systems) @ ISAE-SUPAERO**  
**BSc Aerospace Engineering @ Instituto Superior Técnico**

Computer Vision · Visual Localization · Feature Matching · Embedded Systems

---

## About Me

I am a Computer Vision engineer and researcher focused on **visual localization in GPS-denied environments**, with a strong interest in **feature matching, aerial perception, synthetic data, and robust vision systems under domain shift**.

My recent work has centered on:
- **Drone-to-satellite visual localization**
- **Learned feature matchers for GPS-denied navigation**
- **Synthetic data generation for segmentation**
- **Perception pipelines for data-scarce environments**

I combine an aerospace engineering background with hands-on experience building end-to-end ML systems, from research experiments to deployable benchmarking pipelines.

- **ISAE-SUPAERO (MSc, Embedded Systems)** — CGPA: **3.86/4.0** *(Expected Dec 2026)*
- **Instituto Superior Técnico (BSc, Aerospace Engineering)** — Final Grade: **15/20** *(Jun 2024)*
- **Location:** Toulouse, France
- **Open to:** Research collaborations, internships, and applied CV/ML opportunities

---

## Current Focus

- Visual localization for **GPS-denied drone navigation**
- **Drone-to-satellite matching** and aerial georegistration
- Learned local feature matching with **ELoFTR / LoFTR-style pipelines**
- Synthetic data generation with **ControlNet**
- Segmentation pipelines for agricultural and remote perception tasks

---

## Featured Work

### Visual Localization for GPS-Denied Drone Navigation
Worked on feature-matching systems and benchmarking for a **Series A startup** focused on localization in GPS-denied environments.

Key contributions:
- Built a real-flight benchmark for **drone-to-satellite visual localization**
- Evaluated multiple matchers including **POLARIS, ELoFTR, RoMa, and XFeat**
- Used downstream metrics such as **SR@75, recall, localization error, latency, and FPS**
- Adapted **EfficientLoFTR** for aerial localization with homography-based supervision and temporal satellite pair mining

Selected result:
- Achieved internal **SOTA** with **65.0% SR@75 at ~35 FPS**
- Outperformed **ELoFTR by 39%** on SR@75 at similar speed
- Outperformed **XFeat by 142%** on SR@75 at comparable throughput
- Ran **12x faster than RoMa** at similar SR@75

---

### Synthetic Data for Hierarchical Panoptic Segmentation
**ISAE-SUPAERO**  
[GitHub](https://github.com/TomasCoelho23/hierarchical-segmentation-with-synthetic-data)

Worked on synthetic data generation for **hierarchical panoptic segmentation** on **PhenoBench**.

Key contributions:
- Benchmarked a 3-stage **Mask2Former** pipeline on PhenoBench
- Built a **ControlNet-based augmentation workflow** for generating synthetic image-mask pairs
- Integrated synthetic samples into the training pipeline for low-label agricultural perception

Selected result:
- Reduced validation loss from **9.91** to **9.85**
- Improved **PQ+** from **82.95** to approximately **83.0**

---

### ControlNet + Semantic Segmentation Pipeline
Designed a unified experimentation pipeline for comparing synthetic-data strategies on **PhenoBench**.

Key contributions:
- Built a pipeline with **2 augmentation modes**:
  - **ControlNet-based generative augmentation**
  - **Classic copy-paste augmentation**
- Automated the full workflow:
  - mask generation
  - caption generation
  - ControlNet training
  - dataset preparation
  - DeepLabv3+ training
  - validation/testing
- Ran scaling studies across **25 synthetic-data configurations** from **110 to 2000** added samples

Selected results on a reduced **266-image** training set:
- Reduced-data baseline: **0.8349 mIoU**
- Best **copy-paste** result: **0.8686 mIoU**
- Best **ControlNet** result: **0.8644 mIoU**
- Hardest class IoU improved from **0.5837** to **0.6675** with copy-paste

---

### ATLAS UAV — Air Cargo Challenge 2024
Led the **Tail & Fuselage Structures** department for a **12-person team**.

Key contributions:
- Coordinated structural design, simulation, and manufacturing
- Balanced weight, manufacturability, and compliance with competition rules
- Worked in a multidisciplinary aerospace engineering environment with tight delivery constraints

---

## Technical Skills

### Languages
- Python
- C++
- SQL
- MATLAB

### Computer Vision / ML
- PyTorch
- OpenCV
- Kornia
- PyTorch Lightning
- DeepLabv3+
- Mask2Former
- ControlNet
- Image segmentation
- Local feature matching
- Homography estimation
- RANSAC-based geometric verification

### Domains
- Visual localization
- Drone-to-satellite matching
- GPS-denied navigation
- Aerial image registration
- Synthetic data generation
- Perception under domain shift

### Tools
- Git
- Docker
- Linux
- Weights & Biases
- ROS
- SolidWorks

---

## Certifications

- [Machine Learning Specialization](https://www.coursera.org/account/accomplishments/specialization/2SNHSVNZKBVZ)
- [Advanced Learning Algorithms](https://www.coursera.org/account/accomplishments/verify/JW4185DGSYPO)
- [Supervised ML: Regression & Classification](https://www.coursera.org/account/accomplishments/verify/YQO9TBAD5WPC)
- [Unsupervised Learning, Recommenders & Reinforcement Learning](https://www.coursera.org/account/accomplishments/verify/MGC6NJR0SNLN)

---

## Contact

- **GitHub:** [github.com/TomasCoelho23](https://github.com/TomasCoelho23)
- **LinkedIn:** [linkedin.com/in/tomás-coelho-692a00227](https://www.linkedin.com/in/tom%C3%A1s-coelho-692a00227/)
- **Email:** [tomas.g.c.coelho@gmail.com](mailto:tomas.g.c.coelho@gmail.com)

---

## Interests

I am particularly interested in:
- Visual localization and navigation
- Feature matching for real-world robotics
- Computer vision for aerospace and remote sensing
- Robust perception in low-data environments
- Research-to-engineering workflows in ML systems

