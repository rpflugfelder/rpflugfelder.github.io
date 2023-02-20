---
title: ""
permalink: "/"
layout: page
---

<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/pace/1.0.2/pace.min.js"></script>

<figure>
  <img class="alignleft" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/af/Under_construction_icon-yellow.svg/291px-Under_construction_icon-yellow.svg.png" alt="" width="69" height="57" />
  <figcaption>My research profile is under construction.</figcaption>
</figure>

# Dynamic Perception and Understanding

My scientific interest lies in visual motion analysis and tracking and in the importance of motion perception in object recognition and scene understanding. I currently focus in my research on the problem of fragmented and dynamic occlusion in machine and human vision.

## Examples of Fragmented and Dynamic Occlusion

Please move your mouse pointer (or finger) over the image and click the left mouse button (or touch your display) to start the animation and to perceive motion.

<figure>
  <img src="/assets/images/fence.png" height="180" width="320" alt="Frag Image" data-alt="/assets/images/fence.gif">
  <figcaption>Motion reveals a little car through a fence ...</figcaption>
</figure>

<figure>
  <img src="/assets/images/frag.png" height="320" width="320" alt="Frag Image" data-alt="/assets/images/frag.gif">
  <figcaption>... or a fragmentally occluded person through foliage.</figcaption>
</figure>

<figure>
  <img src="/assets/images/cam.png" height="256" width="320" alt="Cam Image" data-alt="/assets/images/cam.gif">
  <figcaption>Motion makes a camouflaged person in thermal images visible.</figcaption>
</figure>

## Examples of Tracking

<figure>
  <img src="/assets/images/car.png" height="256" width="320" alt="Car Image" data-alt="/assets/images/car.gif">
  <figcaption>Motion helps a detector to aquire online a representation (green circles) of a car starting from an initial bounding box in the first image (<a href="https://doi.org/10.1109/WACV.2014.6836013">IEEE WACV'14</a>, <a href="https://doi.org/10.1109/CVPR.2015.7298895"> CVPR'15</a>).</figcaption>
</figure>

## Further Examples

<figure>
  <img src="/assets/images/heeger.png" height="240" width="320" alt="3D Image" data-alt="/assets/images/heeger.gif">
  <figcaption>Motion let us perceive depth and many more things! For more examples, visit D. Heeger's <a href="http://www.cns.nyu.edu/~david/courses/perception/lecturenotes/motion/motion.html">webpage</a>.</figcaption>
</figure>



<script src="/js/script-min.js"></script>


<!--

We [combined](research/trackdetect.html) detection and tracking of arbitrary looking objects.
Here is the [link](research/early-work.md) to my early work.

***
The summary of publications is found in my [publication list](/assets/docs/mybib.pdf).

# Combining Motion Perception and Recognition
# Work on Object Tracking

# Work on Simultaneous Localisation and Tracking (SLAT)

# Work on 


<h5>The Problem of Fragmented Occlusion in Object Detection</h5>
<div style="float: right; padding-left: 10px;"><img class="alignnone wp-image-8378" src="https://cvl.tuwien.ac.at/wp-content/uploads/2020/04/Level3.jpg" alt="" width="226" height="336" /></div>
Object detection in natural environments is still a very challenging task, even though deep learning has brought a tremendous improvement in performance over the last years. A fundamental problem of object detection based on deep learning is that neither the training data nor the suggested models are intended for the challenge of fragmented occlusion. Fragmented occlusion is much more challenging than ordinary partial occlusion and occurs frequently in natural environments such as forests. A motivating example of fragmented occlusion is object detection through foliage which is an essential requirement in green border surveillance. This paper presents an analysis of state-of-the-art detectors with imagery of green borders and proposes to train Mask R-CNN on new training data which captures explicitly the problem of fragmented occlusion. The results show clear improvements of Mask R-CNN with this new training strategy (also against other detectors) for data showing slight fragmented occlusion. <a href="https://foldout.eu">h2020-foldout</a> <a href="https://arxiv.org/abs/2004.13076">arXiv</a> <a href="https://diglib.tugraz.at/download.php?id=5f6b1d5e08291&amp;location=browse">acvr</a>
<h5 class="title mathjax"><a name="satvideo"></a>On Learning Vehicle Detection in Satellite Video</h5>
<div style="float: right; padding-left: 10px;">

[video width="220" height="220" mp4="https://cvl.tuwien.ac.at/wp-content/uploads/2015/12/lasvegas180.mp4" loop="true" autoplay="true"][/video]

