---
layout: archive
permalink: django/
title: "Django"

author_profile: true
sidebar:
  nav: "docs"
---

{% assign posts = site.categories.django %}
{% for post in posts %}
{% include archive-single.html type=entries_layout %}
{% endfor %}
