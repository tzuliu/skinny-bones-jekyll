---
layout: home
permalink: /
title: "Welcome"
image:
  feature: Chicago2.jpg
---

I am a PhD Candidate in Environmental Science and Policy at the University of California, Davis. My research interests include 
**Political Economy**, **Party Politics**, **Wester European Politics**, **Causal Inference**, **Scaling**, **Duration Model**, **Machine Learning**, **Network Analysis**, **Bayesian Statistics**, and **Time-Series Analysis**.
<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
