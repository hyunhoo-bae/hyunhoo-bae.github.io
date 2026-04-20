---
layout: single
title: "Education"
permalink: /education/
author_profile: true
---

# Education

{% assign edu_list = site.education | sort: 'date' | reverse %}

<div class="entries-grid">
  {% for post in edu_list %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
