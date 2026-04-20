---
layout: entries-grid
title: "Education"
permalink: /education/
author_profile: true
entries_layout: grid
---

{% assign edu = site.education | sort: 'date' | reverse %}
{% for post in edu %}
  {% include archive-single.html type="grid" %}
{% endfor %}
