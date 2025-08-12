---
title: "Delivering arbitrary-modal semantic segmentation"
collection: publications
category: conferences
permalink: /publication/2023-06-21_zhang2023delivering
excerpt: 'This paper presents DeLiVER, a benchmark for arbitrary-modal semantic segmentation across Depth, LiDAR, multiple Views, Events, and RGB, with variations for severe weather and sensor failures. It introduces CMNeXt, a flexible fusion model with a Self-Query Hub and Parallel Pooling Mixer, enabling scaling from 1 to 81 modalities with minimal extra parameters. CMNeXt achieves state-of-the-art results on six datasets, with up to +9.10% mIoU gain on DeLiVER over the RGB-only baseline.'
date: 2023-06-21
venue: 'CVPR'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2023/html/Zhang_Delivering_Arbitrary-Modal_Semantic_Segmentation_CVPR_2023_paper.html'
bibtexurl: 'http://simael.github.io/files/2023-06-21_zhang2023delivering.bib'
authors: 'Jiaming Zhang, Ruiping Liu, Hao Shi, Kailun Yang, Simon Reiß, Kunyu Peng, Haodong Fu, Kaiwei Wang, Rainer Stiefelhagen.'
---
Multimodal fusion can make semantic segmentation more robust. However, fusing an arbitrary number of modalities remains underexplored. To delve into this problem, we create the DeLiVER arbitrary-modal segmentation benchmark, covering Depth, LiDAR, multiple Views, Events, and RGB. Aside from this, we provide this dataset in four severe weather conditions as well as five sensor failure cases to exploit modal complementarity and resolve partial outages. To facilitate this data, we present the arbitrary cross-modal segmentation model CMNeXt. It encompasses a Self-Query Hub (SQ-Hub) designed to extract effective information from any modality for subsequent fusion with the RGB representation and adds only negligible amounts of parameters ( 0.01M) per additional modality. On top, to efficiently and flexibly harvest discriminative cues from the auxiliary modalities, we introduce the simple Parallel Pooling Mixer (PPX). With extensive experiments on a total of six benchmarks, our CMNeXt achieves state-of-the-art performance, allowing to scale from 1 to 81 modalities on the DeLiVER, KITTI-360, MFNet, NYU Depth V2, UrbanLF, and MCubeS datasets. On the freshly collected DeLiVER, the quad-modal CMNeXt reaches up to 66.30% in mIoU with a +9.10% gain as compared to the mono-modal baseline. 