---
layout: page
title: Technology
permalink: /technology/
---

### Topic
# Technology

Best Practices on technical challenges of elastic displays cover prototyping toolkits, miniaturisation of devices etc. ...

<div class="section-index">
    <hr class="panel-line">
    {% for post in site.docs  %}        
    <div class="entry">
    <h5><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h5>
    <p>{{ post.description }}</p>
    </div>{% endfor %}
</div>
