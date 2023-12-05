---
layout: page
short_title: HOI Video Understanding
title: Generalizable Spatio-Temporal Grounding in Hand-Object-Interaction Videos
description: Tsinghua University
img: assets/img/hoi_task.jpeg
importance: 2
category: Research
---

Advisor: [Li Yi](https://ericyi.github.io), <i>Assistant Professor at Institute of Interdisciplinary Information Science, Tsinghua University</i>

Investigated on building an end-to-end spatio-temporal HOI video grounding and it's generalization ability to new actions, new objects and new compositions. Design intermediate representation to guide the finetuning process pretrained general vision-language models, making the model focus more on the essence of the active interaction part and distill more generalizable features. To validate the comparison on generalization, we carefully split the dataset into 4 training sets and 1 test set. Except the in-dataset training set, the other 3 training sets all hold specific domain gaps with the test set: unseen objects, unseen actions and unseen compositions of seen nouns and verbs. Our methods have shown generalization ability across different settings.

- Built a pipeline capable of spatio-temporal segmentation given an input video and a verb-noun interaction query that can distinguish the interactive instance from background objects.
- Defined an intermediate representation to bridge spatial and temporal segmentation and encouraged utilizing the hand and object relationship to achieve better generalizability.
- Designed a set of generalization tests using a carefully split dataset and conducted generalization comprehensive testing on our new method and various existing methods.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/toycar.jpeg" title="toycar spatial example" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/chair.jpeg" title="chair spatial example" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cups.jpeg" title="cups spatial example" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Spatial segmentation visualizations. Yellow means higher probability of being classified to the interactive part.
</div>

Temporal results are produced but visualizations aren't ready yet. On the method part, we are currently still working on improvements on the overall structure or detailed intermediate representation designs that might yield better generalization abilities.
