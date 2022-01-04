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
<iframe width="764" height="430" src="https://www.youtube.com/embed/CDIyYijAyyU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

<p align="center">
<b>
<a href="https://arxiv.org/abs/2011.03384">[Paper]</a>  <a href="https://github.com/niuchuangnn/noise2sim">[Code]</a>  <a href="https://github.com/niuchuangnn/noise2sim">[Data]</a>
</b>
</p>


<h2>Introduction</h2>

<p style="text-align:justify;font-size:20px">
Noise2Sim is the first similarity-based unsupervised deep denoising approach using noisy images only,
suppressing not only independent but also correlated noises.
Theoretically, Noise2Sim is equivalent to supervised denoising under mild conditions.
On common benchmarks and practical CT datasets,
Nosie2Sim recovers intrinsic structures from noisy low-dose and photon-counting CT images 
as effectively as or even better than the supervised learning methods.
Read <a href="https://arxiv.org/abs/2011.03384">Paper</a> for more details.
</p>

<h2>Installation</h2>
<p style="text-align:justify;font-size:20px">
Noise2Sim package can be easily installed using <code>pip install noise2sim</code>.
Note that <a href="https://arxiv.org/abs/2011.03384">Pytorch</a> is required.
The source code are available at <a href="https://github.com/niuchuangnn/noise2sim">GitHub</a>.
</p>

<h2>Datasets</h2>
<p style="text-align:justify;font-size:20px">
Noise2Sim has the potential in various applications.
Here Noise2Sim was applied to denoising natural images with independent noise,
low-dose CT (LDCT) and photon-counting CT (PCCT) images with correlated noises.
All datasets can be freely accessed as follows.
</p>

<p style="text-align:justify;font-size:20px">
<b>Natural Images (grayscale):</b>
</p>

<p style="text-align:justify;font-size:20px">
<b>Natural Images (color):</b>
</p>

<p style="text-align:justify;font-size:20px">
<b>LDCT Data (Mayo):</b>
</p>

<p style="text-align:justify;font-size:20px">
<b>LDCT Data (FDA):</b>
</p>

<p style="text-align:justify;font-size:20px">
<b>PCCT Data (chicken drumstick):</b>
</p>

<p style="text-align:justify;font-size:20px">
<b>PCCT Data (live mouse):</b>
</p>

<p style="text-align:justify;font-size:20px">
<b>PCCT Data (died mouse):</b>
</p>




<h2>Tutorial</h2>
Detail instructions for using Noise2Sim package are <a href="https://github.com/niuchuangnn/noise2sim">Here</a>.


