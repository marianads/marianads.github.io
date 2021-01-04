---
permalink: /thesis
layout: page
title: My thesis
---

Comprehension of shear-induced areareduction of soft elastic contacts

<ul>
  {% for chapter in site.thesis %}
    <li>
      <a href=".{{ thesis.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
