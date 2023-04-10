---
layout: page

title: Highlights

theme: white
permalink: /science/highlights/
---

<!-- <ul>
  {% for item in site.highlights %}
    <li>
      <a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a>
    </li>
  {% endfor %}
</ul>
 -->
 
<br>

<div class="teasers">

{% for item in site.highlights %}

<div class="teaser">
  <a href="{{ site.baseurl }}{{ item.url }}">
  	<div class="image-wrapper">
  		<div><img src="{{ site.baseurl }}/assets/images/{{ item.image }}"></div>
  		<div class="hover-scrim"></div>
  	</div>
  	<div class="content-wrapper">
  		<h3>{{ item.title }}</h3>
  	</div>
  </a>
</div>

{% endfor %}

</div>