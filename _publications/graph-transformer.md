---
title: "A deep learning-based graph-transformer for whole slide image classification"
collection: publications
category: manuscripts
permalink: /publication/graph-transformer
excerpt: 'We present a Graph-Transformer (GT) based framework for processing pathology data, called GTP, that interprets morphological and spatial information at the WSI-level to predict disease grade.'
date: 2022-05-20
venue: 'IEEE Transactions on Medical Imaging'
paperurl: 'http://GSWS.github.io/files/A_Graph-Transformer_for_Whole_Slide_Image_Classification.pdf'
citation: 'Y. Zheng, R. Gindra, M. Betke, J. E. Beane, V. B. Kolachalama, A deep learning-based graph-transformer for whole slide image classification, IEEE Transactions on Medical Imaging 2022'
---

Computational pathology, which entails the analysis of digitized pathology slides, is gaining increased attention over the past few years. The sheer size of a single whole slide image (WSI) typically can exceed a gigabyte, so traditional image analysis routines may not be able to fully process all this data in an efficient fashion. Modern machine learning methods such as deep learning have allowed us to make great progress in terms of analyzing WSIs including disease classification, tissue segmentation, mutation prediction, and spatial profiling of immune infiltration. Most of these methods rely on systematic breakdown of WSIs into image patches, followed by development of deep neural networks at patch-level and integration of outcomes on these patches to create overall WSI-level estimates. While patch-based approaches catalyzed research in the field, the community has begun to appreciate the conditions in which they confer benefit and in those where they cannot fully capture the underlying pathology. For example, methods focused on identifying the presence or absence of a tumor on an WSI can be developed on patches using computationally efficient techniques such as multiple instance learning. On the other hand, if the goal is to identify the entire tumor region or capture the connectivity of the tumor microenvironment characterizing the stage of disease, then it becomes important to assess both regional and WSI-level information. There are several other scenarios where both the patch- and WSI-level features need to be identified to assess the pathology, and methods to perform such analysis are needed.
