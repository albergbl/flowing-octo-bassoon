---
layout: page
title: "Open Letters to the Men of Craigslist"
permalink: /projects/open-letters/
---

A project exploring ways to speak of and describe the manic side of bipolar disorder from an #ownvoices perspective

## Works in this Project
<div class="resp-gallery">
 {% assign work_posts = site.posts | where: "proj_key", "letters" %}

    {% for post in work_posts limit:12 %}
    <div class="card"><a href="{{ post.url }}">
        <img src="{{ post.img_path }}" alt="{{ post.img_alt }}" />
              </a>
        <div class="desc"><a href="{{ post.url }}">{{ post.title }}</a></div>
    </div>
  {% endfor %}
</div>