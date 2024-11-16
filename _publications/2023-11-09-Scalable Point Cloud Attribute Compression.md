---
title: "Scalable Point Cloud Attribute Compression"
collection: papers-journal
permalink: /papers-journal/2023-11-09-Scalable Point Cloud Attribute Compression
excerpt: 'Junteng Zhang, Jianqiang Wang, <strong>Dandan Ding</strong>, Zhan Ma'
date: 2023-11-09
venue: 'Scalable Point Cloud Attribute Compression, IEEE Trans. Multimedia (TMM)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10313579'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---


This paper develops a Scalable Point Cloud Attribute Compression solution, termed ScalablePCAC. In a two-layer example, ScalablePCAC uses the standard G-PCC at the base layer to directly encode the thumbnail point cloud that is downscaled from the original input, and a learning-based model at the enhancement layer to compress and restore the full-resolution input point cloud conditioned on the base layer reconstruction. As such, the base layer provides a coarse reconstruction of the input point cloud and the enhancement layer further improves the quality. We then adopt a cross-layer rate allocation strategy that flexibly determines the resolution downscaling factor, the quantization parameter of the base layer, and the quality controlling factor of the enhancement layer to adapt the bitrate of the two layers for approximately optimal Rate-Distortion (R-D) performance. We conduct extensive experiments on popular point clouds following the MPEG common test conditions. Results demonstrate that the proposed ScalablePCAC achieves > 10% BD-BR reduction against the latest G-PCC version 22 (TMC13v22) on the Y component; it also significantly outperforms existing learning-based solutions for point cloud attribute compression, e.g., compared with a recent work showing state-of-the-art performance, it achieves > 20% BD-BR reduction.
