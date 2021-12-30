---
title: B1- Sprechen
layout: default
permalink: /B1/sprechen
---

## B1- Sprechen
<div>
{% for file in site.static_files %}
    {% if file.path contains '_files_b1_sprechen' %}   
        <p> 
            <a href="{{site.url}}{{file.path}}">{{file.name}}</a>
        </p>
    {% endif %}
{% endfor %}
</div>

