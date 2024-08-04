---
layout: page
title: Video Anomaly Detection for Laboratory Automation
description: Collaboraive research project
img: assets/img/anomaly.png
importance: 3
category: fun
---


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/anomaly_figure.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Visualization of different video frames in a typical ROI of an anomalous video, and their corresponding predicted saliency scores
</div>


During my research internship at Carnegie Mellon University, I co-authored a research paper on developing a machine learning model for detecting anomalies in video data within a laboratory setting.

Below is the abstract of the research manuscript for the project:

Laboratory automation integrates robotics, machine learning, and computer vision to enhance precision and efficiency while reducing costs. Despite its pivotal importance in fully automated experimentation, automatic monitoring of procedures is an overlooked task. In this paper, we aim to address this shortcoming by developing a learning method for detecting anomalies in the laboratory setting. To formalize the problem, we focus on the liquid transfer task as a major task in laboratory automation, given the frequent need for reagent mixing and solution preparation. We introduce a novel video anomaly detection framework that leverages the robust CLIP features in conjunction with a transformer encoder. Through an array of experiments and ablation studies, we demonstrate that our proposed method surpasses current state-of-the-art anomaly detection techniques by a notable margin of over 11%, achieving an impressive AUC of 98.79% for video-level anomaly detection

Access the full research manuscript [here](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4887151).
