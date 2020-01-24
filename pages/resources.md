---
layout: page
title: Resources
permalink: /resources/
---

# Resources
additional resources related to the research on Elastic Displays

### Media Files

### Quizzes

<ul>
{% for reference in site.data.references %}
<li>
    {{ reference.author }}{% if reference.date %} ({{ reference.date}}){% endif %}. {% if reference.in %}In: {{ reference.in}}. {% endif %}. <a href="{{ reference.url }}">{{ reference.title }} </a>. {{ reference.url }}
</li>
{% endfor %}
</ul>

### Links

