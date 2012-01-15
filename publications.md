---
layout: default
title: Publications 
subtitle: List of publications
---

<div id="post">
  <h2>Publications</h2>
  <ul class="posts">
    {% for post in site.posts %}

    {% if post.tags == 'publication' %}

      <li><span>{{ post.date | date_to_string }}</span> &raquo; <span>{{ post.title }}</span> <a href="{{ post.url }}">{{ post.abstract }}</a> </li>
    
    {% endif  %}

    {% endfor %}
  </ul>
</div>

