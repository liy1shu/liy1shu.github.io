---
layout: page
short_title: Motion Planning
title: Solving Multimodal Open Action Planning With Diffusion
description: CMU Robotics Institute
img: assets/img/task.jpeg
importance: 1
category: Research
---

Advisor: [David Held](http://davheld.github.io), <i>Associate Professor at Robotics Institute, Carnegie Mellon University</i>

Investigated on planning to open objects from pure RGB-D observations with diffusion models. Use diffusion model to better represent ambiguity and multimodal action space. Disambiguous diffusion results with history-conditioned structure to predict correct and temporally consistent results.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/task.jpeg" title="Real-world Task" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/flow.jpeg" title="flow definition" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/simulation.jpeg" title="Simulation Environment" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, the real-world task examples. Middle, predicted action flow definition. Right, simulation environment in pybullet.
</div>

While regression models have shown great potential in solving these problems, they have difficulties handling ambiguous datasets. For example, doors with similar geometries could yield different open directions (e.g. push and pull) which is confusing even to humans. If trained on door datasets with similar geometry but various open directions, regression models could easily fail to converge. Unlike traditional regression models, diffusion models are good at fitting multi-modal distributions. With manually selected ambiguous datasets, we have shown that diffusion-based methods are capable of preserving multiple possible solutions and have notably outperformed regression methods by a large margin. Currently, we are working on combining this multi-modal predictor with history- and feedback-aware planner to disambiguate the predicted possible actions.

- Developed a generalizable algorithm which plans the ‘open’ action from a pure, single-view RGB observation.
- Built a simulation environment that can handle simulating manipulation on objects using a suction gripper.
- Utilized diffusion models to better address ambiguity issues in articulative objects.

The multimodal diffusion process visualization example:

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/diffusion.jpeg" title="Diffusion Visualization" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    When given a fully closed ambiguous door, the trained diffusion model can make multimodal predictions starting from different random noises.
</div>
