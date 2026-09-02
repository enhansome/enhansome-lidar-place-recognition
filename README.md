# Awesome lidar place recognition with stars

<div align="center">
    <h1>Awesome LiDAR Place Recognition </h1>
<div>

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 502,344 | 🐛 105 | 📅 2026-09-02

</div>

![image](awesome-lidar-place-recognition.gif)

</div>

> Thumbnail Figures from Complex Urban, Wild-Places, and DiTer datasets / our place recognition method (TBD) / DiSCo-SLAM.

This repository is the collection of LiDAR Place Recognition Research that provides a code or a download page, together. This repository also reports the datasets for Place Recognition and various algorithms utilized in Place Recognition (e.g. multi-robot mapping, SLAM).

LiDAR Place Recognition can be broadly categorized into **handcraft**-based and **learning**-based methods.

Datasets for LiDAR Place Recognition are classified into **single-session**, **multi-session**, and **multi-robot session**. Additionally, it is possible to confirm which **LiDAR** was used and which **vehicle** was utilized (🚙 🤖 🛩️ 🚢).

Finally, **various algorithms** that play an important role in Place Recognition are introduced.

🔥 represents a paper citation count of 50 or more, or a code's star count of 50 or more.

## Contents

<!-- - [News](#news) -->

* [LiDAR Place Recognition Methods](#lidar-place-recognition-methods)
* [LiDAR Place Recognition Datasets](#lidar-place-recognition-datasets)
* [LiDAR Place Recognition with Various Algorithms](#lidar-place-recognition-with-various-algorithms)

## News

**`24.08.18`** Update 3 papers (BEVPlace++, RangePlace, NDTMC, SOLiD)

<details>
<summary>Previous</summary>
<div markdown="1">

* **`24.05.21`** Merged [awesome-lidar repository](https://github.com/szenergy/awesome-lidar) ⭐ 1,336 | 🐛 0 | 📅 2026-03-16!

* **`24.03.20`**  First pull request!

* **`24.03.19`**  First commit!

</div>
</details>

## LiDAR Place Recognition Methods

* 2024

  * **`Handcraft`** **`ICRA`** Effectively Detecting Loop Closures using Point Cloud Density Maps 🔥

    [![Paper](https://img.shields.io/badge/📄%20Paper-PDF-yellow)](https://www.ipb.uni-bonn.de/wp-content/papercite-data/pdf/gupta2024icra.pdf) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/PRBonn/MapClosures) ⭐ 431 | 🐛 2 | 🌐 C++ | 📅 2026-08-14

  * **`Learning`** **`TRO`** BEVPlace++: Fast, Robust, and Lightweight LiDAR Global Localization for Unmanned Ground Vehicles 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2408.01841-b31b1b.svg?style=flat-square)](https://www.arxiv.org/abs/2408.01841) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/zjuluolun/BEVPlace) ⭐ 384 | 🐛 4 | 🌐 Python | 📅 2025-07-24

  * **`Handcraft`** **`TRO`** BTC: A Binary and Triangle Combined Descriptor for 3D Place Recognition 🔥

    [![Paper](https://img.shields.io/badge/📄%20Paper-PDF-yellow)](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=\&arnumber=10388464) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/hku-mars/btc_descriptor) ⭐ 357 | 🐛 14 | 🌐 C++ | 📅 2024-10-07

  * **`Handcraft`** **`IROS`** NDT-Map-Code: A 3D global descriptor for real-time loop closure detection in lidar SLAM 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2307.08221-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2307.08221) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/SlamCabbage/NDTMC) ⭐ 226 | 🐛 0 | 🌐 C++ | 📅 2025-01-06

  * **`Handcraft`** **`RAL`** Narrowing your FOV with SOLiD: Spatially Organized and Lightweight Global Descriptor for FOV-constrained LiDAR Place Recognition 🔥

    [![Paper](https://img.shields.io/badge/📄%20Paper-PDF-yellow)](https://ieeexplore.ieee.org/abstract/document/10629042) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/sparolab/solid) ⭐ 206 | 🐛 0 | 🌐 Python | 📅 2026-08-11

  * **`Learning`** **`TRO`** Fast and Accurate Deep Loop Closing and Relocalization for Reliable LiDAR SLAM

    [![arXiv](https://img.shields.io/badge/arXiv-2309.08086-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2309.08086) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/nubot-nudt/LCR-Net) ⭐ 117 | 🐛 1 | 🌐 Python | 📅 2024-12-05

  * **`Learning`** **`Arxiv`** OverlapMamba: Novel Shift State Space Model for LiDAR-based Place Recognition

    [![arXiv](https://img.shields.io/badge/arXiv-2405.07966-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2405.07966) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/SCNU-RISLAB/OverlapMamba) ⭐ 73 | 🐛 3 | 🌐 Python | 📅 2024-05-21

  * **`Learning`** **`ICCV`** CrossLoc3D: Aerial-Ground Cross-Source 3D Place Recognition

    [![arXiv](https://img.shields.io/badge/arXiv-2303.17778-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2303.17778) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/rayguan97/crossloc3d) ⭐ 67 | 🐛 3 | 🌐 Python | 📅 2026-08-31

  * **`Handcraft`** **`TIM`** OSK: A Novel LiDAR Occupancy Set Key-Based Place Recognition Method in Urban Environment

    [![Paper](https://img.shields.io/badge/📄%20Paper-PDF-yellow)](https://ieeexplore.ieee.org/abstract/document/10464375) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/ZhangZh3ng/Occupancy-Set-Key) ⭐ 32 | 🐛 0 | 🌐 C++ | 📅 2024-02-22

  * **`Learning`** **`RAL`** P-GAT: Pose-Graph Attentional Network for Lidar Place Recognition

    [![arXiv](https://img.shields.io/badge/arXiv-2309.00168-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2309.00168) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/csiro-robotics/P-GAT) ⭐ 30 | 🐛 0 | 🌐 Python | 📅 2024-01-25

  * **`Learning`** **`TIV`** RangePlace: A Hierarchical Range Image Transformer for LiDAR-Based Place Recognition

    [![Paper](https://img.shields.io/badge/📄%20Paper-PDF-yellow)](https://ieeexplore.ieee.org/abstract/document/10634124) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/JiLiBIT/RangePlace) ⭐ 21 | 🐛 1 | 🌐 Python | 📅 2024-10-10

* 2023

  * **`Handcraft`** **`ICRA`** STD: A Stable Triangle Descriptor for 3D place recognition 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2209.12435-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2209.12435) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/hku-mars/STD) ⭐ 735 | 🐛 34 | 🌐 C++ | 📅 2023-05-06

  * **`Learning`** **`ICCV`** BEVPlace: Learning LiDAR-based Place Recognition using Bird's Eye View Images 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2302.14325-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2302.14325) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/zjuluolun/BEVPlace) ⭐ 384 | 🐛 4 | 🌐 Python | 📅 2025-07-24

  * **`Handcraft`** **`TRO`** RING++: Roto-Translation-Invariant Gram for Global Localization on a Sparse Scan Map 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2210.05984-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2210.05984) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/lus6-Jenny/RING) ⭐ 229 | 🐛 1 | 🌐 Python | 📅 2024-04-14

  * **`Handcraft`** **`ICRA`** Contour Context: Abstract Structural Distribution for 3D LiDAR Loop Detection and Metric Pose Estimation 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2302.06149-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2302.06149) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/lewisjiang/contour-context) ⭐ 206 | 🐛 7 | 🌐 C++ | 📅 2024-03-06

  * **`Learning`** **`IROS`** Uncertainty-Aware Lidar Place Recognition in Novel Environments 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2210.01361-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2210.01361) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/csiro-robotics/Uncertainty-LPR) ⭐ 66 | 🐛 0 | 🌐 Python | 📅 2023-07-28

* 2022

  * **`Handcraft`** **`TRO`** Scan Context++: Structural Place Recognition Robust to Rotation and Lateral Variations in Urban Environments 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2109.13494-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2109.13494) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/gisbi-kim/scancontext_tro) ⭐ 339 | 🐛 3 | 🌐 MATLAB | 📅 2025-05-03

  * **`Learning`** **`RAL/IROS`** OverlapTransformer: An Efficient and Yaw-Angle-Invariant Transformer Network for LiDAR-Based Place Recognition 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2203.03397-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2203.03397) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/haomo-ai/OverlapTransformer) ⭐ 294 | 🐛 3 | 🌐 Python | 📅 2024-07-29

  * **`Learning`** **`TRO`** LCDNet: Deep Loop Closure Detection and Point Cloud Registration for LiDAR SLAM 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2103.05056-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2103.05056) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/robot-learning-freiburg/LCDNet) ⭐ 218 | 🐛 3 | 🌐 Python | 📅 2025-01-09

  * **`Learning`** **`IROS`** D-LC-Nets: Robust Denoising and Loop Closing Networks for LiDAR SLAM in Complicated Circumstances with Noisy Point Clouds 🔥

    [![Paper](https://img.shields.io/badge/📄%20Paper-PDF-yellow)](https://ieeexplore.ieee.org/abstract/document/9981388) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/KangchengLiu/DLC_LiDAR_SLAM) ⭐ 149 | 🐛 0 | 🌐 C++ | 📅 2022-12-27

  * **`Learning`** **`ICRA`** LoGG3D-Net: Locally Guided Global Descriptor Learning for 3D Place Recognition 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2109.08336-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2109.08336) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/csiro-robotics/LoGG3D-Net) ⭐ 115 | 🐛 1 | 🌐 Python | 📅 2023-10-06

  * **`Learning`** **`TIE`** SeqOT: A Spatial-Temporal Transformer Network for Place Recognition Using Sequential LiDAR Data 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2209.07951-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2209.07951) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/BIT-MJY/SeqOT) ⭐ 110 | 🐛 4 | 🌐 Python | 📅 2023-06-30

  * **`Learning`** **`ICPR`** Improving Point Cloud Based Place Recognition with Ranking-based Loss and Large Batch Training 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2203.00972-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2203.00972) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/jac99/MinkLoc3Dv2) ⭐ 98 | 🐛 0 | 🌐 Python | 📅 2024-01-31

  * **`Learning`** **`CVPR`** BVMatch: Lidar-based Place Recognition Using Bird's-eye View Images 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2109.00317-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2109.00317) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/zjuluolun/BVMatch) ⭐ 88 | 🐛 4 | 🌐 C++ | 📅 2022-01-17

  * **`Handcraft`** **`ICARCV`** Frequency-Domain Scan Context for Robust LiDAR-based Place Recognition with Translation and Rotation Invariance 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2206.12628-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2206.12628) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/soytony/FreSCo) ⭐ 70 | 🐛 1 | 🌐 MATLAB | 📅 2022-09-26

  * **`Learning`** **`RAL`** RINet: Efficient 3D Lidar-Based Place Recognition Using Rotation Invariant Neural Network

    [![Paper](https://img.shields.io/badge/📄%20Paper-PDF-yellow)](https://ieeexplore.ieee.org/abstract/document/9712221) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/lilin-hitcrt/RINet) ⭐ 48 | 🐛 4 | 🌐 Python | 📅 2022-03-01

  * **`Learning`** **`IROS`** InCloud: Incremental Learning for Point Cloud Place Recognition

    [![arXiv](https://img.shields.io/badge/arXiv-2203.00807-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2203.00807) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/csiro-robotics/InCloud) ⭐ 42 | 🐛 3 | 🌐 Python | 📅 2024-03-08

* 2021

  * **`Handcraft`** **`ICRA`** Robust Place Recognition using an Imaging Lidar 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2103.02111-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2103.02111) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/TixiaoShan/imaging_lidar_place_recognition) ⭐ 432 | 🐛 6 | 🌐 C++ | 📅 2024-08-05

  * **`Learning`** **`WACV`** MinkLoc3D: Point Cloud Based Large-Scale Place Recognition 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2011.04530-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2011.04530) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/jac99/MinkLoc3D) ⭐ 150 | 🐛 0 | 🌐 Python | 📅 2024-01-31

  * **`Learning`** **`ICRA`** Locus: LiDAR-based Place Recognition using Spatiotemporal Higher-Order Pooling 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2011.14497-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2011.14497) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/csiro-robotics/locus) ⭐ 126 | 🐛 0 | 🌐 Python | 📅 2024-06-12

  * **`Learning`** **`ICRA`** NDT-Transformer: Large-Scale 3D Point Cloud Localisation using the Normal Distribution Transform Representation 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2103.12292-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2103.12292) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/dachengxiaocheng/NDT-Transformer) ⭐ 104 | 🐛 4 | 🌐 Python | 📅 2021-03-26

  * **`Learning`** **`RAL/ICRA`** Disco: Differentiable scan context with orientation 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2010.10949-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2010.10949) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/MaverickPeter/DiSCO-pytorch) ⭐ 87 | 🐛 1 | 🌐 Python | 📅 2022-03-22

  * **`Learning`** **`RAL`** EgoNN: Egocentric Neural Network for Point Cloud Based 6DoF Relocalization at the City Scale

    [![arXiv](https://img.shields.io/badge/arXiv-2110.12486-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2110.12486) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/jac99/Egonn) ⭐ 65 | 🐛 3 | 🌐 Python | 📅 2022-03-03

  * **`Learning`** **`RAL`** MinkLoc3D-SI: 3D LiDAR Place Recognition With Sparse Convolutions, Spherical Coordinates, and Intensity

    [![arXiv](https://img.shields.io/badge/arXiv-2112.06539-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2112.06539) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/KamilZywanowski/MinkLoc3D-SI) ⭐ 34 | 🐛 0 | 🌐 Python | 📅 2022-02-14

* 2020

  * **`Learning`** **`RSS`** OverlapNet: Loop Closing for LiDAR-based SLAM 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2105.11344-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2105.11344) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/PRBonn/OverlapNet) ⭐ 734 | 🐛 8 | 🌐 Python | 📅 2023-03-24

  * **`Handcraft`** **`ICRA`** Intensity Scan Context: Coding Intensity and Geometry Relations for Loop Closure Detection 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2003.05656-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2003.05656) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/wh200720041/iscloam) ⭐ 603 | 🐛 16 | 🌐 C++ | 📅 2024-03-24

  * **`Learning`** **`IROS`** Semantic Graph Based Place Recognition for 3D Point Clouds 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2008.11459-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2008.11459) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/kxhit/SG_PR) ⭐ 205 | 🐛 2 | 🌐 Python | 📅 2024-07-25

  * **`Handcraft`** **`IROS`** LiDAR Iris for Loop-Closure Detection 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-1912.03825-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/1912.03825) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/BigMoWangying/LiDAR-Iris) ⭐ 122 | 🐛 4 | 🌐 C++ | 📅 2020-12-28

  * **`Learning`** **`TITS`** 3D LiDAR-Based Global Localization Using Siamese Neural Network 🔥

    [![Paper](https://img.shields.io/badge/📄%20Paper-PDF-yellow)](https://ieeexplore.ieee.org/abstract/document/8734150) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/HuanYin94/LocNet_caffe) ⭐ 32 | 🐛 0 | 📅 2022-07-13

* 2019

  * **`Learning`** **`CVPR`** PCAN: 3D Attention Map Learning Using Contextual Information for Point Cloud Based Retrieval

    [![arXiv](https://img.shields.io/badge/arXiv-1904.09793-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/1904.09793) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/XLechter/PCAN) ⭐ 75 | 🐛 1 | 🌐 Python | 📅 2022-12-20

* 2018

  * **`Learning`** **`CVPR`** PointNetVLAD: Deep Point Cloud Based Retrieval for Large-Scale Place Recognition 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-1804.03492-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/1804.03492) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/mikacuy/pointnetvlad) ⭐ 400 | 🐛 8 | 🌐 Python | 📅 2020-01-19

  * **`Handcraft`** **`IROS`** Scan Context: Egocentric Spatial Descriptor for Place Recognition Within 3D Point Cloud Map 🔥

    [![Paper](https://img.shields.io/badge/📄%20Paper-PDF-yellow)](https://ieeexplore.ieee.org/abstract/document/8593953) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/gisbi-kim/scancontext) ⭐ 112 | 🐛 4 | 🌐 C++ | 📅 2021-09-24

* 2017

  * **`Learning`** **`ICRA`** SegMatch: Segment based place recognition in 3D point clouds 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-1609.077200-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/1609.077200) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/ZengYeGe/segmatch) ⭐ 7 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2018-03-25

* 2016

  * **`Handcraft`** **`IROS`** M2DP: A novel 3D point cloud descriptor and its application in loop closure detection 🔥

    [![Paper](https://img.shields.io/badge/📄%20Paper-PDF-yellow)](https://ieeexplore.ieee.org/abstract/document/7759060) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/LiHeUA/M2DP) ⭐ 96 | 🐛 2 | 🌐 MATLAB | 📅 2019-01-22

* 2015

  * **`Handcraft`** **`IROS`** A Fast Histogram-Based Similarity Measure for Detecting Loop Closures in 3-D LIDAR Data 🔥

    [![Paper](https://img.shields.io/badge/📄%20Paper-PDF-yellow)](https://ieeexplore.ieee.org/abstract/document/7353454) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/wangliuliu/histogram) ⭐ 12 | 🐛 0 | 🌐 Makefile | 📅 2019-06-06

## LiDAR Place Recognition Datasets

* 2024

  * **`Multi`** **`RAL`** **`VLP-16`** **`Livox-Avia`** BotanicGarden: A High-Quality Dataset for Robot Navigation in Unstructured Natural Environments 🤖

    [![arXiv](https://img.shields.io/badge/arXiv-2306.14137-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2306.14137) [![ProjectPage](https://github.com/sparolab/Joint_ID/blob/main/fig/badges/badge-website.svg)](https://github.com/robot-pesg/BotanicGarden) ⭐ 304 | 🐛 13 | 🌐 Jupyter Notebook | 📅 2025-09-14

  * **`Single/Multi`** **`CVPR`** **`OS1-128`** **`OS1-64`** **`Mid-70`** MCD: Diverse Large-Scale Multi-Campus Dataset for Robot Perception 🤖 🧔

    [![arXiv](https://img.shields.io/badge/arXiv-2403.11496-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2403.11496) [![ProjectPage](https://github.com/sparolab/Joint_ID/blob/main/fig/badges/badge-website.svg)](https://mcdviral.github.io/)

  * **`Single/Multi`** **`IJRR`** **`OS2-128`** **`VLP-16`** **`Livox-Avia`** **`Aeva`** Heterogeneous LiDAR Dataset for inter-LiDAR Place Recognition 🚙

    [![arXiv](https://img.shields.io/badge/arXiv-2309.14590-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2309.14590) [![ProjectPage](https://github.com/sparolab/Joint_ID/blob/main/fig/badges/badge-website.svg)](https://sites.google.com/view/heliprdataset)

  * **`Single/Multi`** **`IEEE Sensors Letter`** **`OS1-64`** **`OS1-32`** DiTer: Diverse Terrain and Multi-Modal Dataset for Field Robot Navigation in Outdoor Environments 🤖

    [![Paper](https://img.shields.io/badge/📄%20Paper-PDF-yellow)](https://ieeexplore.ieee.org/abstract/document/10416213) [![ProjectPage](https://github.com/sparolab/Joint_ID/blob/main/fig/badges/badge-website.svg)](https://sites.google.com/view/diter-dataset/)

* 2023

  * **`Multi-Robot`** **`Arxiv`** **`VLP-16`** Resilient and Distributed Multi-Robot Visual SLAM: Datasets, Experiments, and Lessons Learned 🤖

    [![arXiv](https://img.shields.io/badge/arXiv-2304.04362-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2304.04362) [![ProjectPage](https://github.com/sparolab/Joint_ID/blob/main/fig/badges/badge-website.svg)](https://github.com/MIT-SPARK/Kimera-Multi-Data) ⭐ 199 | 🐛 6 | 📅 2026-07-07

  * **`Single/Multi`** **`ITSC`** **`Livox-Horizon`** NTU4DRadLM: 4D Radar-centric Multi-Modal Dataset for Localization and Mapping 🚙

    [![arXiv](https://img.shields.io/badge/arXiv-2309.00962-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2309.00962) [![ProjectPage](https://github.com/sparolab/Joint_ID/blob/main/fig/badges/badge-website.svg)](https://github.com/junzhang2016/NTU4DRadLM) ⭐ 188 | 🐛 16 | 📅 2024-03-22

  * **`Multi`** **`IROS-workshop`** **`Mid-70`** ConPR: Ongoing Construction Site Dataset for Place Recognition 🧔

    [![Paper](https://img.shields.io/badge/📄%20Paper-PDF-yellow)](https://oravus.github.io/vpr-workshop/assets/accepted_papers/1_conpr_ongoing_construction_sit.pdf) [![ProjectPage](https://github.com/sparolab/Joint_ID/blob/main/fig/badges/badge-website.svg)](https://github.com/dongjae0107/ConPR) ⭐ 68 | 🐛 0 | 🌐 C++ | 📅 2025-11-19

  * **`Multi-Robot`** **`Arxiv`** **`VLP-16`** S3E: A Large-scale Multimodal Dataset for Collaborative SLAM 🤖

    [![arXiv](https://img.shields.io/badge/arXiv-2210.13723-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2210.13723) [![ProjectPage](https://github.com/sparolab/Joint_ID/blob/main/fig/badges/badge-website.svg)](https://github.com/PengYu-Team/S3E) ⭐ 15 | 🐛 0 | 🌐 HTML | 📅 2025-10-17

  * **`Single/Multi`** **`ICRA`** **`VLP-16`** Wild-Places: A Large-Scale Dataset for Lidar Place Recognition in Unstructured Natural Environments 🧔

    [![arXiv](https://img.shields.io/badge/arXiv-2211.12732-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2211.12732) [![ProjectPage](https://github.com/sparolab/Joint_ID/blob/main/fig/badges/badge-website.svg)](https://csiro-robotics.github.io/Wild-Places/)

  * **`Multi`** **`IJRR`** **`VLP-128`** Boreas: A Multi-Season Autonomous Driving Dataset 🚙

    [![arXiv](https://img.shields.io/badge/arXiv-2203.10168-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2203.10168) [![ProjectPage](https://github.com/sparolab/Joint_ID/blob/main/fig/badges/badge-website.svg)](https://www.boreas.utias.utoronto.ca/#/)

  * **`Multi`** **`ISVC`** **`VLP-16`** Multimodal Dataset for Localization, Mapping and Crop Monitoring in Citrus Tree Farms 🤖

    [![arXiv](https://img.shields.io/badge/arXiv-2309.15332-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2309.15332) [![ProjectPage](https://github.com/sparolab/Joint_ID/blob/main/fig/badges/badge-website.svg)](https://ucr-robotics.github.io/Citrus-Farm-Dataset/)

  * **`Multi`** **`RAL`** **`VLP-16`** GRACO: A Multimodal Dataset for Ground and Aerial Cooperative Localization and Mapping 🛩️ 🤖

    [![Paper](https://img.shields.io/badge/📄%20Paper-PDF-yellow)](https://ieeexplore.ieee.org/abstract/document/10008011) [![ProjectPage](https://github.com/sparolab/Joint_ID/blob/main/fig/badges/badge-website.svg)](https://sites.google.com/view/graco-dataset)

  * **`Multi`** **`IJRR`** **`OS1-64`** **`OS1-32`** Pohang Canal Dataset: A Multimodal Maritime Dataset for Autonomous Navigation in Restricted Waters 🚢

    [![arXiv](https://img.shields.io/badge/arXiv-2303.05555-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2303.05555) [![ProjectPage](https://github.com/sparolab/Joint_ID/blob/main/fig/badges/badge-website.svg)](https://sites.google.com/view/pohang-canal-dataset)

* 2022

  * **`Multi-Robot`** **`RAL`** **`VLP-16`** DiSCo-SLAM: Distributed Scan Context-Enabled Multi-Robot LiDAR SLAM With Two-Stage Global-Local Graph Optimization 🤖

    [![Paper](https://img.shields.io/badge/📄%20Paper-PDF-yellow)](https://ieeexplore.ieee.org/abstract/document/9662965) [![ProjectPage](https://github.com/sparolab/Joint_ID/blob/main/fig/badges/badge-website.svg)](https://github.com/RobustFieldAutonomyLab/DiSCo-SLAM) ⭐ 291 | 🐛 15 | 🌐 C++ | 📅 2024-10-04

  * **`Single/Multi`** **`Arxiv`** **`VLP-16`** ALITA: A Large-scale Incremental Dataset for Long-term Autonomy 🚙

    [![arXiv](https://img.shields.io/badge/arXiv-2205.10737-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2205.10737) [![ProjectPage](https://github.com/sparolab/Joint_ID/blob/main/fig/badges/badge-website.svg)](https://github.com/MetaSLAM/ALITA) ⭐ 105 | 🐛 0 | 🌐 Python | 📅 2024-06-20

* 2021

  * **`Single`** **`ICRA`** **`OS1-128`** Robust Place Recognition using an Imaging Lidar 🧔

    [![arXiv](https://img.shields.io/badge/arXiv-2103.02111-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2103.02111) [![ProjectPage](https://github.com/sparolab/Joint_ID/blob/main/fig/badges/badge-website.svg)](https://github.com/TixiaoShan/imaging_lidar_place_recognition) ⭐ 432 | 🐛 6 | 🌐 C++ | 📅 2024-08-05

* 2020

  * **`Single/Multi`** **`ICRA`** **`OS1-64`** Multimodal Range Dataset for Urban Place Recognition 🚙

    [![Paper](https://img.shields.io/badge/📄%20Paper-PDF-yellow)](https://ieeexplore.ieee.org/abstract/document/9197298) [![ProjectPage](https://github.com/sparolab/Joint_ID/blob/main/fig/badges/badge-website.svg)](https://sites.google.com/view/mulran-pr)

  * **`Single/Multi`** **`ICRA`** **`HDL-32`** The Oxford Radar RobotCar Dataset: A Radar Extension to the Oxford RobotCar Dataset 🚙

    [![arXiv](https://img.shields.io/badge/arXiv-1909.01300-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/1909.01300) [![ProjectPage](https://github.com/sparolab/Joint_ID/blob/main/fig/badges/badge-website.svg)](https://oxford-robotics-institute.github.io/radar-robotcar-dataset/)

  * **`Single/Multi`** **`IROS`** **`HDL-32`** EU Long-term Dataset with Multiple Sensors for Autonomous Driving 🚙

    [![arXiv](https://img.shields.io/badge/arXiv-1909.03330-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/1909.03330) [![ProjectPage](https://github.com/sparolab/Joint_ID/blob/main/fig/badges/badge-website.svg)](https://epan-utbm.github.io/utbm_robocar_dataset/)

* 2019

  * **`Single`** **`IJRR`** **`VLP-16`** Complex urban dataset with multi-level sensors from highly diverse urban environments 🚙

    [![Paper](https://img.shields.io/badge/📄%20Paper-PDF-yellow)](https://journals.sagepub.com/doi/full/10.1177/0278364919843996) [![ProjectPage](https://github.com/sparolab/Joint_ID/blob/main/fig/badges/badge-website.svg)](https://sites.google.com/view/complex-urban-dataset)

* 2016

  * **`Multi`** **`IJRR`** **`HDL-32`** University of Michigan North Campus long-term vision and lidar dataset 🤖

    [![Paper](https://img.shields.io/badge/📄%20Paper-PDF-yellow)](https://journals.sagepub.com/doi/full/10.1177/0278364915614638) [![ProjectPage](https://github.com/sparolab/Joint_ID/blob/main/fig/badges/badge-website.svg)](http://robots.engin.umich.edu/nclt/)

* 2013

  * **`Single`** **`IJRR`** **`HDL-64`** Vision meets Robotics: The KITTI Dataset 🚙

    [![Paper](https://img.shields.io/badge/📄%20Paper-PDF-yellow)](https://journals.sagepub.com/doi/full/10.1177/0278364913491297) [![ProjectPage](https://github.com/sparolab/Joint_ID/blob/main/fig/badges/badge-website.svg)](https://www.cvlibs.net/datasets/kitti/raw_data.php)

## LiDAR Place Recognition with Various Algorithms

* 2023

  * **`Multi-Robot SLAM`** **`TRO`** MR\_SLAM with RING++: Roto-Translation-Invariant Gram for Global Localization on a Sparse Scan Map 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2210.05984-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2210.05984) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/MaverickPeter/MR_SLAM.git) ⭐ 366 | 🐛 8 | 🌐 C++ | 📅 2024-06-16

  * **`SLAM Framework`** **`ICRA`** Real-Time Simultaneous Localization and Mapping with LiDAR intensity 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2301.09257-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2301.09257)[![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/MISTLab/Intensity_based_LiDAR_SLAM) ⭐ 155 | 🐛 0 | 🌐 C++ | 📅 2024-03-07

  * **`SLAM Framework`** **`IEEE/ASME Transactions on Mechatronics`** DLC-SLAM: A Robust LiDAR-SLAM System With Learning-Based Denoising and Loop Closure 🔥

    [![Paper](https://img.shields.io/badge/📄%20Paper-PDF-yellow)](https://ieeexplore.ieee.org/abstract/document/10092189) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/KangchengLiu/DLC_LiDAR_SLAM) ⭐ 149 | 🐛 0 | 🌐 C++ | 📅 2022-12-27

  * **`Multi-Robot SLAM`** **`IEEE Sensors Journal`** DCL-SLAM: A Distributed Collaborative LiDAR SLAM Framework for a Robotic Swarm 🔥

    [![Paper](https://img.shields.io/badge/📄%20Paper-PDF-yellow)](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=\&arnumber=10375928) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/PengYu-Team/DCL-SLAM) ⭐ 0 | 🐛 0 | 📅 2025-03-27

* 2022

  * **`SLAM Framework`** **`ICEIC`** SC-LiDAR-SLAM: A Front-end Agnostic Versatile LiDAR SLAM System 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2201.06423-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2201.06423) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/gisbi-kim/SC-A-LOAM) ⭐ 625 | 🐛 20 | 🌐 C++ | 📅 2023-01-30 [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/gisbi-kim/SC-LeGO-LOAM) ⭐ 75 | 🐛 2 | 🌐 C++ | 📅 2023-12-04 [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/gisbi-kim/SC-LIO-SAM) ⭐ 841 | 🐛 22 | 🌐 C++ | 📅 2023-04-27 [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/gisbi-kim/FAST_LIO_SLAM) ⭐ 815 | 🐛 18 | 🌐 C++ | 📅 2022-12-28

  * **`Mapping Framework`** **`ICRA`** LT-mapper: A Modular Framework for LiDAR-based Lifelong Mapping 🔥

    [![arXiv](https://img.shields.io/badge/arXiv-2107.07712-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2107.07712) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/gisbi-kim/lt-mapper) ⭐ 544 | 🐛 8 | 🌐 C++ | 📅 2025-02-18

  * **`Multi-Robot SLAM`** **`RAL`** DiSCo-SLAM: Distributed Scan Context-Enabled Multi-Robot LiDAR SLAM With Two-Stage Global-Local Graph Optimization 🔥

    [![Paper](https://img.shields.io/badge/📄%20Paper-PDF-yellow)](https://ieeexplore.ieee.org/abstract/document/9662965) [![GitHub](https://badges.aleen42.com/src/github.svg)](https://github.com/RobustFieldAutonomyLab/DiSCo-SLAM) ⭐ 291 | 🐛 15 | 🌐 C++ | 📅 2024-10-04

## Contact

* Hogyun Kim (<hg.kim@inha.edu>)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-02._
