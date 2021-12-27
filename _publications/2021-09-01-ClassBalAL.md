---
title: "Class-Balanced Active Learning for Image Classification"
collection: publications
permalink: /publications/2021-09-01-ClassBalAL
excerpt: ''
date: 2021-09-01
venue: 'WACV'
paperurl: ''
citation: ''
---
We study the class imbalance in Active Learning and propose an optimization based method to reduce the class imbalance.

[Download paper here](https://arxiv.org/pdf/2110.04543.pdf)

![fig1]({{ site.url }}/images/wacv_framework.jpg)

Abstract:

> Active learning aims to reduce the labeling effort that is required to train algorithms by learning an acquisition function selecting the most relevant data for which a label should be requested from a large unlabeled data pool. Active learning is generally studied on balanced datasets where an equal amount of images per class is available. However, real-world datasets suffer from severe imbalanced classes, the so called long-tail distribution. We argue that this further complicates the active learning process, since the imbalanced data pool can result in suboptimal classifiers. 

> To address this problem in the context of active learning, we proposed a general optimization framework that explicitly takes class-balancing into account. Results on three datasets showed that the method is general (it can be combined with most existing active learning algorithms) and can be effectively applied to boost the performance of both informative and representative-based active learning methods.

Bibtex:
```
@article{bengar2021class,
  title={Class-Balanced Active Learning for Image Classification},
  author={Bengar, Javad Zolfaghari and van de Weijer, Joost and Fuentes, Laura Lopez and Raducanu, Bogdan},
  journal={arXiv preprint arXiv:2110.04543},
  year={2021}
}
```
