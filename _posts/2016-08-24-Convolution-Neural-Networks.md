---
layout: post
title: Convolutional Neural Network
date: 2016-08-24
---

Prerequisites
------
Nueron perceptron model - linear classification - loss function - training - Back Propogation.

Why do we need CNN
------
* The number of parmeters learned in regular neural network will grow if we simplye use a fully connected network.
* Instead if we use a convolution mask to learn the wieghts, then the convolutiona mask wieghts are shared despite the size of the image. This reduces the no of weights to be learned.
* Below is a complex layout of CNN architecture called AlexNet.


![A complex layout of AlexNet]({{ site.base.url }}/images/AlexNet.jpg "Alex Network") 

![A gif of convolution]({{ site.base.url }}/images/convolution.gif "convolution") 
