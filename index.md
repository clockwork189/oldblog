---
layout: page
title: My Rants on Life
tagline: Supporting tagline
---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
    <h3><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h3>
    <div>
      {{ post.content }}
    </div>
  {% endfor %}
</ul>