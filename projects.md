---
layout: page
title: Work
description: Projects
---

<div class="grid-container">

{% for project in site.projects %}


<div>          <a href="{{ project.url | prepend: site.baseurl | prepend: site.url }}">
          <span>
              <h2>{{ project.title }}</h2>
              <br/>
              <p>{{ project.description }}</p>
          </span>
          </a>
  </div>


  {% endfor %}

</div>
