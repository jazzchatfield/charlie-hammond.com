---
layout: default
title: News
---

<ul class="news">
  {% for post in site.posts %}
    <li>
      <!-- <a href="{{ post.url }}">{{ post.title }}</a> -->
      <h3>{{post.title}}</h3>
      {{post.content}}
    </li>
    <hr/>
  {% endfor %}
</ul>
