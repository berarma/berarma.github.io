---
layout: default
title: News
---
<dl class="posts">
  {% for post in site.posts %}
    <dt><span>{{ post.date | date_to_string }}</dt><dd><a href="{{ post.url }}">{{ post.title }}</a></dd>
  {% endfor %}
</dl>
