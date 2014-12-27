---
layout: page
title: Photoes in France
slug: france
---

<div class="posts">

{% for post in site.categories.france %}
 {% if post.url %}
  <div class="post">
       <span class="post-date">{{ post.date | date_to_string }}</span>
       {{ post.excerpt }}
  </div>
 {% endif %}
{% endfor %}
</div>


