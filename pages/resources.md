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

