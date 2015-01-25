---
layout: page
title: Videos
---

{% for post in site.posts %}
    {% if post.category == "video" %}
<div class="page">
  <h2 class="page-title">{{ post.title }}</h2>
  {{ post.content }}
</div>
    {% endif %}
{% endfor %}
