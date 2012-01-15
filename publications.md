---
layout: default
title: Publications 
subtitle: List of publications
---

<div id="post">
  <h2>Publications ({{ site.posts | size }} items)</h2>
  <ul class="posts">
    {% for post in site.posts %}

    {% if post.tags == 'publications' %}

      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a> <span>({{ post.abstract }})</span></li>
    
    {% endif  %}

    {% endfor %}
  </ul>
</div>

