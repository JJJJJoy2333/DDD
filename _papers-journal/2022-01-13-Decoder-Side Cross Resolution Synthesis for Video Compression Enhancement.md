---
title: "Decoder-Side Cross Resolution Synthesis for Video Compression Enhancement"
collection: papers-journal
permalink: /papers-journal/2022-01-13-Decoder-Side Cross Resolution Synthesis for Video Compression Enhancement
excerpt: 'Ming Lu, Tong Chen, Zhenyu Dai, Dong Wang, **Dandan Ding**, and Zhan Ma '
date: 2022-01-13
venue: 'IEEE Transactions on Multimedia'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9681152'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

This paper proposes a decoder-side Cross Resolution Synthesis (CRS) module to pursue better compression efficiency beyond the latest Versatile Video Coding (VVC), where we encode intra frames at original high resolution (HR), compress inter frames at a lower resolution (LR), and then super-resolve decoded LR inter frames with the help from preceding HR intra and neighboring LR inter frames. For a LR inter frame, a motion alignment and aggregation network (MAN) is devised to produce temporally aggregated motion representation to best guarantee the temporal smoothness; Another texture compensation network (TCN) is utilized to generate texture representation from decoded HR intra frame for better augmenting spatial details; Finally, a similarity-driven fusion engine synthesizes motion and texture representations to upscale LR inter frames for the removal of compression and resolution re-sampling noises. We enhance the VVC using proposed CRS, showing averaged 8.76% and 11.93% Bjøntegaard Delta Rate (BD-Rate) gains against the latest VVC anchor in Random Access (RA) and Low-delay P (LDP) settings respectively. In addition, experimental comparisons to the state-of-the-art super-resolution (SR) based VVC enhancement methods, and ablation studies are conducted to further report superior efficiency and generalization of the proposed algorithm. All materials will be made to public at https://njuvision.github.io/CRS for reproducible research.