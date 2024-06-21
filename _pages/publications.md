---
layout: page
permalink: /publications/
title: publications
description: Full list at <a href="https://scholar.google.com/citations?user=aoud5NgAAAAJ">Google Scholar </a>
years: [2024, 2023, 2022, 2021, 2020, 2019, 2018]
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
