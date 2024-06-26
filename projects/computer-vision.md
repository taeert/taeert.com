---
layout: page
title: Computer Vision
subtitle: Making the machines see the world as we do!
cover-img: /assets/img/projects/computer-vision.png
thumbnail-img: /assets/img/projects/computer-vision.png
tags: [computer vision, AI, machine learning, deep learning]
author: Taewoon Kim
comments: true
---

# [Generalizing MLPs with dropouts, batch normalization, and skip connections](https://arxiv.org/abs/2108.08186)

<!-- padding-bottom: 56.25% is for 16:9. For an aspect ratio of 1:1 change to this value to 100% */  -->
<div style="position: relative; padding-bottom: 56.25%">
  <iframe
    style="width: 100%; height: 100%; position: absolute; left: 0px; top: 0px"
    frameborder="0"
    width="100%"
    height="100%"
    allowfullscreen
    allow="autoplay"
    src="
      https://www.youtube.com/embed/Dna_Hp-s78I?si=ZnsOq6I3jVY9A9gu
   "
  >
  </iframe>
</div>

A multilayer perceptron (MLP) is typically made of multiple fully connected
layers with nonlinear activation functions. There have been several approaches
to make them better (e.g. faster convergence, better convergence limit, etc.).
But the researches lack structured ways to test them. We test different MLP
architectures by carrying out the experiments on the age and gender datasets.
We empirically show that by whitening inputs before every linear layer and
adding skip connections, our proposed MLP architecture can result in better
performance. Since the whitening process includes dropouts, it can also be
used to approximate Bayesian inference. We have open-sourced our code, and
released models and docker images at [https://github.com/tae898/age-gender/](https://github.com/tae898/age-gender/)

# [Room classifier](https://github.com/tae898/room-classification)

<!-- padding-bottom: 56.25% is for 16:9. For an aspect ratio of 1:1 change to this value to 100% */  -->
<div style="position: relative; padding-bottom: 56.25%">
  <iframe
    style="width: 100%; height: 100%; position: absolute; left: 0px; top: 0px"
    frameborder="0"
    width="100%"
    height="100%"
    allowfullscreen
    allow="autoplay"
    src="
    https://www.youtube.com/embed/cM01mHaAtNA?si=FQav-tAgMyDB3Ua3
   "
  >
  </iframe>
</div>
