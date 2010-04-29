---
layout: multiple
title: Welcome to CPLUG
---

{% for page in site.posts limit:3 %}
<div class="post">
	{% include post_header.html %}
	{{ page.content }}
</div>
{% endfor %}
