---
title: "Deep Vehicle Detection in Satellite Video"
categories: thesis
layout: post
---

# Problem Statement
[Object detection](https://arxiv.org/abs/1506.01497) is a very important and still unsolved problem in object recognition. For example, the problem becomes challenging in aerial imaging and remote sensing as the scenes and the data differ significantly from the case usually considered in computer vision. Vehicles in satellite images are tiny (4-10 pixel), the recognition of vehicles is challenging as seen in the following image cropped from a high-resolution satellite image.

![Deli](/assets/images/deli.png)

Motion can be an important cue to detect tiny objects. Remote vehicle detection has potential to innovate traffic monitoring and traffic prediction models which are today essential for autonomous driving and smart cities.

# Goal
Given our [previous work](https://arxiv.org/abs/2204.06828) on satellite video, the aim of this thesis is to study vehicle detection for a new sensor modality. This thesis offers the opportunity to develop a vehicle detector based on short sequences of [All-Frames images](https://assets.planet.com/docs/Planet_Basic_L1A_All-Frames_User_Guide.pdf) which are taken by Planet's [SkySat](https://earth.esa.int/eogateway/missions/skysat) constellation.

Starting with the existing encoder-decoder network, a new generative network should be designed for the new data. The network should allow the visualisation of features in the encoder to better understand the generalisation process. The aim of the thesis is to develop a self-supervised or unsupervised learning method.

# Requirements
* Basic knowledge in computer vision or computer graphics
* Basic experience in C++, Python, Julia
* Interest in machine learning, maths, statistics
* Interest in collaborating internationally with other partners ([IARAI](https://www.iarai.ac.at/traffic4cast/), [Planet](http://www.planet.com), [ESA](https://philab.phi.esa.int))

# Workflow
## TUM
Detailed information can be found [here](https://www.in.tum.de/in/fuer-studierende/master-studiengaenge/informatik/abschlussarbeit/).

## TU Wien
You should be enrolled in the Master Programmes Visual Computing or Data Science. The thesis can be combined with an Informatik Praktika. Please, do not forget to attend the mandatory [courses](https://cvl.tuwien.ac.at/teaching/diplomarbeiten/allgemeine-hinweise-zu-masterarbeiten) (as well for the [Praktika](https://cvl.tuwien.ac.at/teaching/informatik-praktika/allgemeine-hinweise-zu-bachelorarbeiten-und-praktikas)). You will write a thesis proposal at the beginning where you are welcome to formulate your own research ideas in agreement with the supervisor.
