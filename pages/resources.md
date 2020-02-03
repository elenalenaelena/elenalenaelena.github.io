---
layout: page
title: Resources
permalink: /resources/
---

# Resources
additional resources related to the research on Elastic Displays

### Media Files

### References

{% assign references = site.data.references | sort: "author" %}
<ul>
{% for reference in references %}
{% assign index = forloop.index %}
<li>
    [{{ index }}] {{ reference.author }}{% if reference.date %} ({{ reference.date}}) }{% elsif reference.year %} ({{ reference.year}}){% endif %}. <a href="{{ reference.url }}">{{ reference.title }}</a>.{% if reference.in %} In: {{ reference.in}}. {% endif %} {{ reference.url }}
</li>
{% endfor %}
</ul>

### Links

{% assign links = site.data.links | sort: "title" %}
<ul>
{% for link in links %}
{% assign index = forloop.index %}
<li>
    <a href="{{ reference.title }}">{{ reference.title }}</a>{% if reference.src %}, {{ reference.src}} {% endif %}. {{ reference.url }}
</li>
{% endfor %}
</ul>

