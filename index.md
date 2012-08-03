---
layout: default
Title: Deutsche Bundesgesetze- und verordnungen
slug: index

---

<ul>
{% for p in site.pages|sort:"slug" %}
	{% if p.jurabk %}
	<li><a href=".{{ p.url|replace:"index.html","" }}">{{ p.jurabk }}: {{ p.Title }}</a></li>
	{% endif %}
{% endfor %}
</ul>

