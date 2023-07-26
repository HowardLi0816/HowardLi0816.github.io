---
permalink: /research/research-3
title: "Visual SLAM system"
excerpt: "Student Researcher (SUSTech), Professor Hao Yu<br/><img src='/images/TLCD.png'>"
collection: Reasearch
order_number: 30
---

## VSlam Loop Closure Detection Based on Transformer (05/2021-04/2022)
- Designed and implemented transformer-based feature extraction with Pytorch and designed sequence matching at the back-end of LCD.
- Trained on Places365 with knowledge distillation, achieving top-1 of 53.28% and top-5 of 84.04%, comparable to CNN-based models.
- Improved the average precision by 3.18% compared to state-of-the-art CNN-based methods on NewCollege and CityCentre datasets.
- Authored and published a paper in 2022 IEEE International Conference on Advanced Robotics and Mechatronics.
    - [2022 ICARM Paper](/files/TLCD_A_Transformer_based_Loop_Closure_Detection_for_Robotic_Visual_SLAM.pdf)
    - [2022 ICARM Slide](/files/TLCD_ARM.pdf)
    
## Light Monocular Visual Odometry through Attentive Tensor-compressed LSTM Model for Robotic VSlam (09/2020-12/2020)
- Designed a CNN+T-LSTM model with attention mechanism to estimate the 6-DoF absolute-scale pose from the optimal flow feature for the monocular visual Odometry, making it friendly to be applied on edge devices.
- Achieved 1/7 the size of DeepVO and 23x faster than Flowdometry on KITTI dataset, while deployed it to a Raspberry Pi-based robot.
- Authored and published a paper in 2021 WRC Symposium on Advanced Robotics and Automation, awarded the Best Student Paper.
    - [2021 WRC Paper](/files/ATFVO_An_Attentive_Tensor-compressed_LSTM_Model_with_Optical_Flow_Features_for_Monocular_Visual_Odometry.pdf)

