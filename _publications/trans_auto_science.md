---
title: "Learning Type-2 Fuzzy Logic for Factor Graph-Based Robust Pose Estimation with Multi-Sensor Fusion"
collection: publications
category: articles
permalink: /publication/2024-02-17-learning-type2-fuzzy-logic
excerpt: 'This paper presents a novel approach using type-2 fuzzy logic in factor graph optimization for robust multi-sensor fusion-based pose estimation.'
date: 2024-02-17
venue: 'International Conference on Autonomous Systems'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10032628'
citation: 'Dinh Van Nam, (2024). "Learning Type-2 Fuzzy Logic for Factor Graph-Based Robust Pose Estimation with Multi-Sensor Fusion." <i>International Conference on Autonomous Systems</i>. 1(1).' 
---

### Abstract
Although a wide variety of high-performance state estimation techniques have been introduced recently, the robustness and extension to actual conditions of the estimation systems have been challenging. This paper presents a robust adaptive state estimation framework based on the **Type-2 fuzzy inference system (FIS)** and **factor graph optimization** for autonomous mobile robots. 

We use a **hybrid solution** to connect the advantages of both **tightly and loosely coupled techniques** by incorporating an **inertial sensor** with other extrinsic sensors such as **LiDARs and cameras**. To tackle **uncertain input covariance** and **sensor failure issues**, we introduce a **learnable observation model** that integrates **Type-2 FIS** with **factor graph optimization**. In particular, the **Type-2 Takagi-Sugeno FIS** is used to model uncertainty via **particle swarm optimization (PSO)** before incorporating the observation model into the **factor graph**.

The proposed design consists of four key components:
1. **Sensor odometry**
2. **Up-sampling**
3. **FIS-based learning observation model**
4. **Factor graph-based smoothing**

We evaluate our system using a **mobile robot platform** equipped with multiple **stereo cameras, an IMU, and a LiDAR sensor**. To **learn the observation model** of visual-inertial estimators, we simulate **LiDAR odometry in structured environments** without the need for bulky **motion capture systems**. Experimental results conducted in **real-world environments** demonstrate the **accuracy and robustness** of the proposed algorithm.

For further details, refer to the full paper linked above.
