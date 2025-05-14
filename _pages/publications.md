---
layout: page
permalink: /publications/
title: publications
description: Publications in reverse chronological order.
years: [2025, 2024, 2023, 2022, 2021, 2020, 2019, 2018]
types: [papers, theses]
nav: true
---

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

<br/>
<h2 class="publications">{{"theses"}}</h2>
<h2 class="year"></h2>
<br/><br/>
{% bibliography -f theses %}

</div>
