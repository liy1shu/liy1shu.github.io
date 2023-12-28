---
layout: page
short_title: 6D Pose Estimation
title: 6D Object Pose Estimation (Course Project)
description: <3D Visual Computing>, Tsinghua University
img: assets/img/icp.jpeg
importance: 4
category: Course
---

Advisor: [Li Yi](https://ericyi.github.io), <i>Assistant Professor at Institute of Interdisciplinary Information Science, Tsinghua University</i>

Completed the 6D pose estimation of objects given the observed point cloud and an initial position point cloud with both analytical method and learning method. The observations may have occlusions and deficiencies. 

- Implemented the classic ICP algorithms to mathematically calculate the rotation and translation parameters.
- Trained a object-specific neural network to predict 6D pose based on the two input point clouds.
- Conducted analysis on the pros and cons of each methods.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/icp.jpeg" title="icp examples" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    ICP examples of aligning 2 point clouds. Failure cases have shown that ICP is sensitive to initial positions and may converge to wrong alignments.
</div>