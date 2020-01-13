---
layout: page
title: User Experience
permalink: /ux/
---

{% include breadcrumb-topic.html %}

<h4 class="strap">Topic</h4>
# User Experience
{: .topic-ux .topic-headline}

This section describes research challenges concerning users’ understanding of, interaction with, and behaviour around shape-changing interfaces. Addressing these challenges will produce empirical and theoretical insight about behaviour.

### Best Practices

{% assign best-practices = site.best-practices | where: "category",  page.title %}
<ul>
{% for item in best-practices %}
  <li><a href="{{ item.url }}">{{ item.title }}</a></li>
{% endfor %}
</ul>

### Terms and Concepts

weighted word cloud for {{page.title}}

<hr class="panel-line">
<h4>Other Topics</h4>

<a href="/technology/">Technology</a>
{: .topic .topic-technology}

<a href="/design/">Design</a>
{: .topic .topic-design}

<a href="/society/">Society</a>
{: .topic .topic-society}
