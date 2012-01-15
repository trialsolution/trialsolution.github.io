---
layout: default
title: News 
subtitle: News items
---

<div id="post">
  <h2>News</h2>
  <ul class="posts">
    {% for post in site.posts %}

   
    {% if post.genre == 'news' %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <span>{{ post.title }}</span><br /> {{ post.subtitle}} <a href="{{ post.url }}">more...</a> </li>


    {% endif  %}

    {% endfor %}
  </ul>
</div>

