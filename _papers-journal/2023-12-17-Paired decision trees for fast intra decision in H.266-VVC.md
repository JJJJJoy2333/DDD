---
title: "Paired decision trees for fast intra decision in H. 266/VVC"
collection: papers-journal
permalink: /papers-journal/2023-12-17-Paired decision trees for fast intra decision in H266-VVC
excerpt: 'Shengrong Wen, Gongchun Ding, <strong>Dandan Ding</strong>'
date: 2023-12-17
venue: 'Displays'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0141938223001786'
citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

The Versatile Video Coding (H.266/VVC) has demonstrated significant improvements to its predecessor High-Efficiency Video Coding (H.265/HEVC) in terms of compression efficiency. One of its advancements is attributed to the introduction of the QuadTree with nested Multi-type Tree (QTMT). However, the accompanying computing complexity challenges practical applications. To this end, this paper proposes a fast encoding algorithm to accelerate the encoding process of H.266/VVC while maintaining its compression efficiency as much as possible. Essentially, the Coding Unit (CU) partition can be modeled as a classification problem, and thus conventional machine learning methods such as the decision tree can be used to solve it. Previous decision tree-based works generally use one decision tree to dyadically select one partition from a set of candidate partition modes, easily leading to a local optimum. In contrast, this work models the classification from a new viewpoint and devises Paired Decision Trees (PDT) to tackle it. Specifically, the first decision tree determines whether to divide the current CU or not, and the second decision tree further determines whether to divide the CU horizontally or vertically. However, inaccurate results in the first decision tree can be propagated to the second one, resulting in error accumulation. To address this issue, we introduce the Indeterminate Space to both decision trees and perform Rate-Distortion Optimization (RDO) on samples falling within this space. Experimental results show that compared with H.266/VVC reference software VTM-15.0, the proposed PDT method saves 52.86% encoding time on average while maintaining a small BDBR increase of only 1.36%, which significantly outperforms previous works.
