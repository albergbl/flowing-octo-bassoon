---
layout: page
title: "Work"
permalink: /the-work/
---

<div class="resp-gallery">
 {% assign work_posts = site.posts | where: "kind", "work" %}

    {% for post in work_posts %}
    <div class="card"><a href="{{ post.url }}">
        <img src="{{ post.img_path }}" alt="{{ post.img_alt }}" />
              </a>
        <div class="desc"><a href="{{ post.url }}">{{ post.title }}</a></div>
    </div>
  {% endfor %}
</div> 