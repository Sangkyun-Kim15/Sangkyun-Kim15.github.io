---
layout: post
title:  "Image Colorizer with neural networks"
date:   2021-09-09
excerpt: "CS440 Intro Artificial Intelligence"
project: true
tag:
- neural network
- ai
comments: false
---
This was the project from CS440 Intro Artificial Intelligence. The goal was to convert greyscale images to two colorized versions of images by using K-means clustering and neural networks.

## K-means clustering verion (Basic agent)
* Select 5 random pixels for grouping
* Grouping was based on the distance between the target pixel and each centroid
* Using euclidean distance to calculate the distance.

![](../assets/img/basic1.png)

## Neural Networks version (Advanced agent)
* A Feed-Forwarding 3 layers neural networks
* 9 nodes in the input layer (3x3 patch = 9 pixels)
* 5 nodes in the hidden layer
* 3 nodes in the output layer (pixel has R, G, B)
* Using sigmoid function as activation function

![](../assets/img/advanced1.png)

<div markdown="0">
    <a href="https://github.com/Norden-Tenzin/440ArtificialIntelligence/tree/master/COLORIZATION" class="btn">Code</a>
    <a href="https://github.com/Norden-Tenzin/440ArtificialIntelligence/blob/master/COLORIZATION/Report4_sk1998_tn266.pdf" class="btn">Tech Report</a>
</div>
