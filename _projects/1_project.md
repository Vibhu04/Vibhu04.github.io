---
layout: page
title: Short-Time Fourier Transform for deblurring Variational Autoencoders
description: Personal research project
img: assets/img/vae3.png
importance: 1
category: work
related_publications: false
---


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/vae2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A typical Variational Autoencoder architecture.
</div>

Variational Autoencoders (VAEs) are powerful generative models, with strong probabilistic fonudations. However their generated samples are known to suffer from a characteristic blurriness, as compared to the outputs of alternative generating techniques. Extensive research efforts have been made to tackle this problem, and several works have focused on modifying the reconstruction term of the evidence lower bound (ELBO). In particular, many have experimented with augmenting the reconstruction loss with losses in the frequency domain. Such loss functions usually employ the Fourier transform to explicitly penalise the lack of higher frequency components in the generated samples, which are responsible for sharp visual features. In this paper, I explore the aspects of previous such approaches which aren't well understood, and propose an augmentation to the reconstruction term in response to them. The reasoning laid out in the paper hints to use the short-time Fourier transform and to emphasise on local phase coherence between the input and output samples. I illustrate the potential of my proposed loss on the MNIST dataset by providing both qualitative and quantitative results.



Access the research manuscript uploaded to Arxiv [here](https://arxiv.org/abs/2401.03166).

Access the code repository on Github [here](https://github.com/Vibhu04/Deblurring-Variational-Autoencoders-with-STFT).



