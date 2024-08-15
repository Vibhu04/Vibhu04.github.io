---
layout: page
title: 2D Hand Pose Estimation
description: Collaborative research project
img: assets/img/color_seg.gif
importance: 3
category: 
---


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/color_seg.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Example output from our real-time 2D hand pose estimation algorithm
</div>

During my internship at Telekinesis AI, I collaborated with another team member on a research project aimed at developing a real-time 2D hand pose estimation algorithm using color segmentation and clustering methods. Specifically, the task of 2D hand pose estimation consists of accurately estimating key points on the palm and fingers (e.g., the base of the index finger) and labeling them correctly.

The first step involved conducting a literature review of existing real-time 2D hand pose estimation algorithms and assessing the advantages and drawbacks of each technique. After this review, we designed a novel pipeline that incorporated ideas from the research papers we studied, as well as some new techniques. The main clustering algorithm we employed was DBSCAN, and we experimented with variants of HSV segmentation. The end results were encouraging, considering the straightforward and lightweight aspects of our approach.