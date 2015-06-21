---
layout: page
title: Jonathan Freites | blogging my life
tagline: No hay lugar para el "UNDO"
---
{% include JB/setup %}
    
## Ultimos posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

