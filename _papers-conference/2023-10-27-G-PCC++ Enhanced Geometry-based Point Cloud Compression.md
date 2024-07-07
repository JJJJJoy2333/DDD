---
title: "G-PCC++: Enhanced Geometry-based Point Cloud Compression"
collection: papers-conference
permalink: /papers-conference/2023-10-27-G-PCC++ Enhanced Geometry-based Point Cloud Compression
excerpt: 'Junzhe Zhang, Tong Chen, <strong>Dandan Ding</strong>, and Zhan Ma'
date: 2023-10-27
venue: '31st ACM International Conference on Multimedia (ACM MM)'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3581783.3613827'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

MPEG Geometry-based Point Cloud Compression (G-PCC) standard is developed for lossy encoding of point clouds to enable immersive services over the Internet. However, lossy G-PCC introduces superimposed distortions from both geometry and attribute information, seriously deteriorating the Quality of Experience (QoE). This paper thus proposes the Enhanced G-PCC (GPCC++), to effectively address the compression distortion and restore the quality. G-PCC++ separates the enhancement into two stages: it first enhances the geometry and then maps the decoded attribute to the enhanced geometry for refinement. As for geometry restoration, a k Nearest Neighbors (kNN)-based Linear Interpolation is first used to generate a denser geometry representation, on top of which GeoNet further generates sufficient candidates to restore geometry through probability-sorted selection. For attribute enhancement, a kNN-based Gaussian Distance Weighted Mapping is devised to re-colorize all points in enhanced geometry tensor, which are then refined by AttNet for the final reconstruction. G-PCC++ is the first solution addressing the geometry and attribute artifacts together. Extensive experiments on several public datasets demonstrate the superiority of G-PCC++, e.g., on the solid point cloud dataset 8iVFB, G-PCC++ outperforms G-PCC by 88.24% (80.54%) BD-BR in D1 (D2) measurement of geometry and by 14.64% (13.09%) BD-BR in Y (YUV) attribute. Moreover, when considering both geometry and attribute, G-PCC++ also largely surpasses G-PCC by 25.58% BD-BR using PCQM assessment.
