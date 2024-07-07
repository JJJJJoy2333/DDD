---
title: "Lossless Point Cloud Attribute Compression Using Cross-scale, Cross-group, and Cross-color Prediction"
collection: papers-conference
permalink: /papers-conference/2023-03-21-Lossless Point Cloud Attribute Compression Using Cross-scale, Cross-group, and Cross-color Prediction
excerpt: 'Jianqiang Wang, <strong>Dandan Ding</strong>, and Zhan Ma'
date: 2023-03-21
venue: 'IEEE Data Compression Conference (DCC)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10125514'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

This work extends the multiscale structure originally developed for point cloud geometry compression to point cloud attribute compression. To losslessly encode the attribute while maintaining a low bitrate, accurate probability prediction is critical. With this aim, we extensively exploit cross-scale, cross-group, and cross-color correlations of point cloud attribute to ensure accurate probability estimation and thus high coding efficiency. Specifically, we first generate multiscale attribute tensors through average pooling, by which, for any two consecutive scales, the decoded lower-scale attribute can be used to estimate the attribute probability in the current scale in one shot. Additionally, in each scale, we perform the probability estimation group-wisely following a predefined grouping pattern. In this way, both cross-scale and (same-scale) cross-group correlations are exploited jointly. Furthermore, cross-color redundancy is removed by allowing inter-color processing for YCoCg/RGB alike multi-channel attributes. The proposed method not only demonstrates state-of-the-art compression efficiency with significant performance gains over the latest G-PCC on various contents but also sustains low complexity with affordable encoding and decoding runtime.
