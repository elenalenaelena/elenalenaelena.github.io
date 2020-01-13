---
layout: page
title: Society
permalink: /society/
---

{% include breadcrumb-topic.html %}

<h4 class="strap">Topic</h4>
# Society
{: .topic-society .topic-headline}

The regulatory, ethical and sustainability implications of the development of shape-changing interfaces will impact the long-term adoption of this technology, therefore also its longterm development.

### Best Practices

{% assign best-practices = site.best-practices | where: "category", page.title %}
<ul>
{% for item in best-practices %}
  <li><a href="{{ item.url }}">{{ item.title }}</a></li>
{% endfor %}
</ul>

### Terms and Concepts

terms and concepts tagged with #{{page.title}}

<hr class="panel-line">
<h4>Other Topics</h4>

{% assign groups = site.best-practices | group_by: "category" %}

{% for group in groups | where: group.name, !page.title %}
<a href="/{{ group.name | downcase | strip | replace:'user experience', 'ux' }}/">{{ group.name | replace:'UX', 'User Experience'}}</a>
{: .topic .topic-{{ group.name | downcase | strip | replace:'user experience', 'ux'}}}

{%endfor%}
