---
layout: page
permalink: /publications/
title: publications
description: Some work placed here, more coming soon.
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} %}

<!-- Adding a direct link to a local publication -->
<a href="{{ site.baseurl }}/assets/pdf/dlai_batchnorm_marcus_henriksboe_2022.pdf" target="_blank">Report in Deep Learning at Sapienza Spring 2022 - Training BatchNorm and Only BatchNorm: Affine parameter effects in MLP’s</a>

<br><br>

<!-- Adding a direct link to a publication -->
<a href="{{ site.baseurl }}/assets/pdf/crpmlcourse-paper1242.pdf" target="_blank">Report in Machine Learning Fall 2021 at EPFL - Finding meaning in autogenerated text</a>

</div>