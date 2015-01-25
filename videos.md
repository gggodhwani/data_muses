---
layout: page
title: Videos
---

{% for post in site.posts %}
    {% if post.category == "video" %}
<div class="post">
  <h2 class="post-title">{{ post.title }}</h2>

    <span class="post-date">{{ post.date | date_to_string }}</span>

    {{ post.content }}
</div>
    {% endif %}
{% endfor %}
