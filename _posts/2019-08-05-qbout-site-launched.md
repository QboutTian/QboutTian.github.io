---
layout: post
title: "ECCV2018, Slam"
date: 2019-08-05
---
1. Absolute Orientation and Localization Estimation from an Omnidirectional Image 
2. Loosely-Coupled Semi-Direct Monocular SLAM 
3. MULTICOL-SLAM-A MODULAR REAL-TIME MULTI-CAMERA SLAM SYSTEM 
4. Gaoxiang: LDSO: Direct Sparse Odometry with Loop Closure [带有回环检测的DSO] 
5. PL-VIO: Tightly-Coupled Monocular Visual–Inertial Odometry Using Point and Line Features 
6. Online Temporal Calibration for Monocular Visual-Inertial Systems 
7. Direct Sparse Odometry with Rolling Shutter 
8. Online Photometric Calibration of Auto Exposure Video for Realtime Visual Odometry and SLAM [对于光照变化很鲁棒] 
9. A Robust and Accurate Simultaneous Localization and Mapping System for RGB-D Cameras 
10. DS-PTAM: Distributed Stereo Parallel Tracking and Mapping SLAM System 
11. ProSLAM: Graph SLAM from a Programmer's Perspective [改变数据结构，计算资源更少] 
https://gitlab.com/srrg-software/srrg_proslam/tree/master 
12. A General Framework for Flexible Multi-Cue Photometric Point Cloud Registration 
https://gitlab.com/srrg-software/srrg_mpr 
13. Direct Sparse Visual-Inertial Odometry using Dynamic Marginalization 
14. Data-Efficient Decentralized Visual SLAM 
https://github.com/uzh-rpg/dslam_open 
15. Estimating Metric Poses of Dynamic Objects Using Monocular Visual-Inertial Fusion 
16. SLAMBench2: Multi-Objective Head-to-Head Benchmarking for Visual SLAM 
https://github.com/pamela-project/slambench2 
17. Pose Estimation with Dual Quaternions and Iterative Closest Point 
18. Comparison of two different objective functions in 2D point feature SLAM 
19. PCR-Pro: 3D Sparse and Different Scale Point Clouds Registration and Robust Estimation of Information Matrix For Pose Graph SLAM 
https://sites.google.com/view/pcr-pro 
20. Low-Cost Multiple-MAV SLAM Using Open Source Software 
21. A Fast Stereo Visual-Inertial Odometry for MAVs 
22. Enhanced Visual Loop Closing for Laser-Based SLAM 
23. Lightweight Visual Odometry for Autonomous Mobile Robots 
24. Robustness Improvement of Long Range Landmark Tracking for Mobile Robots 
25. Grid Map Guided Indoor 3D Reconstruction for Mobile Robots with RGB-D Sensors 
26. Directional grid maps: modeling multimodal angular uncertainty in dynamic environments 
27. A Loop Closure Detection Algorithm in Dynamic Scene [动态环境下回环检测] 
28. A Review of Visual-Inertial Simultaneous Localization and Mapping from Filtering-Based and Optimization-Based Perspectives [VINSLAM 综述] 
29. UFSM_VO: STEREO ODOMETRY BASED ON UNIFORMLY FEATURE SELECTION AND STRICTLY CORRESPONDENCE MATCHING [创新度一般] 
30. DOVO: Mixed Visual Odometry Based on Direct Method and Orb Feature [通过特征点个数判断用直接法与光流法，交替使用] 
31. 2018-09-10-Monocular Object and Plane SLAM in Structured Environments [约束中加入识别的物体与平面] 
32. 2018-09-14-Linear RGB-D SLAM for Planar Environments [卡尔曼滤波估计位姿与平面特征] 
33. 2018-09-14-Good Line Cutting: towards Accurate Pose Tracking of Line-assisted VO/VSLAM [对于线特征提取线内信息最多的一段做SLAM，声称对低纹理，运动模糊鲁棒] 
34. 2018-09-14-Deep Virtual Stereo Odometry:Leveraging Deep Depth Prediction for Monocular Direct Sparse Odometry [Cremers出品，用单目深度估计+DSO] 
35. 2018-09-14-Modeling Varying Camera-IMU Time Offset in Optimization-Based Visual-Inertial Odometry [科大沈老师门生根叔出品，解决了卷帘快门问题，加速IMU预积分，以及使初始化更鲁棒，AR界梦寐以求的算法，可惜没代码] 
36. 2018-09-14-Direct Sparse Odometry with Rolling Shutter [同样是Cremers出品，看题目就知道了] 
37. 2018-09-14-VSO: Visual Semantic Odometry [题目越短，文章越牛逼？] 
38. 2018-09-14-Semantically Aware Urban 3D Reconstruction with Plane-Based Regularization [最近都很喜欢加平面信息做SLAM] 
39. 2018-09-14-Scale-Awareness of Light Field Camera based Visual Odometry [传感器特殊，使用光场相机：https://www.zhihu.com/question/20511442/answer/24066624] 
40. 2018-09-14-Stereo Vision-based Semantic 3D Object and Ego-motion Tracking for Autonomous Driving [沈老师出品，既估计相机位姿，也估计物体位置，对动态物体鲁棒] 
41. 2018-09-14-Structure-from-Motion-Aware PatchMatch for Adaptive Optical Flow Estimation [三维重建方向] 
42. 2018-09-14-Fast and Accurate Camera Covariance Computation for Large 3D Reconstruction [以数学为切入点，难懂] 
43. 2018-09-14-Stereo relative pose from line and point feature triplets [点线结合，但是匹配的是三帧图像] 
44. 2018-09-14-Realtime Time Synchronized Event-based Stereo [双目事件相机，第一家吧] 

ICRA+CVPR 
45. [ICRA 2018] Detection and Resolution of Motion Conflict in Visual Inertial Odometry [解决视觉与IMU估计值之间冲突问题] 
46. [ICRA 2018] Monocular Visual Odometry Scale Recovery using Geometrical Constraint 
47. [ICRA 2018] A Monocular SLAM System Leveraging Structural Regularity in Manhattan World [国内慢慢也有实验室开源了原理与code：http://cvrs.whu.edu.cn/projects/Struct-PL-SLAM/] 
48. [ICRA 2018] Feature-constrained Active Visual SLAM for Mobile Robot Navigation [路径规划时候考虑特征点数量,代码在此：https://github.com/XinkeAE/Active-ORB-SLAM2] 
49. [ICRA 2018] Trajectory Replanning for Quadrotors Using Kinodynamic Search and Elastic Optimization 
50. [ICRA 2018] Online Safe Trajectory Generation for Quadrotors Using Fast Marching Method and Bernstein Basis Polynomial [沈老师连续两篇路径规划] 
51. [ICRA 2018] Assigning Visual Words to Places for Loop Closure Detection [使用GNG clustering algorithm] 
52. [ICRA 2018] Semi-Dense Visual-Inertial Odometry and Mapping for Quadrotors with SWAP Constraints 
53. [ICRA 2018] Online Initialization and Automatic Camera-IMU Extrinsic Calibration for Monocular Visual-Inertial SLAM [单目IMU自动标定，老铁知道比VINS好在哪里么] 
54. [CVPR 2018] Benchmarking 6DOF Outdoor Visual Localization in Changing Conditions [针对于场景变化较大时，例如四季变换的SLAM数据集] 
55. [CVPR 2018] ICE-BA: Incremental, Consistent and Efficient Bundle Adjustment for Visual-Inertial [SLAM新的优化库] 
56. [CVPR 2018] Fast Monte-Carlo Localization on Aerial Vehicles usingApproximate Continuous Belief Representations [粒子滤波viusal+IMU] 
57. [CVPR 2018] CodeSLAM — Learning a Compact, Optimisable Representation for Dense Visual SLAM 
58. [CVPR 2018] Semantic Visual Localization 
59. [CVPR 2018] Polarimetric Dense Monocular SLAM [偏振光传感器SLAM，传感器原理：http://thinklucid.cn/tech-briefs/polarization-explained-sony-polarized-sensor/] 
60. [CVPR 2018] InLoc: Indoor Visual Localization with Dense Matching and View Synthesis [已知3Dmap做定位] 
61. [CVPR 2018] Unsupervised Learning of Monocular Depth Estimation and Visual Odometry with Deep Feature Reconstruction [Ian Reid出品，代码在此：https://github.com/Huangying-Zhan/Depth-VO-Feat]
