---
title: "Low Light RAW Image Enhancement Using Paired Fast Fourier Convolution and Transformer"
collection: papers-conference
permalink: /papers-conference/2022-12-15-Low Light RAW Image Enhancement Using Paired Fast Fourier Convolution and Transformer
excerpt: 'Yichi Zhang, Hengyu Liu, <strong>Dandan Ding</strong>, Zhan Ma'
date: 2022-12-15
venue: '2022 IEEE International Conference on Visual Communications and Image Processing (VCIP), Suzhou, China'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10008898'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Compared to RGB images non-linearly mapped from RAW data through the Image Signal Processor (ISP), RAW data are linear to scene radiance and contain more native information, which is better to be modeled in many vision tasks. This work proposes to enhance low-light images in the RAW domain via a cross-scale framework using paired Fast Fourier Convolution (FFC) and Transformer, driving the network to characterize images effectively. The entire framework has three scales to abstract low-level, mid-level, and high-level representations of input images. We embed paired FFC and Transformer in each scale to attain spatial-spectral information extraction and aggregation. Specifically, by transforming features from the spatial domain into the spectral domain with FFC, pixel correlations can be effectively exploited locally and globally, generating representative features for the input image. Immediately, the Transformer using multi-head self-attention mechanism is applied to aggregate and embed important features. Experimental results demonstrate that our method significantly outperforms state-of-the-art low-light enhancement works in both full reference assessment metrics, including PSNR, MPSNR, and SSIM, and no-reference metrics, such as NIMA. Meanwhile, the perceptual quality of the proposed method is more visually pleasing than that of other methods.
