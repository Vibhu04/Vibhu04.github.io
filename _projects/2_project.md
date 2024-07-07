---
layout: page
title: Dataset Distillation via the Wasserstein metric 
description: Collaborative research project
img: assets/img/wasss.png
importance: 2
category: work
giscus_comments: false
---


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/wass_samples.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Visualizations of our synthetic images from ImageNet-1K
</div>

During my research internship at DREAM Lab (University of Illinois Urbana-Champaign), I collaborated on a project aimed at tackling the task of dataset distillation by incorporating concepts from optimal transport theory, specifically the Wasserstein metric and the Wasserstein barycenter.

Below is the abstract of the research manuscript for the project:

Dataset Distillation (DD) emerges as a powerful strategy to encapsulate the expansive information of large datasets into significantly smaller, synthetic equivalents, thereby preserving model performance with reduced computational overhead. Pursuing this objective, we introduce the Wasserstein distance, a metric grounded in optimal transport theory, to enhance distribution matching in DD. Our approach employs the Wasserstein barycenter to provide a geometrically meaningful method for quantifying distribution differences and capturing the centroid of distribution sets efficiently. By embedding synthetic data in the feature spaces of pretrained classification models, we facilitate effective distribution matching that leverages prior knowledge inherent in these models. Our method not only maintains the computational advantages of distribution matching-based techniques but also achieves new state-of-the-art performance across a range of high-resolution datasets. Extensive testing demonstrates the effectiveness and adaptability of our method, underscoring the untapped potential of Wasserstein metrics in dataset distillation.

Access the full research manuscript [here](https://arxiv.org/abs/2311.18531).