---
layout: page
title: Transfer Learning Toolkit for Large Language Models
description: Python library
img: assets/img/tl_graph.png
importance: 1.5
category: work
giscus_comments: false
---



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/adapter.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Diagram of a typical adapter unit used in parameter-efficient transfer learning for large language models.
</div>


Transfer Learning refers to the process of applying knowledge gained from pre-training on one task to improve the performance of another related task. In NLP, this involves utilizing pre-trained language models that have been trained on large-scale datasets, such as general language understanding or translation, and then fine-tuning them for specific NLP tasks, such as sentiment analysis or named entity recognition. This is typically achieved through fine-tuning some or all parameters of a pre-trained language model on a dataset relevant to the task. However, there are several other transfer learning techniques for NLP that have been explored in academia, such as adapter-tuning or prefix-tuning.

I read numerous research papers on transfer learning for large language models, and during the process decided to create a Python library that enables users to implement various transfer learning techniques on their models. The Python library, named <b>plamtral</b>, comprises of 12 transfer learning techniques, consisting of both fine-tuning and parameter-efficient approaches. 

You can explore the main page of the library [here](https://pypi.org/project/plamtral/).





