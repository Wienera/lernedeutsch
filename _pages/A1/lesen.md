---
title: A1- Lesen
layout: default
permalink: /A1/lesen
---

## A1- Lesen
<div>
{% for file in site.static_files %}
    {% if file.path contains '_files_a1_lesen' %}   
        <p> 
            <a href="{{site.url}}{{file.path}}">{{file.name}}</a>
        </p>
    {% endif %}
{% endfor %}
</div>

