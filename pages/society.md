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

<a href="/technology/">Technology</a>
{: .topic .topic-technology}

<a href="/ux/">User Experience</a>
{: .topic .topic-ux}

<a href="/design/">Design</a>
{: .topic .topic-design}
