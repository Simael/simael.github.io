---
title: "Accurate Fine-Grained Segmentation of Human Anatomy in Radiographs via Volumetric Pseudo-Labeling"
collection: publications
category: conferences
permalink: /publication/2023-06-06_seibold2023accurate
excerpt: 'This paper proposes using 3D CT-based pseudo-labeling to train fine-grained anatomical segmentation models for chest X-rays without manual annotations. From 10,021 thoracic CTs with 157 labels, 3D segmentations are projected to 2D, enabling high-accuracy CXR models with mIoU up to 0.93 and strong agreement with radiologists. The method supports explainable clinical measures like cardio-thoracic ratio and could aid thoracic pathology analysis.'
date: 2023-06-06
venue: 'arXiv, technical report'
paperurl: 'https://arxiv.org/abs/2306.03934'
bibtexurl: 'http://simael.github.io/files/2023-06-06_seibold2023accurate.bib'
authors: 'Constantin Seibold, Alexander Jaus, Matthias A. Fink, Moon Kim, Simon Reiß, Ken Herrmann, Jens Kleesiek, Rainer Stiefelhagen.'
---
Purpose: Interpreting chest radiographs (CXR) remains challenging due to the ambiguity of overlapping structures such as the lungs, heart, and bones. To address this issue, we propose a novel method for extracting fine-grained anatomical structures in CXR using pseudo-labeling of three-dimensional computed tomography (CT) scans.
Methods: We created a large-scale dataset of 10,021 thoracic CTs with 157 labels and applied an ensemble of 3D anatomy segmentation models to extract anatomical pseudo-labels. These labels were projected onto a two-dimensional plane, similar to the CXR, allowing the training of detailed semantic segmentation models for CXR without any manual annotation effort.
Results: Our resulting segmentation models demonstrated remarkable performance on CXR, with a high average model-annotator agreement between two radiologists with mIoU scores of 0.93 and 0.85 for frontal and lateral anatomy, while inter-annotator agreement remained at 0.95 and 0.83 mIoU. Our anatomical segmentations allowed for the accurate extraction of relevant explainable medical features such as the cardio-thoracic-ratio.
Conclusion: Our method of volumetric pseudo-labeling paired with CT projection offers a promising approach for detailed anatomical segmentation of CXR with a high agreement with human annotators. This technique may have important clinical implications, particularly in the analysis of various thoracic pathologies.