---
layout: page
title: "_1 Prototyping Toolkits"
permalink: /1-prototyping-toolkits/
---

# _1 Prototyping Toolkits

### Challenge
How can complex electronic be tested in an early development state?

### Solutions
Explanations on different possibilities to overcome the challenge, for example Physical Programming, 4D Printing, Rapid Prototyping

Additional decision helper (optional)

### Showcase
Showcase of either existing own projects or research results, e.g. 3D Printing for the Rapid Prototyping of Structural Electronics <a href="https://ieeexplore.ieee.org/document/6766751" target="_blank">[DOI 10.1109/ACCESS.2014.2311810]</a>

## Workshop
step-by-step workshop on one of the solutions above, e.g. Try Rapid Prototyping with 3D printing technologies

### More Best Practices 
Link next or similar Best Practices here

<div class="section-index">
    <hr class="panel-line">
    {% for post in site.docs  %}        
    <div class="entry">
    <h5><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h5>
    <p>{{ post.description }}</p>
    </div>{% endfor %}
</div>