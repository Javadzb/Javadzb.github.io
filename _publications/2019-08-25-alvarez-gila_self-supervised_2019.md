---
title: "Self-Supervised Blur Detection from Synthetically Blurred Scenes"
collection: publications
permalink: /publication/2019-08-25-alvarez-gila_self-supervised_2019
date: 2019-08-25
venue: 'Image and Vision Computing'
paperurl: 'https://doi.org/10.1016/j.imavis.2019.08.008'
citation: 'A. Alvarez-Gila, A. Galdran, E. Garrote, and J. van de Weijer, “Self-supervised blur detection from synthetically blurred scenes,” Image and Vision Computing, vol. 92, p. 103804, Dec. 2019.'

---

<a href='https://doi.org/10.1016/j.imavis.2019.08.008'>Full text (official)</a>

<a href='https://arxiv.org/abs/1908.10638'>Full text (preprint)</a>

<a href='https://github.com/aitorshuffle/synthblur'>Code, models and data </a>

Abstract: 

> Blur detection aims at segmenting the blurred areas of a given image. Recent deep learning-based methods approach this problem by learning an end-to-end mapping between the blurred input and a binary mask representing the localization of its blurred areas. Nevertheless, the effectiveness of such deep models is limited due to the scarcity of datasets annotated in terms of blur segmentation, as blur annotation is labor intensive. In this work, we bypass the need for such annotated datasets for end-to-end learning, and instead rely on object proposals and a model for blur generation in order to produce a dataset of synthetically blurred images. This allows us to perform self-supervised learning over the generated image and ground truth blur mask pairs using CNNs, defining a framework that can be employed in purely self-supervised, weakly supervised or semi-supervised configurations. Interestingly, experimental results of such setups over the largest blur segmentation datasets available show that this approach achieves state of the art results in blur segmentation, even without ever observing any real blurred image. 

![fig1]({{ site.url }}/images/alvarez-gila_self-supervised_2019_fig1_abstract.png)

Bibtex:

```
@article{alvarez-gila_self-supervised_2019,
  title = {Self-Supervised Blur Detection from Synthetically Blurred Scenes},
  volume = {92},
  issn = {0262-8856},
  abstract = {Blur detection aims at segmenting the blurred areas of a given image. Recent deep learning-based methods approach this problem by learning an end-to-end mapping between the blurred input and a binary mask representing the localization of its blurred areas. Nevertheless, the effectiveness of such deep models is limited due to the scarcity of datasets annotated in terms of blur segmentation, as blur annotation is labor intensive. In this work, we bypass the need for such annotated datasets for end-to-end learning, and instead rely on object proposals and a model for blur generation in order to produce a dataset of synthetically blurred images. This allows us to perform self-supervised learning over the generated image and ground truth blur mask pairs using CNNs, defining a framework that can be employed in purely self-supervised, weakly supervised or semi-supervised configurations. Interestingly, experimental results of such setups over the largest blur segmentation datasets available show that this approach achieves state of the art results in blur segmentation, even without ever observing any real blurred image.},
  language = {en},
  journal = {Image and Vision Computing},
  doi = {10.1016/j.imavis.2019.08.008},
  author = {{Alvarez-Gila}, Aitor and Galdran, Adrian and Garrote, Estibaliz and {van de Weijer}, Joost},
  month = dec,
  year = {2019},
  keywords = {Blur detection,Deep learning,Defocus blur,Motion blur,Self-supervised learning,Synthetic},
  pages = {103804}
}
```
