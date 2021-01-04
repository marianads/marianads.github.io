---
permalink: /thesis
layout: page
title: My thesis
---


<ul>
  {% for chapter in site.thesis %}
    <li>
      <a href=".{{ thesis.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
