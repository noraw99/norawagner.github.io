---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

## Research Interests

Add your research interests here. For example:
- Clustering algorithms
- Computational complexity
- Machine learning

## Current Projects

Describe your current research projects in detail.

### Project 1: [Project Name]
Brief description of your research project, methodology, and findings.

### Project 2: [Project Name]
Brief description of another research project.

## Publications

You can also find my articles on [Google Scholar](link-to-your-profile).

{% include base_path %}
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
