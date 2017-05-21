---
layout: home
permalink: /
title: "Welcome to Tzu-Ping's Website"
image:
  feature: Chicago2.jpg
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
