---
layout: page
permalink: /publications/
title: publications
description: 
years: [2022, 2021, 2020, 2019]
nav: true
---

<div class="publications">

{% for y in page.years %}
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
