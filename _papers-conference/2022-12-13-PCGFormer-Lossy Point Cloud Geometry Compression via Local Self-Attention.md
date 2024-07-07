---
title: "PCGFormer: Lossy Point Cloud Geometry Compression via Local Self-Attention"
collection: papers-conference
permalink: /papers-conference/2022-12-13-PCGFormer-Lossy Point Cloud Geometry Compression via Local Self-Attention
excerpt: 'Gexin Liu, Jianqiang Wang, <strong>Dandan Ding</strong>, Zhan Ma'
date: 2022-12-13
venue: '2022 IEEE International Conference on Visual Communications and Image Processing (VCIP), Suzhou, China'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10008892'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Although the multiscale sparse tensor using stacked convolutions has attained noticeable gains for lossy compression of point cloud geometry (PCG), its capability suffers because convolutions with fixed receptive field and fixed weights after training cannot aggregate sufficient information collection due to the extremely sparse and unevenly distributed nature of points. To best tackle the sparsity and adaptively exploit inter-point correlations, we apply local self-attention on k nearest neighbors (kNN) that are instantaneously formed for each point, with which attention-based mechanism can effectively characterize and embed spatial information conditioned on the dynamic neighborhood. This kNN self-attention is implemented using the prevalent Transformer architecture and stacked with sparse convolutions to capture neighborhood information in a progres-sively re-sampling framework, referred to as the PCGFormer. Compared with the MPEG standard Geometry-based PCC (G-PCC) using the latest octree codec, the proposed PCGFormer provides more than 90% and 87% BD-rate (Bjøntegaard Delta Rate) reduction in average across three different object point cloud datasets for point-to-point (D1) and point-to-plane (D2) distortion measures. Compared with the state-of-the-art learning-based approach, the PCGFormer achieves 17.39% and 15.75% BD-rate gains on D1 and D2, respectively.
