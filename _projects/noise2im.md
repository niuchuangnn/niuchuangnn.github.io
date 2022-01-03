---
layout: page
title: Noise2Sim
description: An unsupervised deep denoising method.
img: assets/img/noise2sim.png
importance: 1
category: work
---

<head>
<style>
code {
  font-family: Consolas,"courier new";
  color: crimson;
  background-color: #f1f1f1;
  padding: 2px;
  font-size: 105%;
}
</style>
</head>

<p align="center">
<iframe width="672" height="378" src="https://www.youtube.com/embed/G1RJV7h9YhE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

<p align="center">
<b>
<a href="https://arxiv.org/abs/2011.03384">[Paper]</a>  <a href="https://github.com/niuchuangnn/noise2sim">[Code]</a>  <a href="https://github.com/niuchuangnn/noise2sim">[Data]</a>
</b>
</p>


<h2>Introduction</h2>

<p style="text-align:justify;font-size:24px">
Noise2Sim is the first similarity-based unsupervised deep denoising approach using noisy images only,
Noise2Sim can suppress not only independent but also correlated noises.
Theoretically, Noise2Sim is equivalent to supervised denoising under mild conditions.
Experimental results on common benchmarks and practical CT datasets show that
Nosie2Sim recovers intrinsic structures from noisy low-dose and photon-counting CT images,
and is competitive to or even better than the supervised learning methods.
Read <a href="https://arxiv.org/abs/2011.03384">Paper</a> for more details.
</p>

<h2>Installation</h2>
<p style="text-align:justify;font-size:24px">
Assuming <a href="https://arxiv.org/abs/2011.03384">Pytorch</a> is installed,
"nois2sim" package can be easily installed using <code>pip install noise2sim</code>.
</p>

<h2>Datasets</h2>

<h2>Tutorial</h2>

