---
title: "From Driver Talk To Future Action: Vehicle Maneuver Prediction by Learning from Driving Exam Dialogs"
collection: publications
category: conferences
permalink: /publication/2021-07-11_roitberg2021driver
excerpt: 'This paper proposes an automated method to predict driver intentions from YouTube mock road test videos and dialogs, avoiding costly labels. By detecting and filtering out casual smalltalk, our approach improves prediction accuracy using cleaner conversation data.'
date: 2021-07-11
venue: 'IV'
paperurl: 'https://ieeexplore.ieee.org/document/9575655'
bibtexurl: 'http://simael.github.io/files/2021-07-11_roitberg2021driver.bib'
authors: 'Alina Roitberg, Simon Reiß, Rainer Stiefelhagen.'
---
A rapidly growing amount of content posted online inherently holds knowledge about concepts of interest, i.e. driver actions. We leverage methods at the intersection of vision and language to surpass costly annotation and present the first automated framework for anticipating driver intention by learning from recorded driving exam conversations. We query YouTube and collect a dataset of posted mock road tests comprising student-teacher dialogs and video data, which we use for learning to foresee the next maneuver without any additional supervision. However, instructional conversations give us very loose labels, while casual chat results in a high amount of noise. To mitigate this effect, we propose a technique for automatic detection of smalltalk based on the likelihood of spoken words being present in everyday dialogs. While visually recognizing driver's intention by learning from natural dialogs only is a challenging task, learning from less but better data via our smalltalk refinement consistently improves performance.