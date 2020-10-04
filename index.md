---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
     
<div class="beauty-wrap">
<div class="horiz-beauty"><a href="/the-work/"><img src="assets/img/calf.jpg" /></a></div>
    <div class="beauty-container">
<div class="resp-beauty-gallery">
 {% assign beauty_posts = site.posts | where: "feature", "beauty" %}

    {% for post in beauty_posts limit:4 %}
    <div class="beauty-card"><a href="{{ post.url }}">
        <img src="{{ post.img_path }}" alt="{{ post.img_alt }}" />
              </a>
    </div>
  {% endfor %}
</div>
</div>
</div>