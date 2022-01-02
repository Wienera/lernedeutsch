---
title: Schreiben
layout: default
permalink: /A2/schreiben
---

## A2- Schreiben
<div>
{% for file in site.static_files %}
    {% if file.path contains '_files_a2_schreiben' %}   
        <p> 
            <a href="{{site.url}}{{file.path}}" target="_blank" rel="noopener noreferrer">{{file.name}}</a>
        </p>
    {% endif %}
{% endfor %}
</div>

