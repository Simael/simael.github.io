---
title: "Foreign object segmentation in chest x-rays through anatomy-guided shape insertion"
collection: publications
category: conferences
permalink: /publication/2025-01-21_seibold2025foreign
excerpt: 'The paper addresses instance segmentation of foreign objects in chest X-rays, where data scarcity hinders training. It generates synthetic data by inserting shapes or cut-pasted labels with anatomically guided placement. This method matches fully supervised performance while using 93% fewer manual annotations.'
date: 2025-01-21
venue: 'arXiv, technical report'
paperurl: 'https://arxiv.org/abs/2501.12022'
bibtexurl: 'http://simael.github.io/files/2025-01-21_seibold2025foreign.bib'
authors: 'Constantin Seibold, Hamza Kalisch, Lukas Heine, Simon Reiß, Jens Kleesiek.'
---
In this paper, we tackle the challenge of instance segmentation for foreign objects in chest radiographs, commonly seen in postoperative follow-ups with stents, pacemakers, or ingested objects in children. The diversity of foreign objects complicates dense annotation, as shown in insufficient existing datasets. To address this, we propose the simple generation of synthetic data through (1) insertion of arbitrary shapes (lines, polygons, ellipses) with varying contrasts and opacities, and (2) cut-paste augmentations from a small set of semi-automatically extracted labels. These insertions are guided by anatomy labels to ensure realistic placements, such as stents appearing only in relevant vessels. Our approach enables networks to segment complex structures with minimal manually labeled data. Notably, it achieves performance comparable to fully supervised models while using 93\% fewer manual annotations. 