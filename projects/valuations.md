---
layout: page
title: "Self Valuations"
permalink: /projects/valuations/
---

A series of essays-in-progress looking at gender, value, and worth - and selfies.

## Works in this Project
<div class="resp-gallery">
 {% assign work_posts = site.posts | where: "proj_key", "valuations" %}

    {% for post in work_posts limit:12 %}
    <div class="card"><a href="{{ post.url }}">
        <img src="{{ post.img_path }}" alt="{{ post.img_alt }}" />
              </a>
        <div class="desc"><a href="{{ post.url }}">{{ post.title }}</a></div>
    </div>
  {% endfor %}
</div>