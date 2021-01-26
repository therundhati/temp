---
layout: page
permalink: /publications/
title: Publications
description: publications by categories in reversed chronological order.
years: [1956, 1950, 1935, 1905]
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  <!-- a normal html comment 
  {% bibliography -f papers -q @*[year={{y}}]* %} -->
{% endfor %}

</div>
