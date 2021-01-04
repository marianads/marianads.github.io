---
permalink: /thesis
layout: page
title: My thesis
---


<ul>
  {% for chapter in site.thesis %}
    <li>
      <a href=".{{ thesis.url }}">{{ thesis.chapter }}</a>
    </li>
  {% endfor %}
</ul>
