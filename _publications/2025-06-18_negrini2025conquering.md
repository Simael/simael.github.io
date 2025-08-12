---
title: "Conquering the Retina: Bringing Visual in-Context Learning to OCT"
collection: publications
category: conferences
permalink: /publication/2025-06-18_negrini2025conquering
excerpt: 'The paper studies visual in-context learning (VICL) for training generalist models in retinal OCT, enabling task definition on the fly without task-specific models. It proposes an evaluation protocol for VICL in OCT, establishes a baseline using multiple datasets, and releases code to support further research.'
date: 2025-06-18
venue: 'to appear at MICCAI Workshop on Efficient Medical AI'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/abs/2506.15200'
bibtexurl: 'http://simael.github.io/files/2025-06-18_negrini2025conquering.bib'
authors: 'Alessio Negrini, Simon Reiß.'
---
Recent advancements in medical image analysis have led to the development of highly specialized models tailored to specific clinical tasks. These models have demonstrated exceptional performance and remain a crucial research direction. Yet, their applicability is limited to predefined tasks, requiring expertise and extensive resources for development and adaptation. In contrast, generalist models offer a different form of utility: allowing medical practitioners to define tasks on the fly without the need for task-specific model development. In this work, we explore how to train generalist models for the domain of retinal optical coherence tomography using visual in-context learning (VICL), i.e., training models to generalize across tasks based on a few examples provided at inference time. To facilitate rigorous assessment, we propose a broad evaluation protocol tailored to VICL in OCT. We extensively evaluate a state-of-the-art medical VICL approach on multiple retinal OCT datasets, establishing a first baseline to highlight the potential and current limitations of in-context learning for OCT. To foster further research and practical adoption, we openly release our [code](https://github.com/negralessio/thesis-visual-in-context-learning).