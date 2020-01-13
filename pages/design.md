---
layout: page
title: Design
permalink: /design/
---

{% include breadcrumb-topic.html %}

<h4 class="strap">Topic</h4>
# Design
{: .topic-design .topic-headline}

This section describes the design research challenges. The biggest differences to the traditional field of design is the responsiveness of shape-changing interfaces, the design and form of the artefacts, and their dynamic qualities. Shapechanging interfaces are unique in the integration of movement and transformation through actuation based on direct user input. Three key design challenges are identified: designing for temporality, integrating the artefact and interaction, and developing applications and content.

### Best Practices

{% assign best-practices = site.best-practices | where: "category", page.title %}
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

<a href="/ux/">User Experience</a>
{: .topic .topic-ux}

<a href="/society/">Society</a>
{: .topic .topic-society}
