---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---


## Publications

{% include base_path %}
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
