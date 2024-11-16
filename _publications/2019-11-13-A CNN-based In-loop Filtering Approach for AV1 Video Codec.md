---
title: "A CNN-based In-loop Filtering Approach for AV1 Video Codec"
collection: papers-conference
permalink: /papers-conference/2019-11-13-A CNN-based In-loop Filtering Approach for AV1 Video Codec
excerpt: '<strong>Dandan Ding</strong>, Guangyao Chen, Debargha Mukherjee, Urvang Joshi, and Yue Chen'
date: 2019-11-13
venue: 'Picture Coding Symposium (PCS)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/8954565'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

In-loop filter using Convolutional Neural Network (CNN) has lately attracted lots of attention in video coding. CNN models may be trained to learn how to restore degradation introduced by compression in pictures, and hence effectively help improve the coding efficiency. State-of-the-art work in this field generally employs a single network to enhance reconstructed frames mainly in intra coding. In this paper, we develop a depth-variable network handling both intra and inter coding. The depth of our network is varied with the distortion levels of reconstructed frames. Moreover, we leverage a skip enhancing strategy for inter coding, which improves both the coding efficiency and the resulting visual quality, while maintaining low computational complexity. We apply our approach to AV1, a newly released video coding standard from AOM. Experimental results show that our approach achieves an average BD-rate reduction of 7.27% and 5.57% for intra and inter modes, respectively, compared to AV1 anchor. The code and model of our approach are published in our Github website [1].
