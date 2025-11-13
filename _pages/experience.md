---
layout: page
permalink: /experience/
title: Experience
description: Professional experience and work history.
years: [2025, 2024, 2022, 2020]
nav: false  # Set to true to enable in navigation
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

<h1>preprints</h1>

{% bibliography -f preprints %}

<h1> peer reviewed </h1>

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}



<h1>posters</h1>

{% bibliography -f posters %}

</div>


