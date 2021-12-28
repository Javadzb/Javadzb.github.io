---
title: "Portfolio item number 2"
excerpt: "Short description of portfolio item number 2 <br/><img src='/images/500x300.png'>"
collection: projects
---
Study of whether the active learning and self supervised learning can benefit from eachother. 

[Download paper here](https://arxiv.org/pdf/2108.11458.pdf)

![fig1]({{ site.url }}/images/framework_ICCVW2021.jpg)

Abstract:
> Active learning is a paradigm aimed at reducing the annotation effort by training the model on actively selected informative and/or representative samples. 
Another paradigm to reduce the annotation effort is self-training that learns from a large amount of unlabeled data in an unsupervised way and fine-tunes on few labeled samples. Recent developments in self-training have achieved very impressive results  rivaling supervised learning on some datasets. 

> The current work focuses on whether the two paradigms can benefit from each other. We studied object recognition datasets including CIFAR10, CIFAR100 and Tiny 
ImageNet with several labeling budgets for the evaluations.  Our experiments reveal that self-training is remarkably more efficient than active learning 
at reducing the labeling effort, that for a low labeling budget, active learning offers no benefit to self-training, and finally that the combination of 
active learning and self-training is fruitful when the labeling budget is high. The performance gap between active learning trained either with self-training 
or from scratch diminishes as we approach to the point where almost half of the dataset is labeled.
