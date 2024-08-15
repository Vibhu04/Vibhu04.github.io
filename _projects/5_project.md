---
layout: page
title: Visual Saliency Map Translation
description: Personal research project  
img: assets/img/vs.png
importance: 2
category: fun
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/vs_cover.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Example outputs from the Visual Saliency Translator.
</div>

During my research internship at DREAM Lab (University of Illinois Urbana-Champaign), I collaborated with [Dr. Haohan Wang](https://haohanwang.github.io/) on a project aimed at enhancing the interpretability of Convolutional Neural Networks (CNNs). Like other deep neural networks, CNNs suffer from a lack of interpretability and transparency, making it difficult to understand the rationale behind their predictions—a phenomenon often likened to a 'black box'. This lack of interpretability poses risks when deploying CNNs for critical tasks, as it is challenging to predict when or why the model might make an inaccurate prediction. The study of improving interpretability in machine learning models falls under the field of Explainable AI, in which [Dr. Haohan Wang](https://haohanwang.github.io/) is a leading researcher.  

The Visual Saliency Translator we designed consists of two key components:
- A visual saliency map generator, which identifies the regions of the input image most relevant or important to the model's prediction.
- An image-to-text model, which takes the output of the visual saliency generator and produces a textual explanation of the visual saliency map.

We experimented with the family of [GradCAM](https://arxiv.org/abs/1610.02391) models as our visual saliency map generators. These models, given a CNN and an input image, produce a heatmap that highlights the crucial regions of the image in relation to the CNN's predictions. For the image-to-text model, we used the [BLIP](https://arxiv.org/abs/2201.12086) model. Examples of the final results from the entire pipeline are illustrated at the top.



Access the code repository on Github [here](https://github.com/Vibhu04/Saliency-Map-Translation).

Access the Google Slides document, which contains the project elements, [here](https://docs.google.com/presentation/d/1KbaGFRb2mKC1iR1XBGqDzyzhdvCFhQnXy0GpsowUe_s/edit?usp=sharing).