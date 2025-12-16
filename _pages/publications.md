---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
nav_order: 2
toc:
  sidebar: left
---
<hr style="margin-top: 3rem; margin-bottom: 3rem;">
<h2 class="category" id="preprints">Preprints</h2>
<div class="publications">
{% bibliography --query @*[type=preprint] %}
</div>
<hr style="margin-top: 3rem; margin-bottom: 3rem;">
<h2 class="category" id="journal-articles">Journal Articles</h2>
<div class="publications">
{% bibliography --query @*[type=journal] %}
</div>
<hr style="margin-top: 3rem; margin-bottom: 3rem;">
<h2 class="category" id="conference-papers">Conference Papers</h2>
<div class="publications">
{% bibliography --query @*[type=conference] %}
</div>
<hr style="margin-top: 3rem; margin-bottom: 3rem;">
<h2 class="category" id="workshops">Workshops</h2>
<div class="publications">
{% bibliography --query @*[type=workshop] %}
</div>
<hr style="margin-top: 3rem; margin-bottom: 3rem;">
<h2 class="category" id="posters">Posters</h2>
<div class="publications">
{% bibliography --query @*[type=poster] %}
</div>
<hr style="margin-top: 3rem; margin-bottom: 3rem;">
<h2 class="category" id="acknowledgements">Acknowledgements</h2>
<div class="publications">
{% bibliography --query @*[type=acknowledgement] %}
</div>
