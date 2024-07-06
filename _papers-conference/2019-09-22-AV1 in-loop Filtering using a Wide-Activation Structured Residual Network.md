---
title: "AV1 in-loop Filtering using a Wide-Activation Structured Residual Network"
collection: papers-conference
permalink: /papers-conference/2019-09-22-AV1 in-loop Filtering using a Wide-Activation Structured Residual Network
excerpt: 'Guangyao Chen, **Dandan Ding**, Debargha Mukherjee, Urvang Joshi, and Yue Chen'
date: 2019-09-22
venue: 'IEEE International Conference on Image Processing (ICIP)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/8803127'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

The in-loop filter, which constitutes an important part in modern video coding, improves both subjective and objective quality of reconstructed frames. Lately, Convolutional Neural Network (CNN) has demonstrated its superiority over traditional methods in addressing in-loop filtering problem. In this paper, we develop a CNN-based in-loop filter, namely Wide Activation Residual Network (WARN), for AV1 encoder. On top of the plain Residual Network (ResNet), we introduce wide activation to each residual block, making a more reasonable allocation of network parameters. When incorporating WARN into video encoder, particular to inter coding, it is intricate to obtain the global optimum performance. After simplifying this as an end-to-end trainable problem, we propose a skipping method by taking advantage of the hierarchical reference structure in AV1. Experimental results show that our WARN achieves up to 14.42% and 9.64% BD-rate reduction in intra and inter coding, respectively. All the code and model of our approach are available at https://github.com/IVC-Projects/AV1_WARN.