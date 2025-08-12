---
title: "Breaking with fixed set pathology recognition through report-guided contrastive training"
collection: publications
category: conferences
permalink: /publication/2022-09-16_seibold2022breaking
excerpt: 'This paper tackles the limitation of fixed-category supervision in radiology image classification by using direct text supervision from unstructured medical reports. It introduces a contrastive global-local dual-encoder to learn concepts without relying on predefined labels, enabling open set recognition and better use of weakly annotated data. Evaluated on large chest X-ray datasets, the approach matches performance of traditional label-supervised methods while allowing free-form classification.'
date: 2022-09-16
venue: 'MICCAI'
paperurl: 'https://arxiv.org/abs/2205.07139'
bibtexurl: 'http://simael.github.io/files/2022-09-16_seibold2022breaking.bib'
authors: 'Constantin Seibold, Simon Reiß, M. Saquib Sarfraz, Rainer Stiefelhagen, Jens Kleesiek.'
---
When reading images, radiologists generate text reports describing the findings therein. Current state-of-the-art computer-aided diagnosis tools utilize a fixed set of predefined categories automatically extracted from these medical reports for training. This form of supervision limits the potential usage of models as they are unable to pick up on anomalies outside of their predefined set, thus, making it a necessity to retrain the classifier with additional data when faced with novel classes. In contrast, we investigate direct text supervision to break away from this closed set assumption. By doing so, we avoid noisy label extraction via text classifiers and incorporate more contextual information.
We employ a contrastive global-local dual-encoder architecture to learn concepts directly from unstructured medical reports while maintaining its ability to perform free form classification.
We investigate relevant properties of open set recognition for radiological data and propose a method to employ currently weakly annotated data into training.
We evaluate our approach on the large-scale chest X-Ray datasets MIMIC-CXR, CheXpert, and ChestX-Ray14 for disease classification. We show that despite using unstructured medical report supervision, we perform on par with direct label supervision through a sophisticated inference setting.