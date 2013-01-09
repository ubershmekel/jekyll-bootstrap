---
layout: page
title: yuvalg/blog
tagline: Arts and bits
---
    
{% include JB/setup %}

The blog previously known as "uberpython python blog"

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


