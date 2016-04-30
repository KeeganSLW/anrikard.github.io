---
layout: default
description: categories
---
<h1>Projects</h1>

{% for post in site.categories.projects %}
  <p>
      <p><span>{{ post.date | date: "%b %d, %Y" }}</span> // <a href="{{ post.url }}">{{ post.title }}</a> // <span id="word_count">{{ post.content | number_of_words }} wds</span></p>
  </p>
{% endfor %}
