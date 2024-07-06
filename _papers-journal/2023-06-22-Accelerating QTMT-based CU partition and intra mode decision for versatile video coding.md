---
title: "Accelerating QTMT-based CU partition and intra mode decision for versatile video coding"
collection: papers-journal
permalink: /papers-journal/2023-06-22-Accelerating QTMT-based CU partition and intra mode decision for versatile video coding
excerpt: 'Gongchun Ding, Xiujun Lin, Junjie Wang, **Dandan Ding**'
date: 2023-06-22
venue: 'Journal of Visual Communication and Image Representation'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S1047320323000822'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

The H.266/VVC achieves about 50% bitrate saving compared to its predecessor H.265/HEVC at the expense of exponentially increased computational complexity. The most efficient but complex technique for H.266/VVC intra frame coding is the QuadTree with a nested Multi-type Tree encoding structure (QTMT), which usually requires traversing the Rate-Distortion (R-D) cost of each partition and each mode for the best option. To alleviate such computational burden while preserving the coding efficiency as much as possible, this paper develops a multi-feature guided Fast CU Partition (FCP) and Laplacian guided Fast Mode Selection (FMS) to accelerate the intra QTMT decision together. For FCP, we regard the CU partition as a classification problem and adopt the Support Vector Machine (SVM) for its low-complexity implementation; after evaluating the contribution of a set of features, three representative features of video textures are selected and used to train the SVM model. Additionally, an advanced technique is applied by adopting a soft decision in SVM for a more flexible trade-off between the complexity and R-D performance. For FMS, we utilize the Laplace operator to determine the most probable directions of the current CU and skip half of the candidate modes for runtime saving. Experimental results demonstrate that the proposed FCP reduces the encoding time of H.266/VVC by 51.03% with 1.65% Bjøntegaard Delta Bit-Rate (BDBR) increase; the proposed FMS reduces the encoding time by 12.68% with 0.09% BDBR loss. Their direct combination and advanced combination finally lead to 54.84% encoding time reduction with 1.74% BDBR increase and 40.39% encoding time reduction with 1.33% BDBR increase, respectively, outperforming state-of-the-art approaches significantly.
