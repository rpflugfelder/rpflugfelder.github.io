---
layout: page
title: Combined Detection and Tracking
---

We propose a novel method for establishing correspondences on deformable objects for single-target object tracking. The key ingredient is a dissimilarity measure between correspondences that takes into account their geometric compatibility, allowing us to separate inlier correspondences from outliers. We employ both static correspondences from the initial appearance of the object as well as adaptive correspondences from the previous frame to address the stability-plasticity dilemma. The geometric dissimilarity measure enables us to also disambiguate keypoints that are difficult to match. Based on these ideas we build a keypoint-based tracker that outputs rotated bounding boxes. We demonstrate in a rigorous empirical analysis that this tracker outperforms the state of the art on a dataset of 77 sequences. <a href="https://epics.uni-paderborn.de">fp7-epics</a> <a href="https://www.cv-foundation.org/openaccess/content_cvpr_2015/html/Nebehay_Clustering_of_Static-Adaptive_2015_CVPR_paper.html">CvF</a>
