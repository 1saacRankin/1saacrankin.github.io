---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
nav_order: 2
---

## Journal Articles

<div class="publications">
{% bibliography --query @*[type=journal] %}
</div>

## Conference Papers

<div class="publications">
{% bibliography --query @*[type=conference] %}
</div>

## Workshops

<div class="publications">
{% bibliography --query @*[type=workshop] %}
</div>

## Posters

<div class="publications">
{% bibliography --query @*[type=poster] %}
</div>

## Preprints

<div class="publications">
{% bibliography --query @*[type=preprint] %}
</div>
