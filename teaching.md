---
layout: page
title: Teaching 
permalink: /teaching/
---

{% for item in site.data.teaching %} 
#### {{ item.ay }} 
  {% for c in item.courses %} 
  * {{ c.title }}, *{{ c.course }}* ({{ c.role }}) 
  {% endfor %} 
{% endfor %} 

