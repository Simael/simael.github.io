---
title: "Semantic Segmentation for Preoperative Planning in Transcatheter Aortic Valve Replacement"
collection: publications
category: conferences
permalink: /publication/2025-07-22_zollner2025semantic
excerpt: 'This work supports preoperative planning for transcatheter aortic valve replacement (TAVR) by using AI-based semantic segmentation to measure relevant anatomical structures in CT scans. Fine-grained TAVR-specific pseudo-labels are derived from coarse anatomical data to train segmentation models, with a loss function adaptation improving Dice score performance by 1.27%. The pseudo-labeled dataset is publicly available at https://doi.org/10.5281/zenodo.16274176.'
date: 2025-07-22
venue: 'to appear at MICCAI Workshop on Statistical Atlases and Computational Modeling of the Heart'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/abs/2507.16573'
bibtexurl: 'http://simael.github.io/files/2025-07-22_zollner2025semantic.bib'
authors: 'Cedric Zöllner, Simon Reiß, Alexander Jaus, Amroalalaa Sholi, Ralf Sodian, Rainer Stiefelhagen.'
---
When preoperative planning for surgeries is conducted on the basis of medical images, artificial intelligence methods can support medical doctors during assessment. In this work, we consider medical guidelines for preoperative planning of the transcatheter aortic valve replacement (TAVR) and identify tasks, that may be supported via semantic segmentation models by making relevant anatomical structures measurable in computed tomography scans. We first derive fine-grained TAVR-relevant pseudo-labels from coarse-grained anatomical information, in order to train segmentation models and quantify how well they are able to find these structures in the scans. Furthermore, we propose an adaptation to the loss function in training these segmentation models and through this achieve a +1.27% Dice increase in performance. Our fine-grained TAVR-relevant pseudo-labels and the computed tomography scans we build upon are available at [https://doi.org/10.5281/zenodo.16274176](https://doi.org/10.5281/zenodo.16274176).