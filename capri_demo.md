---
layout: onecolumn 
title: CAPRI goodies
subtitle: Demonstration projects around the CAPRI model 
---

<div id="post">

  
  <ul class="posts">
    {% for post in site.posts %}

    {% if post.genre == 'capridemo' %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <span>{{ post.title }}</span><br /> {{ post.subtitle}} <a href="{{ post.url }}">more...</a> </li>


    {% endif  %}

    {% endfor %}
  </ul>
</div>

