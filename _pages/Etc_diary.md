---
layout: archive
permalink: diary/
title: "Diary"

author_profile: true
sidebar:
  nav: "docs"
---

{% assign posts = site.categories.diary%}
{% for post in posts %}
{% include archive-single.html type=entries_layout %}
{% endfor %}
