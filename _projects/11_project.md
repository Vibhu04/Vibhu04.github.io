---
layout: page
title: Implementation of 3D human pose estimation research paper
description: Collaborative project
img: assets/img/xnect.jpg
importance: 4
category: 
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/xnect.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>  
<div class="caption">
    Overview of the 3D human pose estimation pipeline
</div>

During my internship at Telekinesis AI, I collaborated with a teammate to read and implement a research paper on 3D Human Pose Estimation. The paper, titled "XNect: Real-time Multi-Person 3D Motion Capture with a Single RGB Camera" by Mehta et al., introduces a real-time approach for multi-person 3D pose estimation. It consists of three stages and introduces a novel CNN architecture called SelecSLS Net. More information about the paper can be found [here](https://vcai.mpi-inf.mpg.de/projects/XNect/).

Our project involved thoroughly understanding each section of the paper and implementing its methodology from scratch in Python. We also trained the PyTorch model we had developed using the same datasets and configurations specified in the paper. The results we obtained were comparable to those reported by the authors.


