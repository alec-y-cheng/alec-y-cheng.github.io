---
title: Design Portfolio
layout: single
permalink: /portfolio/
classes: wide
---

<h2>Portfolio</h2>
<div class="entries-grid">
  {% for item in site.portfolio %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>

<h2>Projects</h2>
<div class="entries-grid">
  {% for item in site.projects %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
