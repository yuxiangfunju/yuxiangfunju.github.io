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

I am currently an Associate Professor (Research Fellow)、Doctoral Supervisor (博导) in School of Integrated Circuits (集成电路学院), Nanjing University. In 2018, I joined the School of Electronic Science and Engineering, Nanjing University.

I received the B.S. degree in microelectronics and solid state electronics and the Ph.D. degree in electronic science and technology from Nanjing University, Nanjing, China, in 2013 and 2018, respectively.

My research interest includes AI for chip architecture design automation, NoC-based multi-core architectures, high energy efficiency AI chip design, reconfigurable computing, and 3D IC design. My papers are published in prestigious international journals (such as IEEE TC/TCAD/TCAS-I/TVLSI/TCAS-II/IEEE SENSORS JOURNAL) and proceedings (such as ASP-DAC, ICCD, CASES, ISCAS, BioCas). I have been authorized 55 patents.

Everyone is welcome to apply for master and doctoral students！ 欢迎大家报考硕士研究生和博士研究生！

Contact E-mail: yuxiangfu@nju.edu.cn

<!--# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->

# 📝 Publications 

<!--<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**-->
- Optimizing Mixed-Precision DNN Scheduling on Heterogeneous Socs for Enhanced Robustness and Efficiency, AICAS, 2025
- FAS-NoC: A Real-time Fused Approximation Scheme Coordinating Communication and Computation for NoC-Based NN Accelerators, IEEE Transactions on Circuits and Systems I: Regular Papers, 2025
- LT-OAQ: Learnable Threshold based Outlier-Aware Quantization and its Energy-Efficient Accelerator for Low-Precision On-Chip Training，DATE，2025
- Compact Interleaved Thermal Control for Improving Throughput and Reliability of Networks-on-Chip, ASP-DAC 2025
- Four-class EEG Classification for Seizure Prediction and Detection Using a Lightweight CNN-LSTM, BioCAS 2024
- An index-free sparse neural network with 2D semiconductor ferroelectric field-effect transistors, Nature Electronics
- An Energy Efficient Residual Spiking Neural Network Accelerator with Ternary Spikes，IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2024
- Automatic Generation and Optimization Framework of NoC-Based Neural Network Accelerator Through Reinforcement Learning， IEEE Transactions on Computers, 2024
- Communication Synchronization-aware Arbitration Policy in NoC-based DNN Accelerators, IEEE Transactions on Circuits and Systems II: Express Briefs, 2024
- TTNNM: Thermal- and Traffic-Aware Neural Network Mapping on 3D-NoC-based Accelerator, GLSVLSI 2024
- HAS-RL: A Hierarchical Approximate Scheme Optimized with Reinforcement Learning for NoC-based NN Accelerators, IEEE Transactions on Circuits and Systems I: Regular Papers, 2024
- A General Methodology and Reconfigurable Architecture for Calculating AB-Like Functions in the Complex Field, IEEE Transactions on Circuits and Systems II: Express Briefs, 2023
- A NoC-Based Spatial DNN Inference Accelerator with Memory-Friendly Dataflow, IEEE Design & Test, 2023
- Low-Cost High-Precision Architecture for Arbitrary Floating-Point Nth Root Computation, ISCAS, 2023
- A DSP-purposed REconfigurable Acceleration Machine (DREAM) for High Energy Efficiency MIMO Signal Processing, IEEE Transactions on Circuits and Systems I: Regular Papers, 2022
- A Nearest-Neighbor-based Thermal Sensor Allocation and Temperature Reconstruction Method for 3D NoC-based Multicore Systems, IEEE SENSORS JOURNAL, 2022
- Deep Spiking Neural Network with Ternary Spikes, BIOCAS, 2022
- AOME: Autonomous Optimal Mapping Exploration Using Reinforcement Learning for NoC-Based Accelerators Running Neural Networks, ICCD, 2022
- ACAC: An Adaptive Congestion-aware Approximate Communication Mechanism for Network-on-Chip Systems, CASES, 2022
- Unsupervised Learning Based on Temporal Coding Using STDP in Spiking Neural Networks, ISCAS, 2022
- A Hierarchical Parallel Discrete Gaussian Sampler for Lattice-Based Cryptography, ISCAS, 2022
- An Energy Efficient STDP-Based SNN Architecture With On-Chip Learning, C Sun, H Sun, J Xu, J Han, X Wang, X Wang, Q Chen, Y Fu, L Li, IEEE Transactions on Circuits and Systems I: Regular Papers, 2022
- Cerebron: A Reconfigurable Architecture for Spatio-Temporal Sparse Spiking Neural Networks, Q Chen, C Gao, Y Fu, IEEE Transactions on Very Large Scale Integration (VLSI) Systems, 2022
- Low-Latency Low-Complexity Method and Architecture for Computing Arbitrary Nth Root of Complex Numbers, R Wu, H Chen, G He, Y Fu, L Li, IEEE Transactions on Circuits and Systems I: Regular Papers, 2022
- Huicore: A Generalized Hardware Accelerator for Complicated Functions, H Chen, Z Yu, J Xu, L Jiang, Z Lu, Y Fu, L Li, IEEE Transactions on Circuits and Systems I: Regular Papers 69 (6),	2022
- Low-Latency Architecture for Implementing Floating-Point Multiplier and Divider Based on Symmetric-Mapping LUT, H Yang, H Chen, Y Fu, L Li, 2021 18th International SoC Design Conference (ISOCC), 2021
- A Low-Complexity Architecture for Implementing Square to Tenth Root of Complex Numbers, J Xu, L Jiang, H Chen, Y Fu, L Li, 2021 18th International SoC Design Conference (ISOCC),	2021
- LSTM-based Temperature Prediction and Hotspot Tracking for Thermal-aware 3D NoC System, T Cheng, H Du, L Li, Y Fu, 2021 18th International SoC Design Conference (ISOCC), 2021
- Optimized Method for Thermal Tracking in 3D NoC Systems by Using ANN, M Guo, T Cheng, L Li, Y Fu, 2021 18th International SoC Design Conference (ISOCC), 2021
- 2β-softmax: A Hardware-Friendly Activation Function with Low Complexity and High Performance, Y Zhang, H Chen, Y Fu, L Li, 2021 18th International SoC Design Conference (ISOCC), 2021
- A 67.5 μJ/prediction accelerator for spiking neural networks in image segmentation, Q Chen, G He, X Wang, J Xu, S Shen, H Chen, Y Fu, L Li, IEEE Transactions on Circuits and Systems II: Express Briefs 69 (2), 2021
- Low-complexity high-precision method and architecture for computing the logarithm of complex numbers, H Chen, Z Yu, Y Zhang, Z Lu, Y Fu, L Li, IEEE Transactions on Circuits and Systems I: Regular Papers 68 (8), 2021
- Adaptive Successive Cancellation Priority Decoder for 5G Polar Codes, W Song, Y Shen, Y Fu, C Zhang, L Li, 2021 IEEE International Symposium on Circuits and Systems (ISCAS), 2021
- A general methodology and architecture for arbitrary complex number Nth root computation, H Chen, R Wu, Z Lu, Y Fu, L Li, Z Yu, 2021 IEEE International Symposium on Circuits and Systems (ISCAS), 2021
- Dynamic and Traffic-Aware Medium Access Control Mechanisms for Wireless NoC Architectures, Q Gao, W Song, Z Lu, L Li, Y Fu, 2021 IEEE International Symposium on Circuits and Systems (ISCAS), 1-5		2021
- Symmetric-Mapping LUT-Based Method and Architecture for Computing XY-Like Functions, H Chen, H Yang, W Song, Z Lu, Y Fu, L Li, Z Yu, IEEE Transactions on Circuits and Systems I: Regular Papers 68 (3), 1231-1244, 2021
- Optimizing Vertical Link Placement and Congestion Aware Dynamic Elevator Assignment for Partially Connected 3D-NoCs, Y Fu, C Zhang, W Song, Q Chen, H Chen, M Zhou, L Li, IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems,	2020
- Hardware implementation of random forest algorithm based on classification and regression tree, Z Teng, L Chu, K Chen, G He, Y Fu, L Li, 2020 IEEE International Conference on Information Technology, Big Data and Artificial Intelligence (ICIBA),	2020
- An Efficient Hardware Architecture with Adjustable Precision and Extensible Range to Implement Sigmoid and Tanh Functions, H Chen, L Jiang, H Yang, Z Lu, Y Fu, L Li, Z Yu, Electronics 9 (10), 2020
- A CORDIC-based architecture with adjustable precision and flexible scalability to implement sigmoid and tanh functions, H Chen, L Jiang, Y Luo, Z Lu, Y Fu, L Li, Z Yu, 2020 IEEE International Symposium on Circuits and Systems (ISCAS), 1-5, 2020
- An efficient software list sphere decoder for polar codes, H Zhou, Y Fu, Z Zhang, WJ Gross, X You, C Zhang, Journal of Signal Processing Systems 92 (5), 517-528, 2020
- An efficient accelerator for multiple convolutions from the sparsity perspective, Q Chen, Y Huang, R Sun, W Song, Z Lu, Y Fu, L Li, IEEE Transactions on Very Large Scale Integration (VLSI) Systems,	2020
- Hyperbolic CORDIC-based architecture for computing logarithm and its implementation, H Chen, K Cheng, Z Lu, Y Fu, L Li, IEEE Transactions on Circuits and Systems II: Express Briefs 67 (11), 2652-2656, 2020
- ANN based adaptive successive cancellation list decoder for polar codes, W Song, Y Fu, Q Chen, L Li, C Zhang, 2019 IEEE 13th International Conference on ASIC (ASICON), 1-4, 2019
- Congestion-aware dynamic elevator assignment for partially connected 3D-NoCs, Y Fu, Q Chen, G He, K Chen, Z Lu, C Zhang, L Li, 2019 IEEE International Symposium on Circuits and Systems (ISCAS), 1-5, 2019
- Smilodon: An efficient accelerator for low bit-width CNNs with task partitioning, Q Chen, Y Fu, K Cheng, W Song, Z Lu, L Li, C Zhang, 2019 IEEE International Symposium on Circuits and Systems (ISCAS), 1-5,	2019
- Joint detection and decoding of polar-coded OFDM-IDMA systems, X Deng, J Sha, X Zhou, Y Fu, Z Zhang, X You, C Zhang, IEEE Transactions on Circuits and Systems I: Regular Papers 66 (10), 4005-4017,	2019
- An efficient hardware accelerator for the MUSIC algorithm, H Chen, K Chen, K Cheng, Q Chen, Y Fu, L Li, Electronics 8 (5), 511, 2019
- An Efficient Streaming Accelerator for Low Bit-Width Convolutional Neural Networks, Q Chen, Y Fu, W Song, K Cheng, Z Lu, C Zhang, L Li, Electronics 8 (4), 371, 2019
- Thermal sensor placement and thermal reconstruction under Gaussian and non-Gaussian sensor noises for 3-D NoC, Y Fu, L Li, H Pan, K Wang, F Feng, Q Chen, C Zhang, IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems,	2018
- Design and application space exploration of a domain-specific accelerator system, F Feng, L Li, K Wang, Y Fu, G He, H Pan, Electronics 7 (4), 45, 2018
- Kalman predictor-based proactive dynamic thermal management for 3-D NoC systems with noisy thermal sensors, Y Fu, L Li, K Wang, C Zhang, IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems,	2017
- Accurate runtime thermal prediction scheme for 3D NoC systems with noisy thermal sensors, Y Fu, L Li, H Pan, K Wang, F Han, J Lin, 2016 IEEE International Symposium on Circuits and Systems (ISCAS), 1198-1201, 2016
- Lateral asynchronous and vertical synchronous 3D Network on Chip with double pumped vertical links, Y Fu, L Li, Y Zhang, H Pan, F Han, K Wang, 2015 IEEE 11th International Conference on ASIC (ASICON), 1-4, 2015
- Exploring stacked main memory architecture for 3D GPGPUs, Y Zhang, L Li, A Jantsch, Z Lu, M Gao, Y Fu, H Pan, 2015 IEEE 11th International Conference on ASIC (ASICON), 1-4, 2015
- Performance and network power evaluation of tightly mixed SRAM NUCA for 3D multi-core network on chips, Y Zhang, L Li, Z Lu, A Jantsch, Y Fu, M Gao, 2014 IEEE International Symposium on Circuits and Systems (ISCAS), 1961-1964, 2014

# 🎖 Honors and Awards
- First Prize of Jiangsu Provincial Science and Technology Awards, 2023
- National-level Young Talent
- Jiangsu Innovation and Entrepreneurship Doctor
- Suzhou Innovation and Entrepreneurship Leading Talent
- Xiaomi Young Scholar - Science and Technology Innovation Award

# 📖 Educations
- *2013.09 - 2018.12*, Ph.D. degree in electronic science and technology, Nanjing University. 
- *2009.09 - 2013.06*, B.S. degree in microelectronics and solid state electronics, Nanjing University.

<!--# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)-->

<a href="https://info.flagcounter.com/Oymw"><img src="https://s01.flagcounter.com/mini/Oymw/bg_FFFFFF/txt_000000/border_CCCCCC/flags_0/" alt="Flag Counter" border="0"></a>
