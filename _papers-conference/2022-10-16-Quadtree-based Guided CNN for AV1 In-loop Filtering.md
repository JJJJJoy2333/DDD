---
title: "Quadtree-based Guided CNN for AV1 In-loop Filtering"
collection: papers-conference
permalink: /papers-conference/2022-10-16-Quadtree-based Guided CNN for AV1 In-loop Filtering
excerpt: 'Junjie Wang, Gongchun Ding, **Dandan Ding**, Debargha Mukherjee, Urvang Joshi, Yue Chen'
date: 2022-10-16
venue: '2022 IEEE International Conference on Image Processing (ICIP)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9897898'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Recently, learning-based in-loop filtering has attracted lots of attention. State-of-the-art works generally deploy computationally expensive, large-scale neural networks, which is unfriendly to practical applications. Besides, since these models are generally pre-trained using a limited dataset and applied to various videos, they may fail in video contents excluded in the training dataset. To address these issues, this paper develops a Guide CNN in-loop filtering framework to obtain the restored signal. Our basic idea is to construct a subspace and use the projection of the original signal into this subspace to approximate the original signal itself. Specifically, we employ CNN to transform the degraded signal into M subsignals to construct the optimal subspace since the training of CNN is essentially an optimization procedure. Furthermore, unlike existing CNN models that process all blocks uniformly, our method leverages a quadtree structure to implement the Guided CNN through R-D optimization. As such, the best partition to Guided CNN can be determined. We exemplify the proposed method in AV1 codec. Experimental results show that the Guided CNN framework achieves 2.19% and 1.31% BD-Rate gains over the AV1 anchor in intra and inter coding mode, respectively, while the normal CNN achieves only 1.64% and 1.04%.