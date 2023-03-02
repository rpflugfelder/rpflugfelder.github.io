---
layout: page
title: Research on Dynamic Perception and Understanding
comments: true
---

<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/pace/1.0.2/pace.min.js"></script>

My scientific interest lies in visual motion analysis and tracking and in the importance of motion perception in object recognition and scene understanding. I currently focus in my research on the problem of fragmented and dynamic occlusion in machine and human vision.

# Fragmented and Dynamic Occlusion

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

# Object Detection

<figure>
  <img src="/assets/images/car.png" height="240" width="320" alt="Car Image" data-alt="/assets/images/car.gif">
  <figcaption>Motion helps a detector to aquire online a robust representation (green circles) of a car starting from an initial bounding box (<a href="https://doi.org/10.1109/WACV.2014.6836013">WACV'14</a>, <a href="https://doi.org/10.1109/CVPR.2015.7298895"> CVPR'15</a>).</figcaption>
</figure>

<figure>
  <img src="/assets/images/sat.png" height="320" width="320" alt="Sat Image" data-alt="/assets/images/sat.gif">
  <figcaption>Vehicles are reliably detected in satellite images by using motion (<a href="https://arxiv.org/abs/2204.06828">arXiv'22</a>, <a href="https://data.vicos.si/cvww20/05.pdf"> CVWW'20</a>).</figcaption>
</figure>

# Simultaneous Localisation and Tracking (SLAT), Camera Calibration

<figure>
  <img src="/assets/images/socp.png" height="252" width="320" alt="Socp Image" data-alt="/assets/images/socp.gif">
  <figcaption>Motion of a person gives clues for the calibration of multiple security cameras with non-overlapping fields of view (
    <a href="https://doi.org/10.1007/978-3-642-15986-2_3">DAGM'10</a>,
    <a href="https://doi.org/10.1109/TPAMI.2009.56">IEEE TPAMI</a>,
    <a href="https://doi.org/10.1109/CVPR.2010.5540028">CVPR'10</a>,
    <a href="https://doi.org/10.1109/CVPR.2011.5995534">CVPR'11</a>,
    <a href="https://doi.org/10.1109/ICCV.2011.6126334">ICCV'11</a>) ...
  </figcaption>
</figure>

<figure>
  <img src="/assets/images/sfm.png" height="202" width="320" alt="Sfm Image" data-alt="/assets/images/sfm.gif">
  <figcaption>... as well as structure from motion captured by an additional moving camera (
    <a href="https://patents.google.com/patent/AT511968B1/en">AT Patent</a>,
    <a href="https://doi.org/10.1109/3DV.2013.27">3DV'13</a>,
    <a href="https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=b633f72c732569110b26efaa87d87a3cf2641960">ECCVW'14</a>).
  </figcaption>
</figure>


# Further Examples

<figure>
  <img src="/assets/images/heeger.png" height="240" width="320" alt="3D Image" data-alt="/assets/images/heeger.gif">
  <figcaption>Motion let us perceive depth and many more things! For more examples, visit D. Heeger's <a href="http://www.cns.nyu.edu/~david/courses/perception/lecturenotes/motion/motion.html">webpage</a>.</figcaption>
</figure>

<script src="/js/script-min.js"></script>

***

<figure>
  <img class="alignleft" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/af/Under_construction_icon-yellow.svg/291px-Under_construction_icon-yellow.svg.png" alt="" width="69" height="57" />
  <figcaption>My research profile is under construction.</figcaption>
</figure>

<!--
***

{% if page.comments %}
<div id="disqus_thread"></div>
<script>
    /**
    *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
    *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables    */
    
    var disqus_config = function () {
    this.page.url = https://rpflugfelder.github.io;  // Replace PAGE_URL with your page's canonical URL variable
    this.page.identifier = /research; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };
    
    (function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = 'https://rpflugfelder-github-io.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
{% endif %}




Other research [work](research.md) in other areas of vision.

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



<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/pace/1.0.2/pace.min.js"></script>

Please move your mouse pointer (or finger) over the image and click the left mouse button (or touch your display) to start the animation and to perceive motion.

***

<figure>
  <img src="/assets/images/pnd.png" height="240" width="320" alt="Frag Image" data-alt="/assets/images/pnd.gif">
  <figcaption>I developed a monocular calibration algorithms and showed that calibration of security cameras allows better person re-identification (<a href="https://diglib.tugraz.at/download.php?id=577a025937213&location=browse">PhD thesis</a>).</figcaption>
</figure>

<script src="/js/script-min.js"></script>
-->

