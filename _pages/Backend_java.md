---
layout: archive
permalink: java/
title: "Java"

author_profile: true
sidebar:
  nav: "docs"
---

{% assign posts = site.categories.java%}
{% for post in posts %}
{% include archive-single.html type=entries_layout %}
{% endfor %}
