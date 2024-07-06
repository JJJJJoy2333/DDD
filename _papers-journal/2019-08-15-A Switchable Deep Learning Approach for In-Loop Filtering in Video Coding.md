---
title: "A Switchable Deep Learning Approach for In-Loop Filtering in Video Coding"
collection: papers-journal
permalink: /papers-journal/2019-08-15-A Switchable Deep Learning Approach for In-Loop Filtering in Video Coding
excerpt: '<strong>Dandan Ding</strong>, Lingyi Kong, Guangyao Chen, Zoe Liu, and Yong Fang*'
date: 2019-08-15
venue: 'IEEE Transactions on Circuits and Systems for Video Technology'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/8801877'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Deep learning provides a great potential for in-loop filtering to improve both coding efficiency and subjective quality in video coding. State-of-the-art work focuses on network structure design and employs a single powerful network to solve all problems. In contrast, this paper proposes a deep learning based systematic approach that includes an effective Convolutional Neural Network (CNN) structure, a hierarchical training strategy, and a video codec oriented switchable mechanism. First, we propose a novel CNN structure, i.e., Squeeze-and-Excitation Filtering CNN (SEFCNN), as an optional in-loop filter. To capture the non-linear interaction between channels, the SEFCNN is comprised of two subnets, i.e., Feature EXtracting (FEX) subnet and Feature ENhancing (FEN) subnet. Then, we develop a hierarchical model training strategy to adapt the two subnets to different coding scenarios. For high-rate videos with small artifacts, we train a single global model using the FEX for all types of frames, whereas for low-rate videos with large artifacts, different models are trained using both FEX and FEN for different types of frames. Finally, we propose an adaptive enhancing mechanism which is switchable between the CNN-based and the conventional methods. We selectively apply the CNN model to some frames or some regions in a frame. Experimental results show that the proposed scheme outperforms state-of-the-art work in coding efficiency, while the computational complexity is acceptable after GPU acceleration.
