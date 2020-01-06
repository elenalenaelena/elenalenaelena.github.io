---
layout: best-practice
title: "_1 Prototyping Toolkits"
permalink: /1-prototyping-toolkits/
---

# _1 Prototyping Toolkits

Prototyping elastic displays is challenging because it involves complex electronics as well as mechanical engineering and specific use contexts may require different actuation approaches. What are suitable tools to test complex elastic display applications in an early development state?

## Solutions
We describe prototyping toolkits on three technological layers that can lower the barrier to implementation of classic interfaces: 
1. a standard platform for hardware prototyping, dealing with some aspects of actuation
2. a cross-platform software layer for applications and
3. tools for end-user programming

- followed up by linked explanations on different possibilities to overcome the challenge, for example Physical Programming, 4D Printing, Rapid Prototyping, electromechanical/pneumatic/hydraulic actuation, smart materials
- (optional) decision helper

## Showcase
Showcase of either existing own projects or research results, e.g. 3D Printing for the Rapid Prototyping of Structural Electronics <a href="https://ieeexplore.ieee.org/document/6766751" target="_blank">[DOI 10.1109/ACCESS.2014.2311810]</a>

## Workshop
step-by-step workshop on one of the solutions above, e.g. Try Rapid Prototyping with 3D printing technologies

<div class="section-index">
    <hr class="panel-line">
    {% for post in site.docs  %}        
    <div class="entry">
    <h5><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h5>
    <p>{{ post.description }}</p>
    </div>{% endfor %}
</div>