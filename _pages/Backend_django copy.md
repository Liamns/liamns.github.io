---
layout: archive
permalink: project/
title: "Project"

author_profile: true
sidebar:
  nav: "docs"
---

{% assign posts = site.categories.project%}
{% for post in posts %}
{% include archive-single.html type=entries_layout %}
{% endfor %}
