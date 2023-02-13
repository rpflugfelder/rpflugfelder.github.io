---
layout: page
title: "Work"
---

[Early Work](research/early-work.md)

***
The summary of publications is found in my [publication list](/assets/docs/mybib.pdf).

# Combining Motion Perception and Recognition
# Work on Object Tracking

# Work on Simultaneous Localisation and Tracking (SLAT)

# Work on 
# Early work

<h5><img class="alignleft" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/af/Under_construction_icon-yellow.svg/291px-Under_construction_icon-yellow.svg.png" alt="" width="69" height="57" /></h5>
&nbsp;
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
We propose a novel method for establishing correspondences on deformable objects for single-target object tracking. The key ingredient is a dissimilarity measure between correspondences that takes into account their geometric compatibility, allowing us to separate inlier correspondences from outliers. We employ both static correspondences from the initial appearance of the object as well as adaptive correspondences from the previous frame to address the stability-plasticity dilemma. The geometric dissimilarity measure enables us to also disambiguate keypoints that are difficult to match. Based on these ideas we build a keypoint-based tracker that outputs rotated bounding boxes. We demonstrate in a rigorous empirical analysis that this tracker outperforms the state of the art on a dataset of 77 sequences. <a href="https://epics.uni-paderborn.de">fp7-epics</a> <a href="https://www.cv-foundation.org/openaccess/content_cvpr_2015/html/Nebehay_Clustering_of_Static-Adaptive_2015_CVPR_paper.html">CvF</a>
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
