---
title: "Decoupled Semantic Prototypes Enable Learning From Diverse Annotation Types for Semi-Weakly Segmentation in Expert-Driven Domains"
collection: publications
category: conferences
permalink: /publication/2023-06-21_reiss2023decoupled
excerpt: 'This paper addresses segmentation in expert-driven domains with scarce pixel-wise annotations, evaluating existing methods for handling diverse annotation types. Finding current approaches limited, it proposes Decoupled Semantic Prototypes (DSP), a method that learns from image-level, point, box, and pixel annotations, achieving notable accuracy gains in semi-weakly supervised organelle segmentation.'
date: 2023-06-21
venue: 'CVPR'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2023/html/Reiss_Decoupled_Semantic_Prototypes_Enable_Learning_From_Diverse_Annotation_Types_for_CVPR_2023_paper.html'
bibtexurl: 'http://simael.github.io/files/2023-06-21_reiss2023decoupled.bib'
authors: 'Simon Reiß, Constantin Seibold, Alexander Freytag, Erik Rodner, Rainer Stiefelhagen.'
---
A vast amount of images and pixel-wise annotations allowed our community to build scalable segmentation solutions for natural domains. However, the transfer to expert-driven domains like microscopy applications or medical healthcare remains difficult as domain experts are a critical factor due to their limited availability for providing pixel-wise annotations. To enable affordable segmentation solutions for such domains, we need training strategies which can simultaneously handle diverse annotation types and are not bound to costly pixel-wise annotations. In this work, we analyze existing training algorithms towards their flexibility for different annotation types and scalability to small annotation regimes. We conduct an extensive evaluation in the challenging domain of organelle segmentation and find that existing semi- and semi-weakly supervised training algorithms are not able to fully exploit diverse annotation types. Driven by our findings, we introduce Decoupled Semantic Prototypes (DSP) as a training method for semantic segmentation which enables learning from annotation types as diverse as image-level-, point-, bounding box-, and pixel-wise annotations and which leads to remarkable accuracy gains over existing solutions for semi-weakly segmentation.