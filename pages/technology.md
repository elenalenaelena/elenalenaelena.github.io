---
layout: page
title: Technology
permalink: /technology/
---

{% include breadcrumb-topic.html %}

<h4 class="strap">Topic</h4>
# Technology
{: .topic-technology .topic-headline}

Introduction on technical challenges of elastic displays in multiple areas. Technical best practices cover prototyping toolkits, miniaturisation of devices, I/O modalities and non-functional requirements.

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

<a href="/ux/">User Experience</a>
{: .topic .topic-ux}

<a href="/design/">Design</a>
{: .topic .topic-design}

<a href="/society/">Society</a>
{: .topic .topic-society}
