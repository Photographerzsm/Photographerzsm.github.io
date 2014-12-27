---
layout: page
title: Photoes in India
slug: india
---

<div class="posts">

{% for post in site.categories.india %}
 {% if post.url %}
  <div class="post">
       <span class="post-date">{{ post.date | date_to_string }}</span>
       {{ post.excerpt }}
  </div>
 {% endif %}
{% endfor %}
</div>


