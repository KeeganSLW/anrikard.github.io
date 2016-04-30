---
layout: default
description: Categories
---

{% for category in site.categories %}
  <p><a href="{{ site.baseurl }}/categories/{{ category | first }}">{{ category | first }}</a></p>
{% endfor %}
