---
title: "Multiscale Point Cloud Geometry Compression"
collection: papers-conference
permalink: /papers-conference/2021-03-24-Multiscale Point Cloud Geometry Compression
excerpt: 'Jianqiang Wang, **Dandan Ding**, Zhu Li, and Zhan Ma*'
date: 2021-03-24
venue: 'IEEE Data Compression Conference (DCC), Snow Bird, UT, USA'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9418789'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Recent years have witnessed the growth of point cloud based applications for both immersive media as well as 3D sensing for auto-driving, because of its realistic and fine-grained representation of 3D objects and scenes. However, it is a challenging problem to compress sparse, unstructured, and high-precision 3D points for efficient communication. In this paper, leveraging the sparsity nature of the point cloud, we propose a multiscale end-to-end learning framework that hierarchically reconstructs the 3D Point Cloud Geometry (PCG) via progressive re-sampling. The framework is developed on top of a sparse convolution based autoencoder for point cloud compression and reconstruction. For the input PCG which has only the binary occupancy attribute, our framework translates it to a down-scaled point cloud at the bottleneck layer which possesses both geometry and associated feature attributes. Then, the geometric occupancy is losslessly compressed using an octree codec and the feature attributes are lossy compressed using a learned probabilistic context model. Compared with the state-of-the-art Video-based Point Cloud Compression (V-PCC) and Geometry-based PCC (G-PCC) schemes standardized by the Moving Picture Experts Group (MPEG), our method achieves more than 40% and 70% BD-Rate (BjØntegaard Delta Rate) reduction, respectively. We would like to make all materials publicly accessible at https://njuvision.github.io/PCGCv2/ for reproducible research.