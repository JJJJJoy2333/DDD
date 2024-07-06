---
title: "Learning-Based Multi-Frame Video Quality Enhancement"
collection: papers-conference
permalink: /papers-conference/2019-09-24-Learning-Based Multi-Frame Video Quality Enhancement
excerpt: 'Junchao Tong, Xilin Wu, **Dandan Ding**, Zheng Zhu, and Zoe Liu'
date: 2019-09-24
venue: 'IEEE International Conference on Image Processing (ICIP)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/8803786'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Convolution neural network (CNN) has shown its great success in video quality enhancement. Existing methods mainly conduct enhancement tasks in the spatial domain, exploring the pixel correlations within one frame. Taking advantage of the similarity across successive frames, this paper develops a learning-based multi-frame approach, with an aim to explore the greatest potential for video quality enhancement leveraging the temporal correlation. First, we apply a learning-based optical flow to compensate the temporal motion across neighboring frames. Afterwards, a deep CNN network, which is structured in an early-fusion manner, is designed to discover the joint spatial-temporal correlations within a video. To ensure the generality of our CNN model, we further propose a robust training strategy. One high-quality frame and one moderate-quality frame are paired to enhance the remaining low-quality frames in between, which considers a trade-off between frame distances and various frame quality. Experimental results demonstrate that our method outperforms state-of-the-art work in objective quality. The code and model of our approach are published in Github (https://github.com/IVC-Projects/LMVE).