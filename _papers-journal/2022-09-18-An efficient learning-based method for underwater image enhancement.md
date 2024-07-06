---
title: "An efficient learning-based method for underwater image enhancement"
collection: papers-journal
permalink: /papers-journal/2022-09-18-An efficient learning-based method for underwater image enhancement
excerpt: 'Zhangkai Lyu, Andrew Peng, Qingwei Wang, **Dandan Ding**'
date: 2022-09-18
venue: 'Displays'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0141938222000208'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

The Underwater image enhancement, which targets removing the noise, scattering effect, and the bluish, greenish, or yellowish tone from underwater images, has lately attracted much attention. Traditional methods generally assume some prior knowledge when performing constrained optimization. Recently, the deep neural network (DNN)-based methods have exhibited superior performance over the traditional methods. However, state-of-the-art DNN models generally cost a large number of parameters, which is unfriendly to practical implementation. By contrast, this paper proposes a simple yet effective convolution neural network (CNN)-based framework to enhance underwater images. Our method consists of two stages, CNN-based enhancement and YUV-based post-processing. In the first stage, a lightweight CNN network is developed to extract the latent features from the input image for enhancement. Specifically, our CNN cascades three residual groups which leverage channel attention blocks to strengthen the feature extraction capability. In the second stage, the output of our CNN model is transformed to the YUV color space where the luminance component is further corrected, improving the brightness of the whole image. Our model is verified on different underwater image datasets. Experimental results show that our method outperforms state-of-the-art methods both qualitatively and quantitatively. Moreover, in terms of computational complexity, our CNN model costs only 0.89M parameters which is only 21% and 81% of the existing method FUnIE-GAN and WaterNet, respectively.