---
layout: page
title: Best Practices
permalink: /best-practices/
---

# Best Practices

Best Practices cover current challenges in 4 major topics of elastic displays research. Read about a specific challenge and why it is important, what options you have to face it and discover examples of existing solutions. Additional workshop instructions help you to quickly apply your aquired knowledge in practice.

<div class="section-index">
    <hr class="panel-line">
    {% for post in site.docs  %}        
    <div class="entry">
    <h5><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h5>
    <p>{{ post.description }}</p>
    </div>{% endfor %}
</div>
