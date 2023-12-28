---
layout: page
short_title: 3D Scene Recon
title: Joint 3D Reconstruction of Semantic and Geometry
description: Tsinghua University
img: assets/img/3drecon.jpeg
importance: 3
category: Research
---

Advisor: [Yongjin Liu](http://cg.cs.tsinghua.edu.cn/people/~Yongjin/Yongjin.htm), <i>Professor at Department of Computer Science and Technology, Tsinghua University</i>

Built an end-to-end network that jointly reconstructs 3D geometry and semantics under multi-view settings. We came up with a new coarse-to-fine method that iteratively optimizes the ray depth prediction and the 3D feature space, as predicted ray depths could pose constraints to 2D-to-3D feature projection and more precise 3D feature spaces can be processed into more accurate ray depths. Using this two-way approach, we were able to explicitly fuse visual and semantic information and finally came up with more accurate reconstruction results than previous models.

- Investigated the combination of 3D geometry reconstruction and semantic labeling of 3D voxels.
- Introduced the multi-view feature correlation to achieve robust 2D to 3D feature fusion under occlusion, mitigating the feature ambiguity problem introduced by feature averaging in previous works.
- Proposed a two-branch 3D voxel network to jointly reconstruct and label the voxels.
- Achieved smooth and accurate 3D reconstruction and semantic labeling.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3drecon.jpeg" title="Reconstruction Example" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This is a reconstruction example with geometric mesh and also semantic labels represented by different colors.
</div>