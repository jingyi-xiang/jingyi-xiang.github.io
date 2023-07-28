---
layout: page
permalink: /research/
title: Research
description: 
nav: true
nav_order: 4
---

See below for my research experiences listed in reverse chronological order.

&nbsp;

##### **Senior Thesis (Fall 2023 - Spring 2024)**
---
* In progress :)

&nbsp;

##### **ECE Independent Study with the Bretl Research Group (Fall 2022 - Spring 2023)**
---
* Collaborated with other researchers in the group to create [COCOpen](https://rmdlo.github.io/COCOpen-OpenCV/), an open-source library that automatically generates datasets of color images with objects of interest, labeled with object instance segmentation masks, bounding boxes, and category identification.
* Developed a new deformable linear object tracking algorithm, TrackDLO, for robust deformable linear object tracking under occlusion and incomplete data input.
* Developed the open-source [TrackDLO ROS (Robot Operating System) package](https://github.com/RMDLO/trackdlo) with the TrackDLO algorithm implemented in C++.
* Delivered two hour-long research presentations to the Bretl Research Group on the topic of deformable object perception and tracking (Presentation slides: [Fall 2022](https://jingyi-xiang.github.io/assets/pdf/BRG_Fall_2022.pdf), [Spring 2023](https://jingyi-xiang.github.io/assets/pdf/BRG_Spring_2023.pdf)).
* Completed a paper on the TrackDLO algorithm which was accepted into the IEEE Robotics and Automation Letters (RA-L).
* Completed an extended abstract on simultaneous multi-DLO tracking and presented a [poster](https://jingyi-xiang.github.io/assets/pdf/multi_dlo_poster.pdf) at IEEE International Conference on Robotics and Automation (ICRA) Workshop on Representing and Manipulating Deformable Objects.
* Presented a [poster](https://jingyi-xiang.github.io/assets/pdf/poster_urs23.pdf) on the TrackDLO algorithm at the 2023 UIUC Undergraduate Research Symposium.

##### <u>Highlights
<p align="center">
    <img src="../assets/img/dlo.jpg" height="175" /> <img src="../assets/img/multidlo_result.png" height="175" />
</p>
<p align="center">
    <img src="../assets/img/multi_dlo_poster.png" height="278" /> <img src="../assets/img/poster_urs23.png" height="278" />
</p>
From left to right, top to bottom:
1. We ran our TrackDLO algorithm on a rope posed to resemble the word "DLO" (**D**eformable **L**inear **O**bject).
2. Our [multi-dlo package](https://github.com/RMDLO/multi-dlo) successfully tracks three identical blue ropes twisted together.
3. Our poster presented at the ICRA 2023 Workshop on Representing and Manipulating Deformable Objects.
4. My poster presented at the 2023 UIUC Undergraduate Research Symposium.

&nbsp;

##### **Illinois Space Grant Consortium's Undergraduate Research Opportunity Program (Summer 2022)**
---
* Selected to participate in a paid 10-week summer research program with the Bretl Research Group.
* Designed and 3D printed custom camera mounts for linking the camera and the robot end-effector.
* Calibrated our hardware system with fiducial markers and two eye-in-hand camera calibration algorithms: the Tsai-Lenz algorithm and a recently published method based on pose graph optimization.
* Basing off of point set registration algorithm [Global-Local Toplogy Preservation](https://www.cv-foundation.org/openaccess/content_cvpr_workshops_2014/W04/papers/Ge_Non-rigid_Point_Set_2014_CVPR_paper.pdf), developed a new method for tracking multiple deformable linear objects simultaneously without contiuous instance segmentation.
* Delivered a 15-minute presentation at the program symposium.

##### <u>Highlights
<p align="center">
    <img src="../assets/img/wire_stacked_pc.png" height="280" /> <img src="../assets/img/gmm_cpd.png" height="280" />
</p>
From left to right, top to bottom:
1. The point cloud of an ethernet cable produced by stitching together several point clouds taken from different perspectives.
2. I implemented Gaussian Mixture Model (GMM) clustering and Coherent Point Drift (CPD) from scratch and compared their performance for point set registration under occlusion.

&nbsp;

##### **Undergraduate Research Apprenticeship Program (Spring 2022)**
---
* Selected as one of the 60 participants from a pool of more than 500 applicants to work with a graduate student mentor on research projects.
* Implemented the Copy-Paste Augmentation method in an automated dataset generation process to scale the amount of available training data and to eliminate the time-consuming process of manual image annotation.
* Identified, implemented, and evaluated two state-of-the-art deformable linear object instance segmentation algorithms.
* Used the instance segmentation masks output from Mask R-CNN to segment featureless point clouds in stereo depth imagery.
* Presented a [poster](https://jingyi-xiang.github.io/assets/pdf/poster_urs22.pdf) at the 2022 UIUC Undergraduate Research Symposium.

##### <u>Highlights
<p align="center">
    <img src="../assets/img/segmentation_rgb_pc.png" height="300" /> <img src="../assets/img/poster_urs22.png" height="300" />
</p>
From left to right, top to bottom:
1. The RGB cable instance segmentation result and the corresponding segmented point cloud produced by a trained Mask R-CNN model.
2. My poster presented at the 2022 UIUC Undergraduate Research Symposium.

&nbsp;

##### **Bonus**
---
Here is a quick sketch I did when taking a break from research.
<p align="left">
    <img src="../assets/img/sketch.jpg" height="300" />
</p>