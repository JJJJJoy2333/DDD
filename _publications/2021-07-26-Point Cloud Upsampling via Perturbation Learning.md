---
title: "Point Cloud Upsampling via Perturbation Learning"
collection: papers-journal
permalink: /papers-journal/2021-07-26-Point Cloud Upsampling via Perturbation Learning
excerpt: '<strong>Dandan Ding</strong>, Chi Qiu, Fuchang Liu, Zhigeng Pan*'
date: 2021-07-26
venue: 'IEEE Transactions on Circuits and Systems for Video Technology'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9493165'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Given sparse point clouds, this paper develops a perturbation learning-based point cloud upsampling method to generate uniform, clean, and dense point clouds. We build a simple yet efficient neural network framework including feature extraction, perturbation learning, and coordinate reconstruction operations. In the feature extraction task, shallow-and-wide dense connections are applied to present the latent geometric information. Subsequently, the extracted features are expanded for perturbation learning. According to the theory of the differential geometry of surfaces, the position of an upsampled point can be approximated by its projection on a tangent plane in a sufficiently small neighborhood around the point. Inspired by this, we propose learning a 2D perturbation through multilayer perceptrons (MLPs) to estimate the coordinate shift from the input point to the upsampled point. Then, we concatenate the 2D perturbation with the extracted features for residual learning to fine-tune the coordinate shift. Finally, the coordinate reconstruction step transforms all the high-level features into an upsampled and consolidated point cloud. To enable the learning-based point cloud upsampling process above, we collect a large-scale point cloud dataset that contains 36000 pairs of training sets. The entire network size is only 5.01 MB, which is much smaller than the requirements of state-of-the-art point cloud upsampling models. Qualitative and quantitative evaluation results show that our proposed scheme outperforms most existing methods in terms of the Chamfer distance (CD), Hausdorff distance (HD), Jensen-Shannon divergence (JSD), and uniformity. In addition, our method is applied to real scan data, and its robustness is confirmed.
