---
title: "A method for detecting text of arbitrary shapes in natural scenes that improves text spotting"
collection: publications
category: manuscripts
permalink: /publication/uhta
excerpt: 'UHT, short for UNet, Heatmap, and Textfill, uses a UNet to compute heatmaps for candidate text regions and a textfill algorithm to produce tight polygonal boundaries around each word in the candidate text.'
date: 2019-11-16
venue: 'Computer Vision and Pattern Recognition Workshop'
paperurl: 'http://GSWS.github.io/files/A_Method_for_Detecting_Text_of_Arbitrary_Shapes_in_Natural_CVPRW_2020_paper.pdf'
citation: 'Q. Wang, Y. Zheng, and M. Betke, A method for detecting text of arbitrary shapes in natural scenes that improves text spotting, Computer Vision and Pattern Recognition Workshop 2020'
---
Understanding the meaning of text in images of natural scenes like highway signs or store front emblems is particularly challenging if the text is foreshortened in the image or the letters are artistically distorted. We introduce a pipeline-based text spotting framework that can both detect and recognize text in various fonts, shapes, and orientations in natural scene images with complicated backgrounds. The main contribution of our work is the text detection component, which we call UHT, short for UNet, Heatmap, and Textfill. UHT uses a UNet to compute heatmaps for candidate text regions and a textfill algorithm to produce tight polygonal boundaries around each word in the candidate text. Our method trains the UNet with groundtruth heatmaps that we obtain from text bounding polygons provided by groundtruth annotations. Our text spotting framework, called UHTA, combines UHT with the state-of-the-art text recognition system ASTER. Experiments on four challenging and public scene-text-detection datasets (Total-Text, SCUT-CTW1500, MSRA-TD500, and COCO-Text) show the effectiveness and generalization ability of UHT in detecting not only multilingual (potentially rotated) straight but also curved text in scripts of multiple languages. Our experimental results of UHTA on the TotalText dataset show that UHTA outperforms four state-of-theart text spotting frameworks by at least 9.1 percent points in the F-measure, which suggests that UHTA may be used as a complete text detection and recognition system in real applications.
