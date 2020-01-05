---
layout: page
title: Best Practices
permalink: /best-practices/
---

# Best Practices

Best Practices cover current challenges of elastic displays research in the 4 major topics <a href="{{site.baseurl }}/technology">technology</a>, UX, design and society. Read about a specific challenge and why it is important, what options you have to face it and discover examples of existing solutions. Additional workshop instructions help you to quickly apply your aquired knowledge in practice.

<div class="section-index">
    <hr class="panel-line">
    {% for post in site.docs  %}        
    <div class="entry">
    <h5><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h5>
    <p>{{ post.description }}</p>
    </div>{% endfor %}
</div>
