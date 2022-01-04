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
<b>Natural Images (grayscale):</b> <a href="https://github.com/niuchuangnn/noise2sim/tree/master/datasets/Train400">BSD400</a>
and <a href="https://drive.google.com/drive/folders/1b_RvBwIr9yLg8yPWb0BHYmWiOEVUvG4K?usp=sharing">BSD68</a>.
</p>

<p style="text-align:justify;font-size:20px"> 
<b>Natural Images (color):</b> <a href="http://www.eecs.berkeley.edu/Research/Projects/CS/vision/bsds/">BSD500</a>
and <a href="http://www.cs.albany.edu/~xypan/research/snr/Kodak.html">Kodak</a>.
</p>

<p style="text-align:justify;font-size:20px">
<b>LDCT Data (Mayo):</b> <a href="http://www.aapm.org/grandchallenge/lowdosect/">Mayo</a>.
</p>

<p style="text-align:justify;font-size:20px">
<b>LDCT Data (FDA):</b> <a href="https://www.cancerimagingarchive.net/viewer/?study=1.3.12.2.1107.5.1.4.60175.30000008042114404745300000016&series=1.3.12.2.1107.5.1.4.60175.30000008042113424165600232150&token=653e92d2-78d2-4f49-8a4e-bc169676afac">LDCT-b40f</a>,
<a href="https://www.cancerimagingarchive.net/viewer/?study=1.3.12.2.1107.5.1.4.60175.30000008042114404745300000004&series=1.3.12.2.1107.5.1.4.60175.30000008042113424165600181551&token=653e92d2-78d2-4f49-8a4e-bc169676afac">NDCT-b40f</a>,
<a href="https://www.cancerimagingarchive.net/viewer/?study=1.3.12.2.1107.5.1.4.60175.30000008042114404745300000016&series=1.3.12.2.1107.5.1.4.60175.30000008042113424165600232848&token=653e92d2-78d2-4f49-8a4e-bc169676afac">LDCT-b60f</a>,
<a href="https://www.cancerimagingarchive.net/viewer/?study=1.3.12.2.1107.5.1.4.60175.30000008042114404745300000004&series=1.3.12.2.1107.5.1.4.60175.30000008042113424165600180853&token=653e92d2-78d2-4f49-8a4e-bc169676afac">NDCT-b60f-1</a>,
<a href="https://www.cancerimagingarchive.net/viewer/?study=1.3.12.2.1107.5.1.4.60175.30000008042114404745300000004&series=1.3.12.2.1107.5.1.4.60175.30000008042113424165600182490&token=653e92d2-78d2-4f49-8a4e-bc169676afac">NDCT-b60f-2</a>.
</p>

<p style="text-align:justify;font-size:20px">
<b>PCCT Data (chicken drumstick):</b> <a href="https://drive.google.com/file/d/1x6uaSWgEoQw9ZINVfnOc_MxKjZHmY0MP/view?usp=sharing">LDPCCT</a>,
<a href="https://drive.google.com/file/d/1bV0n8L6AbeXLIUY_9lvTL7Tvvmhx3NQT/view?usp=sharing">NDPCCT</a>,
and <a href="https://drive.google.com/file/d/14n7IGVLsGBoRRiZ1Gps78wLP_lpU6ADQ/view?usp=sharing">NDPCCT-reference</a>.
</p>

<p style="text-align:justify;font-size:20px">
<b>PCCT Data (live mouse):</b> <a href="https://drive.google.com/file/d/10fQIxurCiLips0pc5sut_qtGDHWclSOG/view?usp=sharing">NDPCCT</a>.
</p>

<p style="text-align:justify;font-size:20px">
<b>PCCT Data (died mouse):</b> <a href="https://drive.google.com/file/d/1UaS6YdPZ_M0opxpIaUXjbydNq1IlVDiG/view?usp=sharing">NDPCCT</a>.
</p>


<h2>Tutorial</h2>
<p style="text-align:justify;font-size:20px">
Detail instructions including training and testing denoising models with Noise2Sim package are <a href="https://github.com/niuchuangnn/noise2sim">here</a>.
</p>

<h2>Simple training process derived from Noise2Sim theorem</h2>

{% include figure.html path="assets/img/ct-search.png" title="CT" class="img-fluid rounded z-depth-1" %}
<p style="text-align:justify;font-size:20px">
Noise2Sim training process on LDCT and PCCT.
The similar volumes along the slice direction are selected to construct training samples,
where the dissimilar vectors identified in a mask image are excluded during training.
</p>

{% include figure.html path="assets/img/nisearch.png" title="Natural Image" class="img-fluid rounded z-depth-1" %}
<p style="text-align:justify;font-size:20px">
Noise2Sim training process on 2D images with independent noise.
Step 1 is to search for a set of k similar pixels for each pixel in the original noisy image,
and form $k$ most similar images, which is also referred to as nearest images.
Step 2 is to randomly construct a pair of similar images as the input and the target to train a convolutional neural network (CNN).
</p>

