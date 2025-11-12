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

| Title    | Year  | Abbreviation|Published| Code     | Keywords     |
| :---------| ----- | ------------| -------- | -------- | ------------ |
Nerv: Neural representations for videos | 2021 | NeRV | [NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2021/file/b44182379bf9fae976e6ae5996e13cd8-Paper.pdf) | [Code](https://github.com/haochen-rye/NeRV) | PE+MLP+Conv |
E-nerv: Expedite neural video representation with disentangled spatial-temporal context | 2022 | E-NeRV | [ECCV](https://arxiv.org/pdf/2207.08132) | [Code](https://github.com/kyleleey/E-NeRV) | Spatial-temporal disentanglement |
Miner: Multiscale implicit neural representation| 2022 | MINER | [ECCV](https://arxiv.org/pdf/2202.03532) | [Code](https://github.com/vishwa91/miner) | MLP pyramid |
Scalable neural video representations with learnable positional features | 2022 | NVP | [NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2022/file/5297e56ac65ba2bfa70ee9fc4818c042-Paper-Conference.pdf) | [Code](https://github.com/subin-kim-cv/NVP) | Learnable positional features |
Implicit neural video compression | 2022 | IPF | [ArXiv](https://arxiv.org/pdf/2112.11312) | ---- | pixel-wise INR, but not NeRV |

### 2023

| Title    | Year  | Abbreviation|Published| Code     | Keywords     |
| :---------| ----- | ------------| -------- | -------- | ------------ |
Hnerv: A hybrid neural representation for videos | 2023 | H-NeRV | [CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Chen_HNeRV_A_Hybrid_Neural_Representation_for_Videos_CVPR_2023_paper.pdf) | [Code](https://github.com/haochen-rye/HNeRV) | AE+Hybrid representation |
Hinerv: Video compression with hierarchical encoding-based neural representation | 2023 | HiNeRV | [NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/file/e5dc475c370ff42f2f96dddf8191a40c-Paper-Conference.pdf) | [Code](https://github.com/hmkx/HiNeRV) | Hierarchical encoding |
Dnerv: Modeling inherent dynamics via difference neural representation for videos | 2023 | DNeRV | [CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhao_DNeRV_Modeling_Inherent_Dynamics_via_Difference_Neural_Representation_for_Videos_CVPR_2023_paper.pdf) | ---- | Difference representation |
Towards scalable neural representation for diverse videos | 2023 | D-NeRV | [CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/He_Towards_Scalable_Neural_Representation_for_Diverse_Videos_CVPR_2023_paper.pdf) | [Code](https://github.com/boheumd/D-NeRV) | Improving generalization ability |
Ffnerv: Flow-guided frame-wise neural representations for videos | 2023 | FFNeRV | [ACM MM](https://arxiv.org/pdf/2212.12294) | [Code](https://github.com/maincold2/FFNeRV) | Flow-guided representation |
Nirvana: Neural implicit representations of videos with adaptive networks and autoregressive patch-wise modeling | 2023 | Nirvana | [CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Maiya_NIRVANA_Neural_Implicit_Representations_of_Videos_With_Adaptive_Networks_and_CVPR_2023_paper.pdf) | todo | Adaptive networks + AR modeling |
Ps-nerv: Patch-wise stylized neural representations for videos | 2023 | PS-NeRV | [ICIP](https://arxiv.org/pdf/2208.03742) | ---- | Patch-wise representation |
Video compression with entropy-constrained neural representations | 2023 | EC-NeRV* | [CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Gomes_Video_Compression_With_Entropy-Constrained_Neural_Representations_CVPR_2023_paper.pdf) | ---- | RD + Entropy modeling |
Scene matters: Model-based deep video compression | 2023 | MVC | [ICCV](https://openaccess.thecvf.com/content/ICCV2023/papers/Tang_Scene_Matters_Model-based_Deep_Video_Compression_ICCV_2023_paper.pdf) | ---- | Added some scene constraints |
GNeRV: A Global Embedding Neural Representation For Videos | 2023 | GNeRV | [openreview](https://openreview.net/pdf?id=kMOHMk1h0Y) | ---- | Global embedding |

The asterisk (*) in the "Abbreviation" column denotes that the author of the article did not provide predefined abbreviations; the abbreviations listed were formulated by the present team based on the characteristics of the proposed method.

### 2024


| Title    | Year  | Abbreviation|Published| Code     | Keywords     |
| :---------| ----- | ------------| -------- | -------- | ------------ |



























