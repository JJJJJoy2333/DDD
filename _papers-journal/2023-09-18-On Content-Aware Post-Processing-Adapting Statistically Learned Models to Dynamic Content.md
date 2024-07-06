---
title: "On Content-Aware Post-Processing: Adapting Statistically Learned Models to Dynamic Content"
collection: papers-journal
permalink: /papers-journal/2023-09-18-On Content-Aware Post-Processing-Adapting Statistically Learned Models to Dynamic Content
excerpt: 'Yichi Zhang, Gongchun Ding, **Dandan Ding***, Zhan Ma, and Zhu Li'
date: 2023-09-18
venue: 'ACM Transactions on Multimedia Computing, Communications and Applications (ACM TOMM)'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3612925'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---


Learning-based post-processing methods generally produce neural models that are statistically optimal on their training datasets. These models, however, neglect intrinsic variations of local video content and may fail to process unseen content. To address this issue, this article proposes a content-aware approach for the post-processing of compressed videos. We develop a backbone network, called BackboneFormer, where a Fast Transformer using Separable Self-Attention, Spatial Attention, and Channel Attention is devised to support underlying feature embedding and aggregation. Furthermore, we introduce Meta-learning to strengthen BackboneFormer for better performance. Specifically, we propose Meta Post-Processing (Meta-PP) which leverages the Meta-learning framework to drive BackboneFormer to capture and analyze input video variations for spontaneous updating. Since the original frame is unavailable to the decoder, we devise a Compression Degradation Estimation model where a low-complexity neural model and classic operators are used collaboratively to estimate the compression distortion. The estimated distortion is then utilized to guide the BackboneFormer model for dynamic updating of weighting parameters. Experimental results demonstrate that the proposed BackboneFormer itself gains about 3.61% Bj?ntegaard delta bit-rate reduction over Versatile Video Coding in the post-processing task and "BackboneFormer + Meta-PP" attains 4.32%, costing only 50K and 61K parameters, respectively. The computational complexity of MACs is 49k/pixel and 50k/pixel, which represents only about 16% of state-of-the-art methods having similar coding gains.
