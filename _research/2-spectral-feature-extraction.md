---
title: Improving the efficiency of spectral feature extraction by structuring the audio files
tags: [Audio analysis, Spectral features, Librosa, March'20]
style: 
color: 
description: IEEE - Acceptance and due publishing <br>
external_url: 
---

# Improving the efficiency of spectral feature extraction by structuring the audio files

###### - _**Dishant Parikh**, Saurabh Sachdev_

<br>

### Abstract
>The extraction of spectral features from a music clip is a computationally expensive task. As in order to extract accurate features, we need to process the clip for its whole length. This preprocessing task creates a large overhead and also makes the extraction process slower. We show how formatting a dataset in a certain way, can help make the process more efficient by eliminating the need for processing the clip for its whole duration, and still extract the features accurately. In addition, we discuss the possibility of defining set generic durations for analyzing a certain type of music clip while training. And in doing so we cut down the need of processing the clip duration to just 10% of the
global average.

<br>

### Implications

---

The research discusses the  development of a model to extract the best time to trim the clip, and for how much length, to efficiently extract the features, by just 15 to 20 seconds of audio length to be processed. This can be done by making a bigger dataset with defined labels, and then dividing the clips into many different length clips. After that, the features can be extracted for that length and compared with the total length processing. This would lead to a conclusive result that at which length, which genre is at its optimum and can give the near exact feature extraction. 

This would then lead to greater improvements to the efficiency of the feature extraction process. This can take the computational toll down by at least 10 times the current value. When it comes to the use of the technology, this method can be used for faster analysis in the music applications, which deals with the features like understanding the likings of a particular user. For that most applications use data analysis on two features, one is the lyrics and second the tune, i.e. the spectral features. By considering the flow of music into such applications every day, if someone needs to give somewhat of an analysis every time a new song is entered, it can be done dynamically by using our technique. The workaround is going to lead to near-perfect spectral feature extraction, at least **10 times** faster.

<p class="text-center">
{% include elements/button.html link="https://arxiv.org/abs/2010.03136" text="Read full paper" %}
</p>