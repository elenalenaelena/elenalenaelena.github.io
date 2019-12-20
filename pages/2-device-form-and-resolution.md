---
layout: page
title: "_2 Device Form and Resolution"
permalink: /2-device-form-and-resolution/
---

# _2 Device Form and Resolution

### Challenge
...

### Solutions
...

### Example
...

## Workshop
...

<div class="section-index">
    <hr class="panel-line">
    {% for post in site.docs  %}        
    <div class="entry">
    <h5><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h5>
    <p>{{ post.description }}</p>
    </div>{% endfor %}
</div>