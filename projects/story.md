---
layout: page
title: "Stories Alone"
permalink: /projects/stories-alone/
---

Stories that stand alone, were performed once or twice, and are not part of a larger project.

## Works
<div class="resp-gallery">
 {% assign work_posts = site.posts | where: "proj_key", "story" %}

    {% for post in work_posts limit:12 %}
    <div class="card"><a href="{{ post.url }}">
        <img src="{{ post.img_path }}" alt="{{ post.img_alt }}" />
              </a>
        <div class="desc"><a href="{{ post.url }}">{{ post.title }}</a></div>
    </div>
  {% endfor %}
</div>