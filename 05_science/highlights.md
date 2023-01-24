---
layout: page
title: Highlights
permalink: /science/highlights/
---

<ul>
  {% for item in site.highlights %}
    <li>
      <a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a>
    </li>
  {% endfor %}
</ul>