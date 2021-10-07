---
title:  S-Extension Patch - A simple and efficient way to extend an object detection model
tags: [DSI, Image similarity, Visual datasets, Perception architectures, Sep'21]
style: 
color: warning
description: Under Review - Paper accessible
external_url: 
---


# S-Extension Patch: A simple and efficient way to extend an object detection model

###### - _**Dishant Parikh**_

<br>

### Abstract
>While building convolutional network-based systems, the toll it takes to train the network is something that cannot be ignored. In cases where we need to append additional capabilities to the existing model, the attention immediately goes towards retraining techniques. In this paper, I show how to leverage knowledge about the dataset to append the class faster while maintaining the speed of inference as well as the accuracies; while reducing the amount of time and data required. The method can extend a class in the existing object detection model in 1/10th of the time compared to the other existing methods. S-Extension patch not only offers faster training but also speed and ease of adaptation, as it can be appended to any existing system, given it fulfills the similarity threshold condition.
<br>

### Implications

---

In the case of object detectors, the problem of extending a model always exists, and it can be expensive for the company to wait for a period till the team appends the extension class to the system. The S-Extension patch provides an efficient way to extend the model and make sure that the system keeps running, with not just the same but better accuracy with the extension class appended to the existing model. The S-E patch solves the problem of ease of adaptation plus the cost of time-out for the industrial systems.

<p class="text-center">
{% include elements/button.html link="https://arxiv.org/abs/2110.02670" text="Read full paper" %}
</p>