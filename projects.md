---
layout: default
title: Projects
subtitle: List of projects 
---

<div id="post">
  <h2>Projects</h2>
  <ul class="posts">
    {% for post in site.posts %}

    {% if post.genre == 'project' %}
      <li><span>{{ post.year }}</span> &raquo; <span>{{ post.title }}</span><br /> {{ post.summary}} <a href="{{ post.url }}">more...</a> <a href="{{ post.linktosite}}">[project page]</a></li>


    {% endif  %}

    {% endfor %}
  </ul>
</div>

