---
layout: page
title: Publications
permalink: /publications/
---

## Journal and Conference Papers 
{% bibliography -q @article || @inproceedings[dest!=ws]" %} 
## Workshop Papers 
{% bibliography -q @inproceedings[dest=ws] %} 

