---
layout: page
title: publications
index: 2
permalink: /publications/
description: For the complete list of publications, check my [Google Scholar](https://scholar.google.com/citations?user=1AgA0_YAAAAJ&hl=en) or [Semantic Scholar](https://www.semanticscholar.org/author/Giorgos-Vernikos/1972392392) profile.
years: [2021, 2020]
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
