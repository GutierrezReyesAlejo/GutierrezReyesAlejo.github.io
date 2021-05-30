---
layout: page
title: alejo blog!
tagline: Mexican Software Developer
---
{% include JB/setup %}

Encuentra el codigo fuente de este blog en mi repositorio de [github](https://github.com/GutierrezReyesAlejo/GutierrezReyesAlejo.github.io/tree/master/_posts/)
## Algunos de mis blogs

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>