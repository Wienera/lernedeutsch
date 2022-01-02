---
title: Grammatik
layout: default
permalink: /B1/grammatik
---

## B1- Grammatik
<div>
{% for file in site.static_files %}
    {% if file.path contains '_files_b1_grammatik' %}   
        <p> 
            <a href="{{site.url}}{{file.path}}" target="_blank" rel="noopener noreferrer">{{file.name}}</a>
        </p>
    {% endif %}
{% endfor %}
</div>