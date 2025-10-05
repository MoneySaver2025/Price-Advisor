layout: page
title: Buying Guides
permalink: /guides/
---

Our latest guides:

{% assign sorted = site.guides | sort: 'title' %}
{% for g in sorted %}
- [{{ g.title }}]({{ g.url }}) — {{ g.excerpt | strip_html | truncate: 120 }}
{% endfor %}
