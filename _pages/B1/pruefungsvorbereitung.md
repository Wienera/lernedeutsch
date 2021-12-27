---
title: B1- Prüfungsvorbereitung
type: page
permalink: /B1/pruefungsvorbereitung
---

## B1- Prüfungsvorbereitung
<div>
{% for file in site.static_files %}
    {% if file.path contains '_files_b1_pruefung' %}   
        <p> 
            <a href="{{site.url}}{{file.path}}">{{file.name}}</a>
        </p>
    {% endif %}
{% endfor %}
</div>