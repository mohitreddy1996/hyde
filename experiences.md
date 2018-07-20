---
layout: page
title: Experiences
---

<div class="posts">
  {% assign sorted-experiences = site.experiences | sort: 'date' | reverse %}
  {% for project in sorted-experiences %}
  <div class="post">
    <h2 class="post-title">
      <a href="{{ project.url }}">
        {{ project.title }}
      </a>
    </h2>

    <span class="post-date">{{ project.date | date_to_string }}</span>

    <img src="{{ project.image_src }}">

    {{ project.short_desc }}

    <br>
    <br>Know more about my experience <a href="{{ project.url }}">Here!</a>
  </div>
  {% endfor %}

</div>