</div>
Vehicle detection in aerial and satellite images is still challenging due to their tiny appearance in pixels compared to the overall size of remote sensing imagery. Classical methods of object detection very often fail in this scenario due to violation of implicit assumptions made such as rich texture, small to moderate ratios between image size and object size. Satellite video is a very new modality which introduces temporal consistency as inductive bias. Approaches for vehicle detection in satellite video use either background subtraction, frame differencing or subspace methods showing moderate performance (0.26 - 0.82 <span id="MathJax-Element-1-Frame" class="MathJax" tabindex="0"><span id="MathJax-Span-1" class="math"><span id="MathJax-Span-2" class="mrow"><span id="MathJax-Span-3" class="msubsup"><span id="MathJax-Span-4" class="mi">F</span><span id="MathJax-Span-5" class="mn">1</span></span></span></span></span> score). This work proposes to apply recent work on deep learning for wide-area motion imagery (WAMI) on satellite video. We show in a first approach comparable results (0.84 <span id="MathJax-Element-2-Frame" class="MathJax" tabindex="0"><span id="MathJax-Span-6" class="math"><span id="MathJax-Span-7" class="mrow"><span id="MathJax-Span-8" class="msubsup"><span id="MathJax-Span-9" class="mi">F</span><span id="MathJax-Span-10" class="mn">1</span></span></span></span></span>) on Planet's SkySat-1 LasVegas video with room for further improvement. <a href="https://arxiv.org/abs/2001.10900">arXiv </a><a href="https://data.vicos.si/cvww20/CVWW20-proceedings.pdf">cvww</a>
<h5>Benchmarking Tracking</h5>
<img class="alignnone size-full wp-image-6894" src="https://cvl.tuwien.ac.at/wp-content/uploads/2015/12/logo_website.png" alt="" width="127" height="61" />      <img class="alignnone size-medium wp-image-6895" src="https://cvl.tuwien.ac.at/wp-content/uploads/2015/12/videonet_title-300x78.png" alt="" width="300" height="78" />
In 2012, I initiated together with Matej Kristan the Visual Object Tracking Challenge (VOT) and since then I have been co-organising annual challenges and workshops at ICCV and ECCV with Matej Kristan, Ales Leonardis, Jiri Matas, Michael Felsberg and Joni-Kristian Kämäräinen. VOT is de facto the international community benchmark in the field of visual tracking. Important results of our work are A-R measures for quantifying short-term tracking performance in terms of accuracy and robustness and the discovery of correlation filters as superior approach for tracking. More information can be found on our <a href="http://www.votchallenge.net">webpage</a>. VOT is also part of the benchmark <a href="http://videonet.team/#team">initiative</a> for all things video.
<h5>An in-depth Analysis of Visual Tracking with Siamese Neural Networks</h5>
This survey presents a deep analysis of the learning and inference capabilities in nine popular trackers. It is neither intended to study the whole literature nor is it an attempt to review all kinds of neural networks proposed for visual tracking. We focus instead on Siamese neural networks which are a promising starting point for studying the challenging problem of tracking. These networks integrate efficiently feature learning and the temporal matching and have so far shown state-of-the-art performance. In particular, the branches of Siamese networks, their layers connecting these branches (a-e), specific aspects of training and the embedding of these networks into the tracker are highlighted.

<img class="aligncenter wp-image-8225 size-full" src="https://cvl.tuwien.ac.at/wp-content/uploads/2020/02/siamese-classes.png" alt="" width="974" height="259" />

Quantitative results from existing papers are compared with the conclusion that the current evaluation methodology shows problems with the reproducibility and the comparability of results. The paper proposes a novel Lisp-like formalism for a better comparison of trackers. This assumes a certain functional design and functional decomposition of trackers. The paper tries to give foundation for tracker design by a formulation of the problem based on the theory of machine learning and by the interpretation of a tracker as a decision function. The work concludes with promising lines of research and suggests future work. <a href="https://arxiv.org/abs/1707.00569">arXiv</a>
<h5>Clustering of Static-Adaptive Correspondences for Deformable Object Tracking</h5>
<div style="float: right; padding-left: 10px;">

[video width="320" height="240" mp4="https://cvl.tuwien.ac.at/wp-content/uploads/2020/02/occlusion.mp4" loop="true" autoplay="true"][/video]

</div>
<h5>Car Tracking in Tunnels</h5>
<div style="float: right; padding-left: 10px;">

[video width="320" height="240" loop="true" autoplay="true" mp4="https://cvl.tuwien.ac.at/wp-content/uploads/2020/10/carlight_tracking.mp4"][/video]

</div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">

Tracking methods are fundamental operations in traffic scene analysis. In this work we report on a tracking algorithm with a Kalman filter for traffic surveillance in tun- nels. The difficulties of solving the problem are the illumina- tion conditions and the image quality. We demonstrate our work on short sequences of tunnel scenes. <a href="https://www.researchgate.net/profile/Horst_Bischof/publication/260403050_Car_tracking_in_tunnels/links/53cfc4470cf2fd75bc59f73d/Car-tracking-in-tunnels.pdf">CVWW</a>

</div>
</div>
</div>
Please, see my <a href="https://cvl.tuwien.ac.at/wp-content/uploads/2020/01/mybib.pdf">publication list</a> for more details.

-->



<!---
A [Kurt Goedel stipend](https://kgs.logic.at) allowed me to pursue 2001-2002 a master's degree in Computer Science and Informatics under the supervision of [Brian Lovell](https://staff.itee.uq.edu.au/lovell/) and Horst Bischof at  and TU Wien. 

I was awarded for my scientific contributions in 2008 with a Viennese [WWTF](https://www.wwtf.at/index.php?lang=EN) Career Grant and in 2014 with the IEEE/CvF WACV Best Paper Award. I received several reviewer awards (2016 - J. of Image and Vision Computing, 2017 - J. of Pattern Recognition, 2019 - CVPR) for my community work. 

I founded in 2012 together with [Matej Kristan](https://www.vicos.si/people/matej_kristan/) the [VOT challenges and workshop series](https://www.votchallenge.net).

where I built 2008-2015 as a manager of governmental and EU funded projects 

--->






<!---
 I am programming in  

 [![Julia](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1f/Julia_Programming_Language_Logo.svg/200px-Julia_Programming_Language_Logo.svg.png)](https://julialang.org)
--->
