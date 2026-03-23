---
layout: page
title: Publications
permalink: /publications/
---

Publications are sourced from [DBLP](https://dblp.org/pid/308/1672.html) (cached locally as of 2026-03-23).

{% assign pubs_by_year = site.data.publications.publications | group_by: "year" | sort: "name" | reverse %}

{% for year_group in pubs_by_year %}
## {{ year_group.name }}

{% for pub in year_group.items %}
{% if pub.doi %}
**[{{ pub.title }}]({{ pub.doi }})**
{% elsif pub.url %}
**[{{ pub.title }}]({{ pub.url }})**
{% else %}
**{{ pub.title }}**
{% endif %}
{{ pub.authors }}
*{{ pub.venue }}*{% if pub.pages %}, pp. {{ pub.pages }}{% endif %}

{% endfor %}
{% endfor %}
