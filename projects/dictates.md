---
layout: page
title: "Gender and its Dictates"
permalink: /projects/dictates/
---

## Project History

Gender and its Dictates is cut paper collage focused on bodies and gender. It is art that is focused on describing the world as it is and points towards the rigidity of current gender roles and norms.

## Works in this Project
<div class="resp-gallery">
 {% assign work_posts = site.posts | where: "proj_key", "gend" %}

    {% for post in work_posts limit:12 %}
    <div class="card"><a href="{{ post.url }}">
        <img src="{{ post.img_path }}" alt="{{ post.img_alt }}" />
              </a>
        <div class="desc"><a href="{{ post.url }}">{{ post.title }}</a></div>
    </div>
  {% endfor %}
</div>