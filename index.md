---
layout: default
title: Smoothcomp Analysis
permalink: /
---

# Smoothcomp Analysis

Welcome to the project.

## Analyses

{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}