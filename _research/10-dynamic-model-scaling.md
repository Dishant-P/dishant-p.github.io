---
title: Dynamic Model Scaling for Convolutional Neural Networks
tags: [CNN, Model Scaling, April'20]
style: fill
color: success
description: Due submission - Draft is accessible
external_url: 
---


# Dynamic Model Scaling for Convolutional Neural Networks: A review

###### - _**Dishant Parikh**, Jeel Jotaniya_

<br>

### Abstract
>Deep neural network architectures are difficult to train, especially due to the high complexity which in turn leads to higher computational costs. With the introduction of the Pytorch framework, dynamic model scaling came into effect. With this we have an opportunity to scale the model and the meta features dynamically as the model starts to train. If the feature extraction and rates of learning doesn’t affect much then the model can be scaled up. Here we discuss the automated model scaling of deep neural networks for image recognition. The methodology of dynamically changing the model meta features is
named as Efficient Nets. With this we rethink the development of CNN architectures, as the computational budget cannot be considered as fixed, due to the dynamicity of model’s meta features.

<br>

### Implications

---

The paper does show how well the EfficientNets work on the dog breeds dataset even with a heavier similarity between the classes. Even though residual networks took a considerably smaller time to train, it only could get a 68 percent accuracy on the validation. With that the EfficientNet takes about 10 percent more time but has a validation accuracy of 82 percent. The way model scaling has evolved, the whole concept has gone under rethinking. The dynamic model scaling does show an answer into training even
deeper and better neural architectures. 

EfficientNets may also be useful in prototyping newer model architectures as it can get the best model meta features on its own. So if we are able to take a time snapshot, we may declare a acretain network as better for a particular class of image and another for a different one. With this it is suffice to say that with EfficentNets, the whole deep learning community will now have a power to dynamically test their models on different neural architectures on a single run through the network. When we train the model we need not think about the meta features required to increase the efficiency of the model as such.

<p class="text-center">
{% include elements/button.html link="#" text="Draft unavailable" %}
</p>