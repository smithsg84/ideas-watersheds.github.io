---
layout: page
title: ParFlow
show_sidebar: false
menubar: softwares
hero_image: /../img/black.jpg
hero_height: is_fullheight
---

# {{ site.data.parflow.software_title }} 
[<i class="fas fa-book"></i>](https://parflow.org/) [<i class="fab fa-github"></i>](https://github.com/parflow/parflow) 

{{ site.data.parflow.description }}
**DOI:**  {{ site.data.parflow.doi }} <br>

## Developers 

{% for developer in site.data.parflow.developers %} {{ developer.first_name }} {{ developer.last_name }} {% if not loop.last %}, {% endif %} {% endfor %}

## Links
**Repository:**  {{ site.data.parflow.repository_link}}  <br>

