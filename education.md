---
layout: entries-grid
title: "Education"
permalink: /education/
author_profile: true
entries_layout: grid
---

{% assign education = site.education | sort: 'date' | reverse %}
{% for post in education %}
  {% include archive-single.html type="grid" %}
{% endfor %}
