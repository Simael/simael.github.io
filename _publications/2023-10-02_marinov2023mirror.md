---
title: "Mirror U-Net: Marrying Multimodal Fission with Multi-Task Learning for Semantic Segmentation in Medical Imaging"
collection: publications
category: conferences
permalink: /publication/2023-10-02_marinov2023mirror
excerpt: 'This paper introduces Mirror U-Net, a PET/CT tumor segmentation model that replaces traditional fusion with multimodal fission, splitting features into modality-specific and shared decoders. This setup combines fission and multi-task learning to strengthen unimodal features while preserving multimodal ones. Evaluated on AutoPET and MSD BrainTumor, Mirror U-Net achieves state-of-the-art performance. Code is publicly available.'
date: 2023-10-02
venue: 'ICCV Workshops'
paperurl: 'https://openaccess.thecvf.com/content/ICCV2023W/CVAMD/html/Marinov_Mirror_U-Net_Marrying_Multimodal_Fission_with_Multi-Task_Learning_for_Semantic_ICCVW_2023_paper.html'
bibtexurl: 'http://simael.github.io/files/2023-10-02_marinov2023mirror.bib'
authors: 'Zdravko Marinov, Simon Reiß, David Kersting, Jens Kleesiek, Rainer Stiefelhagen.'
---
Positron Emission Tomography (PET) and Computed Tomography (CT) are routinely used together to detect tumors. PET/CT segmentation models can automate tumor delineation, however, current multimodal models do not fully exploit the complementary information in each modality, as they either concatenate PET and CT data or fuse them at the decision level. To combat this, we propose Mirror U-Net, which replaces traditional fusion methods with multimodal fission by factorizing the multimodal representation into modality-specific decoder branches and an auxiliary multimodal decoder. At these branches, Mirror U-Net assigns a task tailored to each modality to reinforce unimodal features while preserving multimodal features in the shared representation. In contrast to previous methods that use either fission or multi-task learning, Mirror U-Net combines both paradigms in a unified framework. We explore various task combinations and examine which parameters to share in the model. We evaluate Mirror U-Net on the AutoPET PET/CT and on the multimodal MSD BrainTumor datasets, demonstrating its effectiveness in multimodal segmentation and achieving state-of-the-art performance on both datasets. Code: [https://github.com/Zrrr1997/autoPET_challenge_mirrorUNet](https://github.com/Zrrr1997/autoPET_challenge_mirrorUNet)