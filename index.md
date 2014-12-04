---
layout: home
permalink: /
image:
  feature: /wood-texture-1600x800.jpg
---
<div class="tiles">



</div><!-- /.tiles -->
<h2>Latest projects:</h2>
<div class="tiles">

{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->