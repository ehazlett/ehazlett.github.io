---
layout: page
title: welcome
tagline:
---
{% include JB/setup %}

## I am a devops guy living in Indianapolis, Indiana.

## To get in touch, <a href="mailto:ejhazlett@gmail.com">email me</a>.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

