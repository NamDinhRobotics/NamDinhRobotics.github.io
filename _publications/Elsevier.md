---
title: "Fusion Consistency for Industrial Robot Navigation: An Integrated SLAM Framework with Multiple 2D LiDAR-Visual-Inertial Sensors"
collection: publications
category: articles
permalink: /publication/2024-12-01-slam-fusion-consistency
excerpt: 'This paper introduces a LiDAR-centric binary pose fusion technique for industrial Autonomous Mobile Robots (AMRs), ensuring robust SLAM integration.'
date: 2024-12-01
venue: 'Computers and Electrical Engineering (Volume 120, Part A, December 2024)'
paperurl: 'https://doi.org/10.1016/j.compeleceng.2024.109607'
citation: 'Dinh Van Nam, (2024). "Fusion Consistency for Industrial Robot Navigation: An Integrated SLAM Framework with Multiple 2D LiDAR-Visual-Inertial Sensors." <i>Computers and Electrical Engineering</i>, 120(A), pp. 109607, DOI: 10.1016/j.compeleceng.2024.109607.' 
publisher: 'Elsevier'
date_of_publication: 'December 2024'
pages: '109607'
---

### Abstract
Autonomous Mobile Robot (AMR) navigation heavily relies on **Simultaneous Localization and Mapping (SLAM)** as a cornerstone technology. While recent SLAM approaches have achieved high performance, ensuring **robustness and adaptability** to diverse real-world conditions remains a challenge. 

Many existing methods use **recursive Bayesian filtering** to integrate **LiDAR and cameras**, employing either **loosely or tightly coupled methods**. However:
- **Loosely coupled techniques** are simple but lack **precision**.
- **Tightly coupled methods** struggle with **2D LiDAR-visual coupling** and are vulnerable to **sensor degradation**.

In response to these challenges, this work introduces a **pioneering SLAM framework** centered around a **LiDAR-centric binary pose fusion technique**, specifically designed for **industrial AMRs**. The framework integrates **multiple 2D LiDARs, cameras, and an Inertial Measurement Unit (IMU)**, adopting a **hybrid coupled technique** that:
1. **LiDAR-centric front-end processing** combined with **visual-inertial odometry**.
2. **Back-end factor graph optimization** with **LiDAR-camera loop closure detection**.

To validate the efficacy of our approach, we implemented the **SLAM framework in real-world industrial environments**, showcasing its efficiency with **multiple 2D LiDAR-visual-inertial sensors**. The results demonstrate:
- **Exceptional accuracy** exceeding conventional LiDAR and visual SLAM systems.
- A **low-cost maintenance sensor system**, significantly reducing industrial AMR deployment costs compared to existing approaches.

This research contributes a **comprehensive and innovative solution** to **SLAM integration in AGV navigation**, emphasizing the **importance of fusion consistency** and **practical applicability** in **industrial settings**.
