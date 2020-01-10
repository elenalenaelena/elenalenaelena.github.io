---
layout: page
title: Glossary
permalink: /glossary/
---

# <i class="fa fa-book-open"></i> Glossary

Find detailed explanation about vocabulary and concepts of elastic displays.

{% for term in site.terms %} 
    <p>{{ term.title }}</p>  
{% endfor %}

<div class="section-index">
    <hr class="panel-line">
    {% for post in site.docs  %}        
    <div class="entry">
    <h5><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h5>
    <p>{{ post.description }}</p>
    </div>{% endfor %}
</div>
