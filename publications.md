---
layout: default
title: Publications 
subtitle: List of publications
---

<div id="post">
  <h2>Publications</h2>
  <ul class="posts">
    {% for post in site.posts %}

    {% if post.genre == 'publication' %}
      <li><span>{{ post.year }}</span> &raquo; <span>{{ post.title }}</span><br /> {{ post.abstract }} <a href="{{ post.url }}">more...</a> <a href="{{ post.linktodoc }}">[doc]</a></li>


    {% endif  %}

    {% endfor %}
  </ul>
</div>

