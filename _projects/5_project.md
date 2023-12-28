---
layout: page
short_title: MMGC Contest Developer
title: 2022 MMGC Contest Organizer and Developer
description: Tsinghua University
img: assets/img/stream_simulator.jpeg
importance: 4
category: Work
related_publications: zuo2022bandwidthefficient
---

Advisor: [Yong Cui](http://www.cuiyong.net/index.html), <i>Professor at Department of Computer Science and Technology, Tsinghua University</i>

Applications that allow sharing of user-created short videos exploded in popularity in recent years. Solutions to reduce bandwidth waste without impairing the Quality of Experience (QoE) are needed. Solving the problem requires adaptively prefetching of short video chunks, which is challenging as the download strategy needs to match unknown user viewing behavior and network conditions. 

In our work, we first formulate the problem of adaptive multi-video prefetching in short video streaming. And we design and implement a [discrete-event simulator](https://github.com/AItransCompetition/Short-Video-Streaming-Challenge) to facilitate the integration and comparison of researchers’ algorithms towards solving the problem. We organized and coordinated the 2022 MMGC Contest and analyzed the contestants' algorithms in hope of promoting the research community towards addressing this problem.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/system.jpeg" title="System overview" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The system overview for short video streaming.
</div>


- Organized and coordinated the 2022 Multi-Media Grand Competition focusing on designing short video preload algorithms to balance between bandwidth wastage and quality of user experience.
- Built and maintained a simulator that can test all the submitted algorithms
- Implemented baseline preload algorithms.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/stream_simulator.jpeg" title="Streaming Simulator" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overview of short video streaming simulator.
</div>

