---
title: B1- Grammatik
type: page
permalink: /B1/grammatik
---

## B1- Grammatik
<div>
{% for file in site.static_files %}
    {% if file.path contains '_files_b1_grammatik' %}   
        <p> 
            <a href="{{site.url}}{{file.path}}">{{file.name}}</a>
        </p>
    {% endif %}
{% endfor %}
</div>