---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
nav_order: 2
---


<hr style="margin-top: 3rem; margin-bottom: 3rem;">

<h2 class="category">Preprints</h2>

<div class="publications">
{% bibliography --query @*[type=preprint] %}
</div>

<hr style="margin-top: 3rem; margin-bottom: 3rem;">

<h2 class="category">Journal Articles</h2>

<div class="publications">
{% bibliography --query @*[type=journal] %}
</div>

<hr style="margin-top: 3rem; margin-bottom: 3rem;">

<h2 class="category">Conference Papers</h2>

<div class="publications">
{% bibliography --query @*[type=conference] %}
</div>

<hr style="margin-top: 3rem; margin-bottom: 3rem;">

<h2 class="category">Workshops</h2>

<div class="publications">
{% bibliography --query @*[type=workshop] %}
</div>

<hr style="margin-top: 3rem; margin-bottom: 3rem;">

<h2 class="category">Posters</h2>

<div class="publications">
{% bibliography --query @*[type=poster] %}
</div>
