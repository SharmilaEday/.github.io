---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
entries_layout: grid
---

{% include feature_row id="featured" type="left" %}

{% for project in site.projects %}
  {% include archive-single.html type="grid" %}
{% endfor %}
