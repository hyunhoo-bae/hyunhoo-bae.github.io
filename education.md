---
layout: entries-grid
title: "Education"
permalink: /education/
author_profile: true
entries_layout: grid
---

{% assign edu_items = site.education | sort: 'date' | reverse %}
{% for item in edu_items %}
  {% include archive-single.html type="grid" %}
{% endfor %}
