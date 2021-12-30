---
title: "When Deep Learners Change Their Mind: Learning Dynamics for Active Learning"
collection: publications
permalink: /publication/2021-06-01-dispersion
excerpt: ''
date: 2021-06-01
venue: 'CAIP'
paperurl: ''
citation: ''
---
To tackle the overconfidence of neural nets, we introduce dispersion metric that is based on learning dynamics of neural nets. 
[Download paper](https://arxiv.org/pdf/2107.14707.pdf)[Video](https://www.youtube.com/watch?v=qYt7SD8MaQ4)

![fig1]({{ site.url }}/images/caip_motivation_figure.jpg)

Abstract:

> Active learning aims to select samples to be annotated that yield the largest performance improvement for the learning algorithm. Many methods approach this problem by measuring the informativeness of samples and do this based on the certainty of the network predictions for samples. However, it is well-known that neural networks are overly confident about their prediction and are therefore an untrustworthy source to assess sample informativeness. 

> In this paper, we propose a new informativeness-based active learning method. Our measure is derived from the learning dynamics of a neural network. More precisely we track the label assignment of the unlabeled data pool during the training of the algorithm. We capture the learning dynamics with a metric called label-dispersion, which is low when the network consistently assigns the same label to the sample during the training of the network and high when the assigned label changes frequently.

> We show that label-dispersion is a promising predictor of the uncertainty of the network, and show on two benchmark datasets that an active learning algorithm based on label-dispersion obtains excellent results.

<!-- Recommended citation: Javad Zolfaghari, Bogdan Raducanu, Joost van de Weijer. When Deep Learners Change Their Mind: Learning Dynamics for Active Learning. Proceedings of 19th International Conference on Computer Analysis of Images and Patterns (CAIP), 2021. -->
