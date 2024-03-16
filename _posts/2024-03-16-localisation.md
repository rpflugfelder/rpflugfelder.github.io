---
title: "Robust Object Localisation under Fragmented Occlusion"
categories: thesis
layout: post
---

# Problem Statement
Localising objects under [fragmented occlusion](https://doi.org/10.1006/cviu.1996.0006) is an important pre-requisite for [through-foliage detection](https://link.springer.com/chapter/10.1007/978-3-030-69460-9_16) in forests. Unfortunately, [state-of-the-art detectors fail](https://www.doi.org/10.3217/978-3-85125-752-6-23) to accurately localise objects under this type of occlusion.

Interestingly, [human vision](https://doi.org/10.1177%2F20416695211062625) seems to overcome fragmented occlusion seamlessly by integrating partial visual percepts over time. 

# Goal
The thesis builds on [previous work](https://doi.org/10.1109/AVSS52988.2021.9663791) based on an encoder-decoder network and aims at open questions to be answered, such as:
* how to improve the method to generalise to empty scenes and scenes with more than one person,
* why does the network generalise to occluded sequences from unoccluded training data,
* how to adapt the encoder to allow visualisation of the features

![Localisaion](/assets/images/localisation.png)

# Requirements
* Basic knowledge in computer vision or computer graphics
* Basic experience in C++, Python, Julia
* Interest in machine learning, maths, statistics

# Workflow
## TUM
Detailed information can be found [here](https://www.cit.tum.de/cit/studium/studierende/abschlussarbeit-abschluss/).
