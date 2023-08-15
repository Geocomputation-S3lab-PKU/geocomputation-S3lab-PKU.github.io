---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016]
nav: true
---

[[Google scholar](https://scholar.google.com/citations?user=BUFSF_8AAAAJ&hl=en)] | [[ResearchGate](https://www.researchgate.net/profile/Zhou-Huang-3)] | [[View by topic](https://pku-geocomp.com/research/)]

#### Papers

<div class="publications">

{% for y in page.years %}
  <div>{{y}}</div>
  {% bibliography -f hz_refs -q @*[year={{y}}]* %}
{% endfor %}

</div>
