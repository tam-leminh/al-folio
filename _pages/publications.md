---
layout: page
permalink: /publications/
title: publications
description: 
years: [2025, 2024, 2023, 2022, 2021, 2020, 2019]
nav: true
---

## Preprints (submitted)

<div class="publications">

{% for y in page.years %}
  {% bibliography -f preprints -q @*[year={{y}}]* %}
{% endfor %}

</div>

## Published papers

<div class="publications">

{% for y in page.years %}
  {% bibliography -f published -q @*[year={{y}}]* %}
{% endfor %}

</div>

## PhD thesis

<div class="publications">

{% bibliography -f theses %}

</div>
