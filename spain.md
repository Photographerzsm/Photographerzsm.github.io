---
layout: page
title: Photoes in Barcelona, Spain
slug: spain
---

<div class="posts">

{% for post in site.categories.spain %}
 {% if post.url %}
  <div class="post">
       <span class="post-date">{{ post.date | date_to_string }}</span>
       {{ post.excerpt }}
  </div>
 {% endif %}
{% endfor %}
</div>


