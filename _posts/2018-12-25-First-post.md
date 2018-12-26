---
layout: post
title: First blog post
---

Hi. In this blog I will detail projects I am working on.

# First Project

The first project I will describe is a cough detector. My daughter has a
cough suseptiblity and my wife and I need a way to figure out when we should
give her an albuterol treatment. The goal will be to have some sort of application
running in the background to track how much time she coughs at night. My wife and
I will decide if we need to give her a treatment given how much time she has coughed at
night.

### Initial thoughts on how to proceed
* Collect examples of her coughing
* Annotate the coughs
* Syntesize positive and negative training examples
* Compute spectrogram of audio clips
* Learn a simple classifier to see how well we can classify examples


### Example of spectrogram
![_config.yml]({{ site.baseurl }}/images/Spectrogram-example.png)
