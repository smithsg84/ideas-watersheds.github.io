---
layout: page
title: ParFlow
show_sidebar: false
menubar: softwares
hero_image: /../img/black.jpg
hero_height: is_fullheight
---

<h1>{{ site.data.parflow.software_title }} [<i class="fas fa-book"></i>](https://parflow.org/) [<i class="fab fa-github"></i>](https://github.com/parflow/parflow) </h1>

{{ site.data.parflow.description }}

<h2> Developers </h2>

{% for developer in site.data.parflow.developers %}
<p>{{ developer.first_name }} {{ developer.last_name }},
{% endfor %}
  
Repository:  {{ site.data.parflow.repository_link}}  
DOI:  {{ site.data.parflow.doi }}
