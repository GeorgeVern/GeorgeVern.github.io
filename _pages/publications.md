---
layout: page
title: publications
permalink: /publications/
description: 
years: [2022, 2021, 2020]
nav: true
---
<<<<<<< HEAD

For the complete list of publications, check my [Google Scholar](https://scholar.google.com/citations?user=1AgA0_YAAAAJ&hl=en) or [Semantic Scholar](https://www.semanticscholar.org/author/Giorgos-Vernikos/1972392392) profile.

=======
<!-- _pages/publications.md -->
>>>>>>> b950fc3 (Better SEO, OpenGraph, schema.org and clean generated code (#481))
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
