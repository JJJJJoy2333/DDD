---

permalink: /

title: ""

excerpt: ""

author_profile: true

redirect_from: 

  - /about/

  - /about.html

---



{% if site.google_scholar_stats_use_cdn %}

{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}

{% else %}

{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}

{% endif %}

{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 👨‍🎓 About Me

I am a Professor at the School of Information Science and Engineering, Hangzhou Normal University, where I lead the Intelligent Video Coding (IVC) Lab. My research primarily focuses on the cutting-edge fields of visual data compression and multimedia communication.



Specifically, my work explores next-generation visual compression technologies, including AV2 and MPEG AI-based point cloud/3DGS compression, as well as their real-time system implementations on NPU and FPGA platforms. Since 2018, I have been continuously supported by Google’s Chrome University Relationship Program to advance the development of the AV2 standard.



I am an IEEE Senior Member and currently serve as an Associate Editor for IEEE Signal Processing Letters. Over the years, I have actively contributed to international standardization, notably receiving the ISO/IEC Appreciation Prize in 2011 for my leadership in MPEG activities.



# 🔥 News

- *2026.01*: &nbsp;📢 Serving as **Area Chair** for **ICASSP 2026** and **ICME 2026**.

- *2025.10*: &nbsp;📄 Paper on "GeoQE" (Point Cloud Streaming) accepted by **ACM MM 2025**.

- *2025.07*: &nbsp;🎉 One paper on LiDAR reflectance compression accepted by **ICML 2025**.

- *2025.06*: &nbsp;🚀 Presented "Reno" (Real-time Neural Compression) at **CVPR 2025**.

- *2025.01*: &nbsp;📑 Research on Multiscale Point Cloud Compressor published in **IEEE TPAMI**.

- *2024.12*: &nbsp;📢 Serving as **Area Chair** for **MMSP 2025**.

- *2024.06*: &nbsp;🏆 Paper "ELIM" nominated as **Best Paper Award Finalist** at **IEEE PCS 2024**.

- *2023.10*: &nbsp;📄 Two papers on G-PCC++ and YOGA accepted by **ACM MM 2023**.

- *2020.12*: &nbsp;🏫 Promoted to **Professor** and lead the **IVC Lab** at Hangzhou Normal University.

  

<span class='anchor' id='publications'></span>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT 2023</div><img src='images/Neural Adaptive Loop Filtering for Video Coding Exploring Multi-Hypothesis Sample Refinement.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Neural Adaptive Loop Filtering for Video Coding: Exploring Multi-Hypothesis Sample Refinement](https://ieeexplore.ieee.org/abstract/document/10078282)  
**Dandan Ding**, Junjie Wang, Guangkun Zhen, Debargha Mukherjee, Urvang Joshi, Zhan Ma
- We reformulate ALF as a Multi-Hypothesis Sample Refinement (MSR) problem, using a DNN model to generate multiple distortion hypotheses that are linearly superimposed to approximate the final reconstruction.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2023</div><img src='images/Sparse Tensor-based Multiscale Representation for Point Cloud Geometry Compression.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Sparse Tensor-based Multiscale Representation for Point Cloud Geometry Compression](https://ieeexplore.ieee.org/abstract/document/9968173)  
Jianqiang Wang, **Dandan Ding**, Zhu Li, Xiaoxing Feng, Chuntong Cao, Zhan Ma
- We propose SparsePCGC, a low-complexity multiscale representation that performs sparse convolutions only on most-probable positively-occupied voxels to characterize spatial correlations efficiently.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Proc. IEEE 2021</div><img src='images/Advances In Video Compression System Using Deep Neural Network.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Advances In Video Compression System Using Deep Neural Network: A Review And Case Studies](https://ieeexplore.ieee.org/abstract/document/9369668)  
**Dandan Ding**, Zhan Ma, Di Chen, Qingshuang Chen, Zoe Liu, Fengqing Zhu
- This article extensively reviews technical advances in video compression using deep neural networks, presenting case studies on semantic pre-processing, end-to-end neural coding, and neural adaptive post-processing.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP 2021</div><img src='images/Neural Reference Synthesis for Inter Frame Coding.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Neural Reference Synthesis for Inter Frame Coding](https://ieeexplore.ieee.org/abstract/document/9658260)  
**Dandan Ding**, Xiang Gao, Chenran Tang, Zhan Ma
- We propose a Neural Reference Synthesis (NRS) framework with joint optimization of reconstruction enhancement and reference synthesis modules to improve both in-ring filtering and inter-frame prediction.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCyb 2022</div><img src='images/Biprediction-Based Video Quality Enhancement via Learning.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Biprediction-Based Video Quality Enhancement via Learning](https://ieeexplore.ieee.org/abstract/document/9119800)  
**Dandan Ding**, Wenyu Wang, Junchao Tong, Xinbo Gao, Zoe Liu, Yong Fang
- We develop a biprediction-based multiframe video enhancement (PMVE) framework that synthesizes virtual frames to extract cross-correlations between successive frames for high-accuracy quality restoration.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT 2021</div><img src='images/Point Cloud Upsampling via Perturbation Learning.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Point Cloud Upsampling via Perturbation Learning](https://ieeexplore.ieee.org/abstract/document/9493165)  
**Dandan Ding**, Chi Qiu, Fuchang Liu, Zhigeng Pan
- We propose learning 2D perturbations through MLPs to estimate coordinate shifts from sparse input points to upsampled dense points, outperforming state-of-the-art methods in geometric uniformity.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/exploit contextual clustering in learned image coding.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Another way to the top: exploit contextual clustering in learned image coding](https://ojs.aaai.org/index.php/AAAI/article/view/28791)  
Yichi Zhang, Zhihao Duan, Ming Lu, **Dandan Ding**, Fengqing Zhu, Zhan Ma
- We propose Contextual Clustering based LIC (CLIC), which relies on clustering operations and local attention instead of traditional convolutions to generate compact representations for image compression.
</div>
</div>

## Journal Papers
- Improving Occupancy Prediction for Multiscale Point Cloud Geometry Compression, Z. Li, J. Zhu, D. Ding*, Z. Ma, IEEE TCSVT 2025 
- Revisit Point Cloud Quality Assessment: Current Advances and a Multiscale-Inspired Approach, J. Zhang, T. Chen, D. Ding*, Z. Ma, IEEE TVCG 2025 
- ConPCAC: Conditional Lossless Point Cloud Attribute Compression via Spatial Decomposition, J. Zhang, T. Chen, K. You, D. Ding*, Z. Ma, IEEE TCSVT 2025 
- DeepPCC: Learned Lossy Point Cloud Compression, J. Zhang, G. Liu, J. Zhang, D. Ding*, Z. Ma, IEEE TETCI 2025 
- Learning to Restore Compressed Point Cloud Attribute: A Fully Data-Driven Approach and a Rules-Unrolling-Based Optimization, J. Zhang, J. Zhang, D. Ding*, Z. Ma, IEEE TVCG 2025 
- Scalable Point Cloud Attribute Compression, J. Zhang, J. Wang, D. Ding*, Z. Ma, IEEE TMM 2025 
- A Versatile Point Cloud Compressor Using Universal Multiscale Conditional Coding – Part I: Geometry, J. Wang, R. Xue, J. Li, D. Ding, Y. Lin, Z. Ma*, IEEE TPAMI 2025 
- A Versatile Point Cloud Compressor Using Universal Multiscale Conditional Coding – Part II: Attribute, J. Wang, R. Xue, J. Li, D. Ding, Y. Lin, Z. Ma*, IEEE TPAMI 2025 
- Content-aware Rate Control for Geometry-based Point Cloud Compression, J. Zhang, J. Zhang, W. Ma, D. Ding*, Z. Ma, IEEE TCSVT 2024 
- GRNet: Geometry Restoration for G-PCC Compressed Point Clouds Using Auxiliary Density Signaling, G. Liu, R. Xue, J. Li, D. Ding*, Z. Ma, IEEE TVCG 2024 
- Neural Adaptive Loop Filtering for Video Coding: Exploring Multi-hypothesis Sample Refinement, D. Ding, J. Wang, G. Zhen, D. Mukherjee, U. Joshi, Z. Ma*, IEEE TCSVT 2023 
- Sparse Tensor-Based Multiscale Representation for Point Cloud Geometry Compression, J. Wang, D. Ding, Z. Li, X. Feng, C. Cao, Z. Ma*, IEEE TPAMI 2022 
- Neural Reference Synthesis for Inter Frame Coding, D. Ding*, X. Gao, C. Tang, Z. Ma, IEEE TIP 2022 
- Bi-prediction Based Video Quality Enhancement via Learning, D. Ding, W. Wang, X. Gao, Z. Liu, Y. Fang*, IEEE TCyb 2022 
- Advances in Video Compression Systems Using Deep Neural Networks: A Review and Case Studies, D. Ding, Z. Ma, D. Chen, Q. Chen, Z. Liu, F. Zhu*, Proc. IEEE 2021 
- Point Cloud Upsampling via Perturbation Learning, D. Ding, C. Qiu, F. Liu, Z. Pan*, IEEE TCSVT 2021

## Conference Papers
- GeoQE: Enhancing Quality of Experience in Point Cloud Streaming, J. Zhang, C. Han, D. Ding*, Z. Ma, ACM MM 2025 
- Efficient LiDAR Reflectance Compression via Scanning Serialization, J. Zhu, K. You, D. Ding*, Z. Ma, ICML 2025
- Reno: Real-time Neural Compression for 3D LiDAR Point Clouds, K. You, T. Chen, D. Ding, M. S. Asif, Z. Ma, CVPR 2025 
- Compressing 3D Gaussian Splatting via a Generalizable Neural Coder, J. Zhang, T. Chen, H. Zhu, D. Wang, D. Ding, Z. Ma, IEEE VCIP 2024 
- ELIM: Extremely Low-Complexity Implicit Neural Model for Super Resolution-Based Coding, W. Wang, J. Wang, D. Ding*, IEEE PCS 2024 (Best Paper Award Finalist) 
- Encoding Auxiliary Information to Restore Compressed Point Cloud Geometry, G. Liu, J. Zhu, D. Ding*, Z. Ma, IJCAI 2024 
- Another Way to the Top: Exploit Contextual Clustering in Learned Image Coding, Y. Zhang, Z. Duan, M. Lu, D. Ding*, F. Zhu, Z. Ma, AAAI 2024 
- YOGA: Yet Another Geometry-based Point Cloud Compressor, J. Zhang, T. Chen, D. Ding*, Z. Ma, ACM MM 2023 
- G-PCC++: Enhanced Geometry-based Point Cloud Compression, J. Zhang, T. Chen, D. Ding*, Z. Ma, ACM MM 2023
- Lossless Point Cloud Attribute Compression Using Cross-scale, Cross-group, and Cross-color Prediction, J. Wang, D. Ding, Z. Ma, IEEE DCC 2023 
- Low-Light Raw Image Enhancement Using Paired Fast Fourier Convolution and Transformer, Y. Zhang, H. Liu, D. Ding*, Z. Ma, IEEE VCIP 2022 
- PCGFormer: Lossy Point Cloud Geometry Compression via Local Self-Attention, G. Liu, J. Wang, D. Ding*, Z. Ma, IEEE VCIP 2022 
- Quadtree-based Guided CNN for AV1 In-loop Filtering, J. Wang, G. Ding, D. Ding*, D. Mukherjee, U. Joshi, Y. Chen, IEEE ICIP 2022 
- Multiscale Point Cloud Geometry Compression, J. Wang, D. Ding, Z. Li, Z. Ma*, IEEE DCC 2021 
- Guided CNN Restoration with Explicitly Signaled Linear Combination, L. Kong, D. Ding*, D. Mukherjee, U. Joshi, Y. Chen, IEEE ICIP 2020




# 🎖 Honors and Awards

- *2024.06* Best Paper Award Finalist, IEEE PCS 2024.

- *2011.06* ISO/IEC Appreciation Prize, for leadership in MPEG standardization.



# 📖 Educations

- *2006.09 - 2011.06*, **Zhejiang University**, China. Ph.D. in Communication and Information System.

- *2007.07 - 2008.05*, **EPFL**, Switzerland. Joint Ph.D. program in GR-LSM.

- *2002.09 - 2006.06*, **Zhejiang University**, China. B.S. in Communication Engineering.

  

<span class='anchor' id='professional-experience'></span>

# 💻 Professional Experience

- *2020.12 - Present*, **Professor**, Hangzhou Normal University. Lead IVC lab.

- *2015.12 - 2020.11*, **Assistant Professor**, Hangzhou Normal University.

- *2013.07 - 2015.11*, **Assistant Professor**, Zhejiang University.

