---
layout: page
title: Teaching 
permalink: /teaching/
---

{% for item in site.data.teaching %} 
#### {{ item.ay }}
{% if item.courses %}
##### Courses 
{% endif %}
{% for c in item.courses %} 
* {{ c.title }}, *{{ c.course }}* ({{ c.role }}) 
{% endfor %} 
{% if item.theses %}
##### Theses 
{% endif %}
{% for t in item.theses %} 
* "{{ t.title }}" by {{ t.student }}, *{{ t.course }}* ({{ t.month }} {{ item.ay }}), supervised with {{ t.supervisors }}
{% endfor %}
{% endfor %} 

