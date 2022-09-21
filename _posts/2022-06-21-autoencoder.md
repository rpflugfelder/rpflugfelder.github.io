---
title: "Deoccluding Autoencoder"
categories: thesis
layout: post
---

# Problem Statement
Occlusion is a substantial problem in object recognition. A special type of occlusion is [fragmented occlusion](https://doi.org/10.1006/cviu.1996.0006) where only small and always different parts of the object are visible at a time.

Interestingly, [human vision](https://doi.org/10.1177%2F20416695211062625) is able to spatiotemporally analyse such fragmental, visual percepts and allows accurate object recognition even for very challenging scenes such as to recognise a moving object of interest behind a fence.

# Goal
The thesis aims at the idea to learn a neural function of deocclusion by an encoder-decoder archiecture in spirit similar to a [denoising autoencoder](https://www.deeplearningbook.org/contents/autoencoders.html). The candidate is asked to investigate avenues of unsupervised learning by using examples with synthetic occlusion.

![architecture](/assets/images/test.png)

The interested candidate is also encouraged to work with event data from a [neuromorphic camera](https://inivation.com) inspired by [recent research](https://scholar.google.at/scholar?cites=5205630784265455546&as_sdt=2005&sciodt=0,5).

| --- | --- |
| <img alt="event" src="/assets/images/event.jpg" width="202"> |
  <video controls autoplay loop>
    <source type="video/mp4" src="/assets/images/events.mp4" />
  </video> |

# Requirements
* Basic knowledge in computer vision or computer graphics
* Basic experience in C++, Python, Julia
* Interest in machine learning, maths, statistics

# Workflow
## TUM
Detailed information can be found [here](https://www.in.tum.de/in/fuer-studierende/master-studiengaenge/informatik/abschlussarbeit/).

## TU Wien
You should be enrolled in the Master Programmes Visual Computing or Data Science. The thesis can be combined with an Informatik Praktika. Please, do not forget to attend the mandatory [courses](https://cvl.tuwien.ac.at/teaching/diplomarbeiten/allgemeine-hinweise-zu-masterarbeiten) (as well for the [Praktika](https://cvl.tuwien.ac.at/teaching/informatik-praktika/allgemeine-hinweise-zu-bachelorarbeiten-und-praktikas)). You will write a thesis proposal at the beginning where you are welcome to formulate your own research ideas in agreement with the supervisor.
