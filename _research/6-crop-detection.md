---
title: Automatic Crop-fields classifier trained on Digital Images
tags: [Satellite Imagery, Object Detection, September'19]
style: 
color: 
description: Research conclusive, due submission
external_url: 
---


# Automatic Crop-fields classifier trained on Digital Images

###### - _**Dishant Parikh**, Ishika Saini, Pranjal Sharma, Giribabu Babu Dandabathula, Sitiraju Srinivasa Rao_

<br>

### Abstract
>Rule based approaches using multi-temporal and radar images, have shown their promise as a universal representation for recognition and detection of agricultural crop fields. But when it comes to dealing with images which captures the digital imagery in the normal visible band, it is certainly an unanswered question, with no structured data whatsoever. Remote sensing is heavily dependent on the accuracy of the satellites, but some weather conditions do deteriorate the accuracy and efficiency of a satellite image, especially monsoon. Hence working with the digital images captured by drones or by other means, become a necessary data to work upon. Here we propose an object detection model to work with normal digital images to automatically classify various crop fields. Here we propose a two step object detection model to classify, using SSD as detection model and Mobile Net as feature extractor. As we are using transfer learning for training, due to the lack of data, we are going to use a parent model trained on the Open Image Dataset.

<br>

### Implications

---

The model, though complete in itself for the crops listed earlier, still cannot be deployed in the agriculture sector at large. There are still many crops specific to the particular region, which need to be added in the dataset. In short, the model needs to train on other crop fields too. 
This task will be quite difficult as such, because many crops, specifically in India, are rare or difficult to find. But to make the crop fields classifier robust and autonomous, it is important to train it on those crops too. The way it can be achieved is by making applications or web portals, through which people or farmers themselves can upload images of the fields. Again this task still has a lot of work due to the manually label encoding. But once the dataset is expanded, it will be useful for the agricultural technology and related field of work.


<p class="text-center">
{% include elements/button.html link="#" text="Draft unavailable" %}
</p>