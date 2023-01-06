---
layout: single
title: Posts
permalink: /posts/
---

Here is a list of my posts.
{% for tag in site.tags %}
  {% if tag[0] == "general" %}
   <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
       <small>{{ post.date | date_to_long_string: "ordinal", "US" }}{{ post.excerpt }}</small>
             
    {% endfor %}
  <u1>
  {% endif %}
{% endfor %}