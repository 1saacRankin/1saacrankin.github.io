---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
nav_order: 2
---

<h2 class="category">Journal Articles</h2>

<div class="publications">
{% bibliography --query @*[type=journal] --order descending %}
</div>

<div style="margin-top: 3rem;"></div>

<h2 class="category">Conference Papers</h2>

<div class="publications">
{% bibliography --query @*[type=conference] --order descending %}
</div>

<div style="margin-top: 3rem;"></div>

<h2 class="category">Workshops</h2>

<div class="publications">
{% bibliography --query @*[type=workshop] --order descending %}
</div>

<div style="margin-top: 3rem;"></div>

<h2 class="category">Posters</h2>

<div class="publications">
{% bibliography --query @*[type=poster] --order descending %}
</div>

<div style="margin-top: 3rem;"></div>

<h2 class="category">Preprints</h2>

<div class="publications">
{% bibliography --query @*[type=preprint] --order descending %}
</div>
