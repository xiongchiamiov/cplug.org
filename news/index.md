---
layout: multiple
title: News
---
{% assign root = '/cplug.org' %}

{% for page in site.posts %}
<div style="margin-bottom: .5em;">
	<div class="date">
		{{ page.date | date: "%Y-%m-%d" }}
	</div>
	<a href="{{ root }}{{ page.url }}">{{ page.title }}</a>
</div>
{% endfor %}
