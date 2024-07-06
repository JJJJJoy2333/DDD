---
title: "Neural Adaptive Loop Filtering for Video Coding: Exploring Multi-Hypothesis Sample Refinement"
collection: papers-journal
permalink: /papers-journal/2023-03-22-Neural Adaptive Loop Filtering for Video Coding-Exploring Multi-Hypothesis Sample Refinement
excerpt: '**Dandan Ding**, Junjie Wang, Guangkun Zhen, Debargha Mukherjee, Urvang Joshi, Zhan Ma'
date: 2023-03-22
venue: 'IEEE Transactions on Circuits and Systems for Video Technology'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10078282'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---


Adaptive loop filtering (ALF) is extensively investigated for lossy video coding to mitigate compression noise. Numerous learning-based ALFs have emerged recently and improved the coding efficiency significantly through the use of complexity-intensive, large-scale models trained on excessive samples, making it impractical for real-life applications. By contrast, lightweight, small-scale ALF models cannot promise convincing performance and model generalization. In principle, the ALF estimates the sample distortion for restoration. Instead of directly approximating the distortion as in existing solutions, we reformulate it as a Multi-hypothesis Sample Refinement (MSR) problem. To this end, we first generate multiple distortion hypotheses through a deep neural network (DNN) model. Then, these hypotheses are linearly superimposed to approximate the final distortion through the minimization of mean square error (MMSE) between the filtered reconstruction and its original, uncompressed input. Finally, the linear superimposition coefficients are explicitly signaled in the compressed bitstream. As seen, the superimposition coefficients inherently generalize the MSR to various content. And using DNNs to generate distortion hypotheses essentially models the spatial priors of a local block and its underlying compression error distribution. As a result, the MSR using a small-scale convolutional neural network (CNN) model with only 5k parameters and 5 KMACs/pixel achieves 4.35% (Intra) and 2.49% (Inter) BD-Rate (Bjøntegaard Delta Rate) gains over the AV1 anchor. Ablation studies further demonstrate that the MSR can be generalized to diverse small-scale network structures, different standards (e.g., H.265/HEVC and H.266/VVC), and diverse video content (e.g., screen videos).
