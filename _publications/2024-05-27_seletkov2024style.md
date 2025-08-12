---
title: "Style Transfer and Pseudo-Label Filtering Improve Transferability in Cell Organelle Segmentation Scenarios"
collection: publications
category: conferences
permalink: /publication/2024-05-27_seletkov2024style
excerpt: 'The paper studies domain adaptation for cell organelle segmentation, where models lose over 60% accuracy on new imaging data. It evaluates unsupervised and weakly supervised methods, finding that image-level labels help. The proposed StyleFilter method leverages these labels, improving performance by 19.2% absolute Dice over naive transfer in electron microscopy adaptation.'
date: 2024-05-27
venue: 'ISBI'
paperurl: 'https://ieeexplore.ieee.org/document/10635796'
bibtexurl: 'http://simael.github.io/files/2024-05-27_seletkov2024style.bib'
authors: 'Dmitrii Seletkov, Simon Reiß, Alexander Freytag, Constantin Seibold, Rainer Stiefelhagen.'
---
Our community has experienced a lot of progress in analyzing biomedical images driven by semantic segmentation solutions. However, the insufficient ability to adapt to new data distributions limits their applicability. As an example, we observed that cell organelle segmentation models can easily drop by more than 60% in relative accuracy when applied to differently imaged cell data. While bridging this gap is possible by collecting new annotations for new data, it is highly repetitive, inefficient, and expensive. In this work, we evaluate how unsupervised and weakly supervised domain adaptation techniques can help to close this gap more efficiently. We answer the questions of how well domain adaptation techniques perform in cell organelle segmentation and whether easy-to-obtain image-level information gives specific benefits. Based on our findings, we propose StyleFilter: a simple and effective approach that uses image-level labels and leads to an observed improvement in 19.2% absolute DICE over the naive transfer baseline in electron microscopy-based domain adaptation for cell organelle segmentation.