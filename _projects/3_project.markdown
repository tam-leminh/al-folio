---
layout: page
title: publications
description: This is an outdated publication pages
importance: 2
category: work
years: [2024, 2023, 2022, 2021, 2020, 2019]
---

## Preprints (submitted)

<div class="publications">

{% for y in page.years %}
  {% bibliography -f hidden -q @*[year={{y}}]* %}
{% endfor %}

</div>
