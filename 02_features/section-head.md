---
layout: page
title: Features
permalink: /features/
---


The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog. The quick brown fox jumps over the lazy dog.

{% assign features = site.data.nav-config.toc | where: "title", "Features" %}

<ul>
  {% for entry in features[0].subfolderitems %}
    <li>
      <a href="{{ site.baseurl }}{{ entry.url }}">{{ entry.page }}</a>
    </li>
  {% endfor %}
</ul>
