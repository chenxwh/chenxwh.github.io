---
layout: page
permalink: /publications/
title: Publications

years: [2022]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

<h2> Conference Papers </h2>

{%- for y in page.years %}

  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

<h2> Preprints </h2>

</div>
