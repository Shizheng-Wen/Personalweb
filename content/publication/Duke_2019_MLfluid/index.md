---
abstract: Recent efforts have shown machine learning to be useful for analysis of nonlinear fluid dynamics. Predictive accuracy is often a central motivation for employing neural networks, but the pattern recognition central to the network function is equally valuable for purposes of enhancing our dynamical insight into sometimes confounding dynamics. In this paper, convolutional neural networks (CNNs) were trained to recognize several qualitatively different subsonic buffet flows over a high-incidence airfoil, and a near-perfect accuracy was performed with only a small training dataset. The convolutional kernels and corresponding feature maps, developed by the model with no temporal information provided, identified large-scale coherent structures in agreement with those known to be associated with buffet flows. Sensitivity to hyperparameters including network architecture and convolutional kernel size was explored. One conclusion is that only a small training dataset is necessary, but that smaller kernels are better at coherent structure identification than are larger kernels. An approach named Gradient-weighted Class Activation Mapping (Grad-CAM) was then applied to the trained model to indicate the importance of these feature maps in classification. Sensitivity to hyperparameters including network architecture and convolutional kernel size was also explored, and results show that smaller kernels are better at coherent structure
identification than are larger kernels. A long-short term memory CNN was then used to demonstrate that with the inclusion of temporal information, the coherent structures remained qualitatively comparable to those of the conventional CNN and less dynamically significant features were no longer recorded. The coherent structures identified by these models enhance our dynamical understanding of subsonic buffet over high-incidence airfoils over a wide range of Reynolds numbers.
author_notes:
- Corresponding Author
- 
authors:
- admin
- Michael W. Lee
- Kai M. Kruger Bastos
- Earl H. Dowell
date: "2022-09-01T00:00:00Z"
doi: ""
featured: true
image:
  caption: 'Architecture of the conventional CNN employed for buffet flow classification.'
  focal_point: ""
  preview_only: false
#links:
#- name: Custom Link
#url: https://arxiv.org/abs/2208.09663
#projects:
#- internal-project
publication: ""
publication_short: "Preprint, arxiv.org/abs/2208.09663"
publication_types:
- "3"
publishDate: "2022-09-01T00:00:00Z"
#slides: example
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.
tags:
- Fluid Mechanics
- Machine Learning
title: Feature identification in complex fluid flows by convolutional neural networks.
url_code: ''
url_dataset: ''
url_pdf: publication/Duke_2019_MLfluid/ML_fluid.pdf
url_poster: ''
url_project: ""
url_slides: Presentation.pdf
url_source: ''
url_video: ''
---
