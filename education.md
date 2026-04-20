---
layout: entries-grid
title: "Education"
permalink: /education/
author_profile: true
entries_layout: grid
---

{% assign education_list = site.education | sort: 'date' | reverse %}
{% for post in education_list %}
  {% include archive-single.html type="grid" %}
{% endfor %}
