---
layout: page
permalink: /publications/
title: papers
description: working papers and publications
years: [2023,2021,2020,2019,2018,2017,2016]
nav: true
nav_order: 3
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
 