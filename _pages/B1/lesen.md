---
title: B1- Lesen
type: page
permalink: /B1/lesen
---

## B1- Lesen
<div>
{% for file in site.static_files %}
    {% if file.path contains '_files_b1_lesen' %}   
        <p> 
            <a href="{{site.url}}{{file.path}}">{{file.name}}</a>
        </p>
    {% endif %}
{% endfor %}
</div>

