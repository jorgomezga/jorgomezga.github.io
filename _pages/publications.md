---
layout: page
permalink: /publications/
title: publications
description:
years: [2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014, 2010, 2008]
years_thesis: [2018, 2008]
yeats_conf: []
nav: true
nav_order: 0
---


Thesis
--------------------
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years_thesis %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f thesis -q @*[year={{y}}]* %}
{% endfor %}

</div>



Papers
--------------------

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>


Conferences
--------------------

<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f conferences -q @*[year={{y}}]* %}
{% endfor %}

</div>