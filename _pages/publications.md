---
layout: page
title: publications
index: 2
permalink: /publications/
description: For the complete list of publications, check my Google Scholar or Semantic Scholar profile.
years: [2020, 2021]
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
