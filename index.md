---
layout: default
Title: Deutsche Bundesgesetze- und verordnungen
---

<ul>
{% for p in site.pages|sort:"slug" %}
	<li><a href=".{{ p.url|replace:"index.html","" }}">{{ p.jurabk }}: {{ p.Title }}</a></li>
{% endfor %}
</ul>

