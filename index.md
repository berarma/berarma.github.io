---
layout: default
title: Home
---

I'm a Computer Engineer and Web Developer living in Valencia (Spain). This is
my personal site to share my professional interest in Software and Computers.
It may have something useful for you, or at the very least you will know
something more about me and my work.

## Latest posts:

<dl class="posts">
  {% for post in site.posts %}
    <dt><span>{{ post.date | date_to_string }}</span></dt>
    <dd><a href="{{ post.url }}">{{ post.title }}</a></dd>
  {% endfor %}
</dl>
