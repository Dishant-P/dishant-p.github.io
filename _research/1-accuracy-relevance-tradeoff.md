---
title: Accuracy Releance trade-off in Transfer Learning for Object Detection
tags: [Computer Vision, Dataset Relevance, January'20]
style: fill
color: primary
description: IEEE - Acceptance and due publishing <br>
external_url: 
---


# Accuracy Relevance trade-off in Transfer Learning for Object Detection

###### - _**Dishant Parikh**, Saurabh Sachdev_

<br>

### Abstract
>This paper addresses the problem of accuracy while using different datasets to train the parent model on, while using transfer learning. We show how the training time and accuracy of the custom object detector depend on the parent model’s dataset. We show comprehensive empirical evidence that there is a strong dependence of datasets, while there is a possibility to train any model up to the desired accuracy if trained for a longer time, or if the relevance with the custom dataset is increased. The more the relevance, the faster the training and more is the accuracy of the custom detector. The difference in accuracy, given the same time to train, but different parent dataset is 10-12%. When using Ava as parent dataset we obtain 68.4%. By merely changing the parent dataset to COCO, we achieved a 20% increase in the mAP score.

<br>

### Implications

---

The research helps in choosing the right dataset and model while training a object detector using transfer learning. Research shows the possibility of a central master parent dataset over which different types of models are trained and then those are used for any purpose whatsoever. With the mathematical definition and/or comparison of the relevancy of the parent and custom dataset, we can more accurately define and see the dependence and can give a solid trade-off of accuracy.

The results of the experiments support the claims and hence prove that there does lie a dependency of the dataset on which the parent model has been trained. Although it is important to note that every parent dataset model can be used to predict the objects on the custom detector. The more clear and mathematical proof could be given once we can mathematically define the relevance of parent data with the
custom data.

<p class="text-center">
{% include elements/button.html link="https://drive.google.com/file/d/1nqIQiqOhJr5BF_DW4DpBGcozLn7cNrCb/view?usp=sharing" text="Read full paper" %}
</p>