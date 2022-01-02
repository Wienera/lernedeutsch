---
title: Lesen
layout: default
permalink: /A2/lesen
---

## A2- Lesen
<div>
{% for file in site.static_files %}
    {% if file.path contains '_files_a2_lesen' %}   
        <p> 
            <a href="{{site.url}}{{file.path}}" target="_blank" rel="noopener noreferrer">{{file.name}}</a>
        </p>
    {% endif %}
{% endfor %}
</div>

