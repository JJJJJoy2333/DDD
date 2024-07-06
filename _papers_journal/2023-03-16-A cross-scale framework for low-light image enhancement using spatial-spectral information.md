---
title: "A cross-scale framework for low-light image enhancement using spatial-spectral information"
collection: publications
permalink: /publication/2023-03-16-A cross-scale framework for low-light image enhancement using spatial-spectral information
excerpt: 'Zhang, Yichi, Hengyu Liu, and **Dandan Ding**'
date: 2023-03-16
venue: 'Computers and Electrical Engineering'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0045790623000332'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

This paper presents a spatial-spectral low-light enhancement approach based on the neural network. Considering that the Image Signal Processor (ISP) which non-linearly maps RAW data to RGB images may introduce additional noise and artifacts, we propose to conduct the enhancement task directly on RAW data. To this end, we propose a cross-scale framework to map the input low-light RAW data to visually pleasing RGB images. The cross-scale framework consists of three branches for low-level, mid-level, and high-level representations of input images. We embed paired Fast Fourier Convolution (FFC) and Transformer in each level for global and local feature analysis and aggregation. Specifically, the FFC enlarges the receptive field of our neural network, exploring the pixel correlations in the spectral space; the following Transformer uses self-attention for feature selection and aggregation in the spatial space. As a result, spatial-spectral information within an image is jointly utilized for the final fusion. Experimental results demonstrate that the proposed approach significantly outperforms state-of-the-art low-light enhancement methods in both full reference assessment metrics, including PSNR, MPSNR, and SSIM, and no-reference metrics, such as NIMA. Moreover, the proposed method produces more aesthetically pleasing RGB images than other methods.