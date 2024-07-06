---
title: "A progressive CNN in-loop filtering approach for inter frame coding"
collection: papers-journal
permalink: /papers-journal/2021-05-17-A progressive CNN in-loop filtering approach for inter frame coding
excerpt: '**Dandan Ding**, Lingyi Kong, Wenyu Wang, and Fengqing Zhu'
date: 2021-05-17
venue: 'Signal Processing: Image Communication'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0923596521000321'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Convolutional Neural Network (CNN) structures have been designed for in-loop filtering to improve video coding performance. These CNN models are usually trained through learning the correlations between the reconstructed and the original frames, which are then applied to every single reconstructed frame to improve the overall video quality. This direct model training and deployment strategy is effective for intra coding since a locally optimal model is sufficient. However, when applied to inter coding, it causes over-filtering because the intertwined reference dependencies across inter frames are not taken into consideration. To address this issue, existing methods usually resort to the Rate-Distortion Optimization (RDO) to selectively apply the CNN model, but fail to address the limitation of using a local CNN model. In this paper, we propose a progressive approach to train and incorporate the CNN-based in-loop filters to work seamlessly with video encoders. First, we develop a progressive training method to obtain the inter model. Using transfer learning, reconstructed frames using the CNN model are progressively involved back into the training of the CNN model itself, to simulate the reference dependencies in inter coding. Next, we design a frame-level model selection strategy for the high-bitrate coding where the over-filtering effect is diluted. Experimental results show that the proposed method outperforms the RDO method that utilizes only local model. Proposed approach also achieves comparable coding performance but with less computational complexity when integrating our progressive model into the RDO scheme.