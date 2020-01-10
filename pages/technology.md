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
- [__1 Prototyping Toolkits](/1-prototyping-toolkits/)
- [__2 Device Form and Resolution](/2-device-form-and-resolution/)

<ul>
{% for best-practice in site.best-practices | where:'category', 'Technology' %}
<li><span>{{ best-practice.title }}</span></li>
{% endfor %}
</ul>

### Terms and Concepts

weighted word cloud for {{page.title}}

<hr class="panel-line">
<h4>Other Topics</h4>

<a href="/ux/">User Experience</a>
{: .topic .topic-ux}

<a href="/design/">Design</a>
{: .topic .topic-design}

<a href="/society/">Society</a>
{: .topic .topic-society}
