---
layout: default
title: Projects
output: true
---

<div class="posts">
  {% for project in site.projects %}
    <h2 class="post-title">
      <a href="{{ project.url }}">
        {{ project.title }}
      </a>
    </h2>


  {% endfor %}
</div>
