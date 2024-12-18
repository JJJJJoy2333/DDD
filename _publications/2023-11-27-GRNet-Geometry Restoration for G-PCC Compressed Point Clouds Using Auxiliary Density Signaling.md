---
title: "GRNet: Geometry Restoration for G-PCC Compressed Point Clouds Using Auxiliary Density Signaling"
collection: papers-journal
permalink: /papers-journal/2023-11-27-GRNet-Geometry Restoration for G-PCC Compressed Point Clouds Using Auxiliary Density Signaling
excerpt: ' Gexin Liu, Ruixiang Xue, Jiaxin Li, <strong>Dandan Ding</strong>, Zhan Ma'
date: 2024-10-07
venue: 'IEEE Transactions on Visualization and Computer Graphics'
paperurl: ' https://ieeexplore.ieee.org/abstract/document/10328911'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---


The lossy Geometry-based Point Cloud Compression (G-PCC) inevitably impairs the geometry information of point clouds, which deteriorates the quality of experience (QoE) in reconstruction and/or misleads decisions in tasks such as classification. To tackle it, this work proposes GRNet for the geometry restoration of G-PCC compressed large-scale point clouds. By analyzing the content characteristics of original and G-PCC compressed point clouds, we attribute the G-PCC distortion to two key factors: point vanishing and point displacement. Visible impairments on a point cloud are usually dominated by an individual factor or superimposed by both factors, which are determined by the density of the original point cloud. To this end, we employ two different models for coordinate reconstruction, termed Coordinate Expansion and Coordinate Refinement, to attack the point vanishing and displacement, respectively. In addition, 4-byte auxiliary density information is signaled in the bitstream to assist the selection of Coordinate Expansion, Coordinate Refinement, or their combination. Before being fed into the coordinate reconstruction module, the G-PCC compressed point cloud is first processed by a Feature Analysis Module for multiscale information fusion, in which k NN-based Transformer is leveraged at each scale to adaptively characterize neighborhood geometric dynamics for effective restoration. Following the common test conditions recommended in the MPEG standardization committee, GRNet significantly improves the G-PCC anchor and remarkably outperforms state-of-the-art methods on a great variety of point clouds ( e.g. , solid, dense, and sparse samples) both quantitatively and qualitatively. Meanwhile, GRNet runs fairly fast and uses a smaller-size model when compared with existing learning-based approaches, making it attractive to industry practitioners.
