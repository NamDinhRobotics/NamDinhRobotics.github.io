---
title: "Learning Observation Model for Factor Graph-Based State Estimation Using Intrinsic Sensors"
collection: publications
category: articles
permalink: /publication/2023-07-28-learning-observation-model
excerpt: 'This paper presents a robust state estimation system for holonomic mobile robots using intrinsic sensors and adaptive factor graph optimization.'
date: 2023-07-28
venue: 'IEEE Transactions on Automation Science and Engineering (Volume: 20, Issue: 3, July 2023)'
paperurl: 'https://doi.org/10.1109/TASE.2022.3193411'
citation: 'Dinh Van Nam, (2023). "Learning Observation Model for Factor Graph-Based State Estimation Using Intrinsic Sensors." <i>IEEE Transactions on Automation Science and Engineering</i>, 20(3), pp. 2049-2062, DOI: 10.1109/TASE.2022.3193411.' 
issn: 'ISSN Information: IEEE'
publisher: 'IEEE'
date_of_publication: '28 July 2022'
pages: '2049 - 2062'
---

### Abstract
The navigation system of autonomous mobile robots has appeared challenging when using **exteroceptive sensors** such as **cameras, LiDARs, and radars** in **textureless and structureless environments**. This paper presents a **robust state estimation system** for **holonomic mobile robots** using **intrinsic sensors**, leveraging **adaptive factor graph optimization** to handle **degradation scenarios**.

In particular, **neural networks** are employed to learn the **observation and noise model** using only **IMU sensor and wheel encoder data**. Investigating the **learning model** for the **holonomic mobile robot** is discussed with various **neural network architectures**. We explore how **lightweight neural networks** provide better efficiency and lower computational cost compared to **deep learning models** while relying solely on **inertial-wheel encoder sensors**.

To validate our approach, we employ an **industrial holonomic robot platform** equipped with **multiple LiDARs, cameras, IMU, and wheel encoders** to conduct real-world experiments. Ground truth data is collected **without using a bulky motion capture system**. The collected datasets are used to train the **neural networks**, and our solution demonstrates **better accuracy and real-time performance** than conventional methods.

### Note to Practitioners
Autonomous mobile robots must operate in **challenging environments** where **extrinsic sensors** such as **cameras, LiDARs, and radars** are unreliable. In such cases, the navigation system must depend on **intrinsic sensors** like **IMU sensors and wheel encoders**.

Existing methods primarily rely on **recursive Bayesian filtering techniques**, which **do not adapt** to varying conditions. Meanwhile, **deep learning solutions**, such as **LSTMs or CNNs**, require extensive computational resources. This work presents a **state estimation subsystem** for **holonomic mobile robots**, integrating **intrinsic sensors** with **adaptive factor graph optimization**.

Key contributions:
- **Efficiently incorporating factor graphs** with **learning-based observation models** using **IMU and wheel encoder factors**.
- **Leveraging neural networks** to train observation models based on **intrinsic sensor data**.
- **Demonstrating that lightweight neural networks** can outperform deep learning techniques in **state estimation accuracy and computational efficiency**.
- **Embedding the trained neural network** into a **factor graph** for **real-time smoothing state estimation**.

The proposed system delivers **high-accuracy real-time state estimation**, making it well-suited for **autonomous navigation** in environments where extrinsic sensors are unreliable.
