---
layout: single
title: Projects
permalink: /projects/
---

Here is a list the projects I have worked on, some were for school and some were personal projects. 

{% for tag in site.tags %}
  {% if tag[0] == "projects" %}
   <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
       <small>{{ post.date | date_to_long_string: "ordinal", "US" }}{{ post.excerpt }}</small>
             
    {% endfor %}
  <u1>
  {% endif %}
{% endfor %}