---
layout: post
title: "Assorted Deep Learning Materials"
excerpt: "These contain learning resources and academic papers on deep learning"
date:   2016-1-1 10:00:00
header-img: "img/post-bg-01.jpg"
---

##General

### [My favorite learning resource on neural network implementation](http://neuralnetworksanddeeplearning.com/chap6.html)
Chapter 6 focuses on implementation and the other chapters deal with math, layers, etc.

### [An engineering approach to understanding neural networks](http://karpathy.github.io/neuralnets/)

### [This is a fun assortment of tips from the top experts](http://www.marekrei.com/blog/26-things-i-learned-in-the-deep-learning-summer-school/)
The blog is maintained by a Cambridge researcher and has useful tips on deep learning with python

### [Kaggle competition interviews provide specific insights](http://blog.kaggle.com/2012/11/01/deep-learning-how-i-did-it-merck-1st-place-interview)

### [This is a quick and reliable implementation of selective search](https://github.com/AlpacaDB/selectivesearch)



## Academic Papers

###[TL;DR: Random patterns can be interpreted by neural nets as natural objects with high confidence](http://arxiv.org/pdf/1412.1897v4.pdf)

###[TL;DR: A barely noticeable change in the image can lead to different classifications by the model](http://arxiv.org/pdf/1312.6199v4.pdf)

###[TL;DR: Movie scenes and dialogue can be used to generate answers to diverse questions](http://arxiv.org/pdf/1512.02902v1.pdf)



##Miscellaneous

### Fun with Image Generation
Training a neural network on a particular style can make you an artist in no time.  
Here is a "self-portrait" in the style of Greco:
![]({{DenisPeskov.github.io}}/images/Greco_DeepLearning_self.png)

[Google Deep Dream](https://github.com/google/deepdream) is based on creating a feedback loop of deep neural net predicitions and subsequent image modifications that makes images appear out of thin air.  You can quickly test it out [here](http://deepdreamgenerator.com/).



### Installing Caffe
Installing caffe can be tedious.  Installing it on a Mac was twice as frustrating as on Linux.  Ensuring that dependencies in homebrew and anaconda are installed in the correct locations complicates a seemingly straighforward process:
http://caffe.berkeleyvision.org/install_osx.html

I would recommend installing caffe in CPU_only mode first before trying the GPU installation.  This makes debugging CUDA installation issues easier.  I've successfully run caffe on Amazon Web Services and Nimbix servers without issues.
