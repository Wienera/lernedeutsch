---
title: Sprechen
layout: default
permalink: /A2/sprechen
---

## A2- Sprechen
<div>
{% for file in site.static_files %}
    {% if file.path contains '_files_a2_sprechen' %}   
        <p> 
            <a href="{{site.url}}{{file.path}}" target="_blank" rel="noopener noreferrer">{{file.name}}</a>
        </p>
    {% endif %}
{% endfor %}
</div>

