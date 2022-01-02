---
title: Schreiben
layout: default
permalink: /B1/schreiben
---

## B1- Schreiben
<div>
{% for file in site.static_files %}
    {% if file.path contains '_files_b1_schreiben' %}   
        <p> 
            <a href="{{site.url}}{{file.path}}" target="_blank" rel="noopener noreferrer">{{file.name}}</a>
        </p>
    {% endif %}
{% endfor %}
</div>

