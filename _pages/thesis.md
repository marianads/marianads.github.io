---
permalink: /thesis
layout: page
title: My thesis
---

Comprehension of shear-induced areareduction of soft elastic contacts

<ul>
  {% for post in site.thesis %}
    <li>
      <a href=".{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

