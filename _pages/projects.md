---
layout: collection
title: "Projects"
permalink: /projects/
collection: projects
entries_layout: grid
classes: wide
filter:
  show: true
  # label: "Project Type"
---

## Research Projects

{% assign research_projects = site.projects | where: "category", "research" %}
{% for project in research_projects %}
  {% include archive-single.html %}
{% endfor %}

## Course Projects

{% assign course_projects = site.projects | where: "category", "course" %}
{% for project in course_projects %}
  {% include archive-single.html %}
{% endfor %}