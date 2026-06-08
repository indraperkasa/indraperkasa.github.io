---
title: projects <i class="fa-solid fa-person-hiking"></i>
layout: archive
collection: posts
permalink: /projects/
excerpt: >
  a collection of nothing specific. a bit here and there.<br />
  <small><a>*sometimes personal related. mostly music related.*</a></small>
header:
  overlay_image: /assets/images/banner/lee-wall-banner-flip.jpg
  overlay_filter: 0.16
entries_layout: grid
classes: wide
---

{% assign projects = site.categories.project | concat: site.categories.blog | sort: "date" | reverse %}

<div class="entries-grid">
  {% for post in projects %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>