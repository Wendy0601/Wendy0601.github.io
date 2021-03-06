---
title: "Markov Random Field (MRF) for Image Segmentation"
excerpt: "Initialize the labels with noise and then iteratively segment the plane in the image <br/><img src='/images/segment_plane.png'>" 
collection: portfolio
--- 
The aim of this project is to segment the background and foreground of an image
using the Label-Observation MRF model. The labels are defined to represent the background
and foreground respectively. The intensity is continuous observations. The Potts model is
employed to model the correlations between any two nodes, and the intensity is assumed
to follow the Gaussian distribution. The parameters of the
MRF model are given, and the problem is to determine the labels of each nodes.
This is the report and codes.
[Download here](http://Wendy0601.github.io/files/segment.pdf)
