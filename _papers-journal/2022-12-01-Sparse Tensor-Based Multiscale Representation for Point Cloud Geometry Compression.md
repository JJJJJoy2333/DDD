---
title: "Sparse Tensor-Based Multiscale Representation for Point Cloud Geometry Compression"
collection: papers-journal
permalink: /papers-journal/2022-12-01-Sparse Tensor-Based Multiscale Representation for Point Cloud Geometry Compression
excerpt: 'Jianqiang Wang, **Dandan Ding**, Zhu Li, Xiaoxing Feng, Chuntong Cao, Zhan Ma'
date: 2022-12-01
venue: 'IEEE Transactions on Pattern Analysis and Machine Intelligence'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9968173'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

This study develops a unified Point Cloud Geometry (PCG) compression method through the processing of multiscale sparse tensor-based voxelized PCG. We call this compression method SparsePCGC. The proposed SparsePCGC is a low complexity solution because it only performs the convolutions on sparsely-distributed Most-Probable Positively-Occupied Voxels (MP-POV). The multiscale representation also allows us to compress scale-wise MP-POVs by exploiting cross-scale and same-scale correlations extensively and flexibly. The overall compression efficiency highly depends on the accuracy of estimated occupancy probability for each MP-POV. Thus, we first design the Sparse Convolution-based Neural Network (SparseCNN) which stacks sparse convolutions and voxel sampling to best characterize and embed spatial correlations. We then develop the SparseCNN-based Occupancy Probability Approximation (SOPA) model to estimate the occupancy probability either in a single-stage manner only using the cross-scale correlation, or in a multi-stage manner by exploiting stage-wise correlation among same-scale neighbors. Besides, we also suggest the SparseCNN based Local Neighborhood Embedding (SLNE) to aggregate local variations as spatial priors in feature attribute to improve the SOPA. Our unified approach not only shows state-of-the-art performance in both lossless and lossy compression modes across a variety of datasets including the dense object PCGs (8iVFB, Owlii, MUVB) and sparse LiDAR PCGs (KITTI, Ford) when compared with standardized MPEG G-PCC and other prevalent learning-based schemes, but also has low complexity which is attractive to practical applications.
