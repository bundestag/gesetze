---
layout: default
Title: Deutsche Bundesgesetze- und verordnungen
slug: index

---

<ul class="laws">
{% for p in site.pages %}
	{% if p.jurabk %}
	<li id="{{ p.slug }}">
		<a href=".{{ p.url|replace:"index.html","" }}">{{ p.jurabk }}</a>
		- {{ p.Title }}</a>
	</li>
	{% endif %}
{% endfor %}
</ul>

