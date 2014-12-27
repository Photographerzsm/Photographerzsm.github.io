---
layout: page
title: Photoes in Hong Kong
slug: hongkong
---

<div class="posts">

{% for post in site.categories.hongkong %}
 {% if post.url %}
  <div class="post">
       <span class="post-date">{{ post.date | date_to_string }}</span>
       {{ post.excerpt }}
  </div>
 {% endif %}
{% endfor %}
</div>


