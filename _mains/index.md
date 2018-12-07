---
title: Mains
layout: category_index
---

{% for x in site.mains %}
  <h2>
    <a href="{{ x.url }}">
      {{ x.title }} - {{ x.url }}
    </a>
  </h2>
{% endfor %}