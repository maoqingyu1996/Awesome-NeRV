# Awesome-Neural-Representation-for-Videos

A curated collection of papers, code, datasets, and other resources related to **Neural Representations for Videos (NeRV)**. This repository is primarily organized by the author for convenient reference during the preparation of a thesis, and the selected keywords reflect the author's personal perspective only and should not be regarded as authoritative references.

By [Qingyu Mao](https://scholar.google.com.hk/citations?hl=zh-CN&user=SWUKj1MAAAAJ) and [Jiacong Chen](https://scholar.google.com.hk/citations?user=34zL_BYAAAAJ&hl=zh-CN&oi=ao).

TODO:
- [x] bunny
- [x] UVG
- [ ] DAVIS
- [ ] 2024 paper


## 1. Datasets and Evaluation Metrics


|Name    |   Usage  | Link      |  Comments  | Special |
| :----: | :------: | :-------: | :------:   | :------   |
| Big Buck Bunny | Training/Testing | [Link](https://github.com/haochen-rye/NeRV/tree/master/data/bunny) | 132 frames at 720×1080 resolution | Just having Bunny is sufficient. It is commonly used for training and testing. When making improvements, it is a good choice to test first on Bunny. |
| UVG | Training/Testing | [Link](https://ultravideo.fi/dataset.html) | 3900 frames at 1920×1080 resolution | Generally, the following seven videos are used: Beauty, Bosphorus, HoneyBee, Jockey, ReadySetGo, ShakeNDry, YachtRide. This dataset should be used when fully verifying the effectiveness of the proposed method and conducting the RD compression analysis. |



## 2. Papers

### 2021-2022

| No. | Title    | Year  | Abbreviation|Published| Code     | Keywords     |
| :-- | :---------| ----- | ------------| -------- | -------- | ------------ |
| 1 | Nerv: Neural representations for videos | 2021 | NeRV | [NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2021/file/b44182379bf9fae976e6ae5996e13cd8-Paper.pdf) | [Code](https://github.com/haochen-rye/NeRV) | PE+MLP+Conv |
| 2 | E-nerv: Expedite neural video representation with disentangled spatial-temporal context | 2022 | E-NeRV | [ECCV](https://arxiv.org/pdf/2207.08132) | [Code](https://github.com/kyleleey/E-NeRV) | Spatial-temporal disentanglement |
| 3 | Miner: Multiscale implicit neural representation| 2022 | MINER | [ECCV](https://arxiv.org/pdf/2202.03532) | [Code](https://github.com/vishwa91/miner) | MLP pyramid |
| 4 | Scalable neural video representations with learnable positional features | 2022 | NVP | [NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2022/file/5297e56ac65ba2bfa70ee9fc4818c042-Paper-Conference.pdf) | [Code](https://github.com/subin-kim-cv/NVP) | Learnable positional features |
| 5 | Implicit neural video compression | 2022 | IPF | [ArXiv](https://arxiv.org/pdf/2112.11312) | ---- | pixel-wise INR, but not NeRV |

### 2023

| No. | Title    | Abbreviation|Published| Code     | Keywords     |
| :-- | :---------| ------------| -------- | -------- | ------------ |
| 1 |Hnerv: A hybrid neural representation for videos | H-NeRV | [CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Chen_HNeRV_A_Hybrid_Neural_Representation_for_Videos_CVPR_2023_paper.pdf) | [Code](https://github.com/haochen-rye/HNeRV) | AE+Hybrid representation |
| 2 |Hinerv: Video compression with hierarchical encoding-based neural representation | HiNeRV | [NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/file/e5dc475c370ff42f2f96dddf8191a40c-Paper-Conference.pdf) | [Code](https://github.com/hmkx/HiNeRV) | Hierarchical encoding |
| 3 |Dnerv: Modeling inherent dynamics via difference neural representation for videos | DNeRV | [CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhao_DNeRV_Modeling_Inherent_Dynamics_via_Difference_Neural_Representation_for_Videos_CVPR_2023_paper.pdf) | ---- | Difference representation |
| 4 |Towards scalable neural representation for diverse videos | D-NeRV | [CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/He_Towards_Scalable_Neural_Representation_for_Diverse_Videos_CVPR_2023_paper.pdf) | [Code](https://github.com/boheumd/D-NeRV) | Improving generalization ability |
| 5 |Ffnerv: Flow-guided frame-wise neural representations for videos | FFNeRV | [ACM MM](https://arxiv.org/pdf/2212.12294) | [Code](https://github.com/maincold2/FFNeRV) | Flow-guided representation |
| 6 |Nirvana: Neural implicit representations of videos with adaptive networks and autoregressive patch-wise modeling | Nirvana | [CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Maiya_NIRVANA_Neural_Implicit_Representations_of_Videos_With_Adaptive_Networks_and_CVPR_2023_paper.pdf) | todo | Adaptive networks + AR modeling |
| 7 |Ps-nerv: Patch-wise stylized neural representations for videos | PS-NeRV | [ICIP](https://arxiv.org/pdf/2208.03742) | ---- | Patch-wise representation |
| 8 |Video compression with entropy-constrained neural representations | EC-NeRV* | [CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Gomes_Video_Compression_With_Entropy-Constrained_Neural_Representations_CVPR_2023_paper.pdf) | ---- | RD + Entropy modeling |
| 9 |Scene matters: Model-based deep video compression | MVC | [ICCV](https://openaccess.thecvf.com/content/ICCV2023/papers/Tang_Scene_Matters_Model-based_Deep_Video_Compression_ICCV_2023_paper.pdf) | ---- | Added some scene constraints |
| 10 |GNeRV: A Global Embedding Neural Representation For Videos | GNeRV | [openreview](https://openreview.net/pdf?id=kMOHMk1h0Y) | ---- | Global embedding |

The asterisk (*) in the "Abbreviation" column denotes that the author of the article did not provide predefined abbreviations; the abbreviations listed were formulated by the present team based on the characteristics of the proposed method.

### 2024


| No. | Title    | Abbreviation|Published| Code     | Keywords     |
| :-: | :---------| ------------| -------- | -------- | ------------ |
1 | C3: High-performance and low-complexity neural compression from a single image or video | C3 | [CVPR](https://openaccess.thecvf.com/content/CVPR2024/papers/Kim_C3_High-Performance_and_Low-Complexity_Neural_Compression_from_a_Single_Image_CVPR_2024_paper.pdf) | [Code](https://github.com/google-deepmind/c3_neural_compression) | High-performance compression |
2 | NVRC: Neural video representation compression | NVRC | [NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2024/file/eed57814c16645298db3164829e2e45c-Paper-Conference.pdf) | ---- | Video compression |
3 | Boosting neural representations for videos with a conditional decoder | BoostNeRV | [CVPR](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_Boosting_Neural_Representations_for_Videos_with_a_Conditional_Decoder_CVPR_2024_paper.pdf) | [Code](https://github.com/Xinjie-Q/Boosting-NeRV) | Improving generalization ability |
4 | Snerv: Spectra-preserving neural representation for video | Snerv | [ECCV](https://arxiv.org/pdf/2501.01681?) | [Code](https://github.com/qwertja/SNeRV) | Spectra-preserving compression |
5 | Ds-nerv: Implicit neural video representation with decomposed static and dynamic codes | Ds-NeRV | [CVPR](https://openaccess.thecvf.com/content/CVPR2024/papers/Yan_DS-NeRV_Implicit_Neural_Video_Representation_with_Decomposed_Static_and_Dynamic_CVPR_2024_paper.pdf) | [Maybe](https://haoyan14.github.io/DS-NeRV/) | Decomposed static and dynamic codes |
6 | Qs-nerv: Real-time quality-scalable decoding with neural representation for videos | Qs-NeRV | [ACM MM](https://openreview.net/pdf?id=vJbyT9bYgf) | ---- | Quality-scalable decoding |
7 | Fast encoding and decoding for implicit video representation | FastNeRV | [ECCV](https://arxiv.org/pdf/2409.19429?) | [Code](https://github.com/haochen-rye/FastNeRV) | Fast encoding and decoding |
8 | Latent-inr: A flexible framework for implicit representations of videos with discriminative semantics | Latent-INR | [ECCV](https://arxiv.org/pdf/2408.02672) | ---- | Discriminative semantics |
9 | Pnerv: Enhancing spatial consistency via pyramidal neural representation for videos | PNeRV | [CVPR](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhao_PNeRV_Enhancing_Spatial_Consistency_via_Pyramidal_Neural_Representation_for_Videos_CVPR_2024_paper.pdf) | ---- | Pyramidal representation |
10 | Combining frame and gop embeddings for neural video representation | T-NeRV | [CVPR](https://openaccess.thecvf.com/content/CVPR2024/papers/Saethre_Combining_Frame_and_GOP_Embeddings_for_Neural_Video_Representation_CVPR_2024_paper.pdf) | ---- | Combining frame and gop embeddings |
11 | Vq-nerv: A vector quantized neural representation for videos | VQ-NeRV | [Arxiv](https://arxiv.org/pdf/2403.12401) | [Maybe](https://github.com/magicffourier/VQ-NeRV) | Vector quantized representation |
12 | Parameter-efficient instance-adaptive neural video compression | PEVC | [ACCV](https://openaccess.thecvf.com/content/ACCV2024/papers/Oh_Parameter-Efficient_Instance-Adaptive_Neural_Video_Compression_ACCV_2024_paper.pdf) | [Code](https://github.com/ohsngjun/PEVC) | Parameter-efficient instance-adaptive compression |
13 | Cool-chic video: Learned video coding with 800 parameters | Cool-Chic | [DCC](https://arxiv.org/pdf/2402.03179) | [Code](https://github.com/Orange-OpenSource/Cool-Chic) | Learned video coding |
14 | Res-nerv: Residual blocks for a practical implicit neural video decoder | Res-NeRV | [ICIP](https://ieeexplore.ieee.org/abstract/document/10647402) | ---- | Residual blocks |
15 | HFS-HNeRV: High-Frequency Spectrum Hybrid Neural Representation for Videos | HFS-HNeRV | [ACM MM](https://dl.acm.org/doi/pdf/10.1145/3696409.3700250) | ---- | High-Frequency Spectrum Hybrid Representation |
16 | Nerv++: An enhanced implicit neural video representation | Nerv++ | [VCIP](https://arxiv.org/pdf/2402.18305) | ---- | Dynamic codes |
17 | Efficient Neural Video Representation with Temporally Coherent Modulation | NVTM | [ECCV](https://arxiv.org/pdf/2505.00335?) | ---- | Temporally coherent modulation |
18 | VQNeRV: Vector Quantization Neural Representation for Video Compression | VQNeRV | [ISCAS](https://ieeexplore.ieee.org/abstract/document/10558613) | ---- | Vector quantized representation |
19 | Quality Scalable Video Coding Based on Neural Representation | QSVCNR | [ICMM](https://link.springer.com/chapter/10.1007/978-3-031-53305-1_30) | ---- | Quality-scalable compression |
20 | PET-NeRV: Bridging Generalized Video Codec and Content-Specific Neural Representation | PET-NeRV | [VCIP](https://ieeexplore.ieee.org/abstract/document/10849907) | ---- | Bridging generalized video codec and content-specific neural representation |
21 | NeRVA: Joint Implicit Neural Representations for Videos and Audios | NeRVA | [ICME](https://ieeexplore.ieee.org/abstract/document/10687669) | ---- | Joint implicit neural representations for videos and audios |
22 | PNeRV: A Polynomial Neural Representation for Videos | PNeRV | [Arxiv](https://arxiv.org/pdf/2406.19299?) | ---- | Polynomial neural representation |
23 | SNeRV: Scalable Neural Representations for Video Coding | SNeRV | [NeurIPS Workshop](https://openreview.net/pdf?id=ZqN4bnXSSY) | ---- | Scalable neural representations |

### 2025

| Title    | Year  | Abbreviation|Published| Code     | Keywords     |
| :---------| ----- | ------------| -------- | -------- | ------------ |
































