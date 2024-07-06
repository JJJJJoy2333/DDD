---
title: "YOGA: Yet Another Geometry-based Point Cloud Compressor"
collection: papers-conference
permalink: /papers-conference/2023-10-27-YOGA-Yet Another Geometry-based Point Cloud Compressor
excerpt: 'Junteng Zhang, Tong Chen, **Dandan Ding**, and Zhan Ma'
date: 2023-10-27
venue: '31st ACM International Conference on Multimedia (ACM MM)'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3581783.3613847'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

A learning-based YOGA (Yet Another Geometry-based Point Cloud Compressor) is proposed. It is flexible, allowing for the separable lossy compression of geometry and color attributes, and variable-rate coding using a single neural model; it is high-efficiency, significantly outperforming the latest G-PCC standard quantitatively and qualitatively, e.g., 25% BD-BR gains using PCQM (Point Cloud Quality Metric) as the distortion assessment, and it is lightweight, e.g., similar runtime as the G-PCC codec, owing to the use of sparse convolution and parallel entropy coding. To this end, YOGA adopts a unified end-to-end learning-based backbone for separate geometry and attribute compression. The backbone uses a two-layer structure, where the downscaled thumbnail point cloud is encoded using G-PCC at the base layer, and upon G-PCC compressed priors, multiscale sparse convolutions are stacked at the enhancement layer to effectively characterize spatial correlations to compactly represent the full-resolution sample. In addition, YOGA integrates the adaptive quantization and entropy model group to enable variable-rate control, as well as adaptive filters for better quality restoration.