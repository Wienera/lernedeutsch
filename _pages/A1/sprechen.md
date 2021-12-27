---
title: A1- Sprechen
type: page
permalink: /A1/sprechen
---

## A1- Sprechen
<div>
{% for file in site.static_files %}
    {% if file.path contains '_files_a1_sprechen' %}   
        <p> 
            <a href="{{site.url}}{{file.path}}">{{file.name}}</a>
        </p>
    {% endif %}
{% endfor %}
</div>

