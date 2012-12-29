---
layout: page
title: yuvalg/blog
tagline: Arts and bits
---
    
{% include JB/setup %}

This blog contains the old posts from uberpython 
and more in the future.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


