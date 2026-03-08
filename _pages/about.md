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

I am currently a professor at the School of Information Science and Technology, Hangzhou Normal University, and lead the Intelligent Video Coding (IVC) Lab. My research focuses on advanced visual media representation and processing, with particular emphasis on image and video coding, point cloud compression, 3D representation and reconstruction, and hardware AI accelerators . 

I have published over 90 high-quality papers in leading journals and conferences, including Proceedings of the IEEE, TPAMI, TIP, TVCG, TCSVT, TMM, etc., as well as top conferences such as CVPR, ICML, AAAI, IJCAI, and ACM MM. I have been actively engaged in international video coding standardization activities since 2007. My early contributions included work on MPEG Reconfigurable Video Coding (RVC), and in 2011, I was awarded the MPEG Appreciation Prize in recognition of my work in RVC. 

I am a IEEE Senior Member and maintain active involvement in the IEEE Signal Processing Society and the IEEE Circuits and Systems Society. I served as Organizing Co-Chair of the ICME Workshop in 2023 and as International Liaison Co-Chair for the IEEE MMSP in 2024. I currently serve as an Associate Editor for IEEE Signal Processing Letters (SPL).



# 🔥 News <a href="{{ '/news/' | relative_url }}" target="_self" style="text-decoration: underline; margin-left: 10px; font-weight: bold; background-color: #eee; padding: 0 4px; border-radius: 3px;">more news</a>

<ul style="list-style-type: disc; margin-left: 20px; line-height: 1.8;">
  <li><strong>2026.01</strong>: &nbsp;📢 Serving as <strong>Area Chair</strong> for <strong>ICASSP 2026</strong> and <strong>ICME 2026</strong>.</li>
  <li><strong>2025.10</strong>: &nbsp;📄 Paper on "GeoQE" (Point Cloud Streaming) accepted by <strong>ACM MM 2025</strong>.</li>
  <li><strong>2025.07</strong>: &nbsp;🎉 One paper on LiDAR reflectance compression accepted by <strong>ICML 2025</strong>.</li>
  <li><strong>2025.06</strong>: &nbsp;🚀 Presented "Reno" (Real-time Neural Compression) at <strong>CVPR 2025</strong>.</li>
  <li><strong>2025.01</strong>: &nbsp;📑 Research on Multiscale Point Cloud Compressor published in <strong>IEEE TPAMI</strong>.</li>

  <div id="more-news" style="display: none;">
    <li><strong>2024.12</strong>: &nbsp;📢 Serving as <strong>Area Chair</strong> for <strong>MMSP 2025</strong>.</li>
    <li><strong>2024.06</strong>: &nbsp;🏆 Paper "ELIM" nominated as **Best Paper Award Finalist</strong> at <strong>IEEE PCS 2024</strong>.</li>
    <li><strong>2023.10</strong>: &nbsp;📄 Two papers on G-PCC++ and YOGA accepted by <strong>ACM MM 2023</strong>.</li>
    <li><strong>2020.12</strong>: &nbsp;🏫 Promoted to <strong>Professor</strong> and lead the <strong>IVC Lab</strong> at Hangzhou Normal University.</li>
  </div>
</ul>

  

<span class='anchor' id='publications'></span>

# 📝 Publications <a href="{{ '/publications/' | relative_url }}" target="_self" style="text-decoration: underline; font-weight: bold; background-color: #eee; padding: 0 4px; border-radius: 3px;">more publications</a>
<div class="slide-group">
  
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT 2025</div><img src='images/Improving Occupancy Prediction for Multiscale Point Cloud Geometry Compression.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Improving Occupancy Prediction for Multiscale Point Cloud Geometry Compression](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11289509)   
Zehong Li, Jiahao Zhu, **Dandan Ding***, Zhan Ma
- We propose two new techniques. The first is KPA (Key Point-driven Attention), which integrates both local and global characteristics. The second is AdaScale (Adaptive Lossy/Lossless Scale), which decides whether the transitional scale should be in lossless or lossy mode based on temporal displacement, thereby enhancing the reconstruction quality of the temporal reference.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TVCG 2025</div><img src='images/Revisit Point Cloud Quality Assessment Current Advances and a Multiscale-Inspired Approach.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Revisit Point Cloud Quality Assessment: Current Advances and a Multiscale-Inspired Approach](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11048499)   
Junzhe Zhang, Tong Chen, **Dandan Ding***, Zhan Ma
- We paper proposes PQI, a simple yet efficient metric to index point cloud quality. PQI suggests using scale-wise key points to uniformly perceive distortions within a point cloud, along with a mild neighborhood size associated with each key point for compromised N2N computation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMM 2025</div><img src='images/Scalable Point Cloud Attribute Compression.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Scalable Point Cloud Attribute Compression](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10313579)   
Junzhe Zhang, Jianqiang Wang, **Dandan Ding***, Zhan Ma
- We develops a Scalable Point Cloud Attribute Compression solution, termed ScalablePCAC. In a two-layer example, ScalablePCAC uses the standard G-PCC at the base layer to directly encode the thumbnail point cloud that is downscaled from the original input, and a learning-based model at the enhancement layer to compress and restore the full-resolutioninput point cloud conditioned on the base layer reconstruction.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2025</div><img src='/images/GeoQE Enhancing Quality of Experience in Point Cloud Streaming.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[GeoQE: Enhancing Quality of Experience in Point Cloud Streaming](https://dl.acm.org/doi/epdf/10.1145/3746027.3754909)   
Junzhe Zhang, Chengfeng Han, **Dandan Ding***, Zhan Ma
- we propose GeoQE, an enhancement model that seamlessly integrates with the G-PCC decoder to mitigate compression artifacts and improve QoE.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='/images/Efficient LiDAR Reflectance Compression via Scanning Serialization.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Efficient LiDAR Reflectance Compression via Scanning Serialization](https://arxiv.org/pdf/2505.09433)  
Jiahao Zhu, Kang You, **Dandan Ding***, Zhan Ma
- We introduce SerLiC, a serialization-based neural compression frame work to fully exploit the intrinsic characteristics of LiDAR reflectance.
</div>
</div>

<!--
<div style="text-align: right; width: 100%; margin-top: -10px;">
    <a href="{{ '/publications/' | relative_url }}" style="text-decoration: none; font-weight: bold; background-color: #eee; padding: 2px 10px; border-radius: 3px; font-size: 0.9em; color: #333;">
      View More Publications ...
    </a>
  </div>
-->
</div>



<!--
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
-->



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
