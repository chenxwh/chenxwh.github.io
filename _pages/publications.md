---
layout: page
permalink: /publications/
title: Publications

years: [2024, 2023, 2022]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

* indicates Equal Contribution.

<!-- <h2> Conference Papers </h2> -->

{%- for y in page.years %}
<h4 class="year">{{y}}</h4>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}


</div>
