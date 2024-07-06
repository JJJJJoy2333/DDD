---
title: "Real-Time H.265/HEVC Intra Encoding with a Configurable Architecture on FPGA Platform"
collection: papers-journal
permalink: /papers-journal/2019-09-01-Real-Time H.265-HEVC Intra Encoding with a Configurable Architecture on FPGA Platform
excerpt: '<strong>Dandan Ding</strong>, WANG Silong, LIU Zoe, and YUAN Qingshu'
date: 2019-09-01
venue: 'Chinese Journal of Electronics'
paperurl: 'https://ietresearch.onlinelibrary.wiley.com/doi/abs/10.1049/cje.2019.06.020'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---


This paper proposes a flexible design scheme for H.265/HEVC encoding based on FPGA, which allows an easy incorporation of a variety of algorithms applied to different scenarios. In particular, we present an H.265/HEVC intra encoder as an instantiation of our proposed scheme. The key idea is to develop an encoder system by configuring basic Processing elements (PEs) of fundamental algorithms. Our intra encoder using the flexible framework is structured with fourstage CTU based pipeline. Pixel-level PEs are designed to unify the intra prediction of 35 modes and a multiscale compatible transform array is proposed to process variable size transform. 32 PEs are paralleled for intra mode decision to support 35 combinations of modes and partitions. In the reconstruction stage, 16 PEs are paralleled for intra prediction and a 16 x 16 multiplier array is configured for transforms of variable sizes with a constant 16 pixels/cycle throughput. Implementation results show that our proposed architecture costs about 63K Lookup tables and 62KB on-chip memories on Xilinx Kintex-7 platform with the maximum working frequency at 175MHz, which is sufficient for real-time encoding of 1920 x 1080 @60fps video at 160MHz. The flexibility and extension capability of our framework provides a great potential for future FPGA solutions serving for different purposes.
