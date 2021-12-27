---
title: A1- Prüfungsvorbereitung
type: page
permalink: /A1/pruefungsvorbereitung
---

## A1- Prüfungsvorbereitung
<div>
{% for file in site.static_files %}
    {% if file.path contains '_files_a1_pruefung' %}   
        <p> 
            <a href="{{site.url}}{{file.path}}">{{file.name}}</a>
        </p>
    {% endif %}
{% endfor %}
</div>