---
layout: default 
title: Interactive maps and plots of CAPRI results
subtitle: Visualisations and online publishing of CAPRI results 
---

<div id="post">
  <h2>Visualisations of CAPRI model results</h2>
  <ul class="posts">
    {% for post in site.posts %}

    {% if post.genre == 'capridemo' %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <span>{{ post.title }}</span><br /> {{ post.subtitle}} <a href="{{ post.url }}">more...</a> </li>


    {% endif  %}

    {% endfor %}
  </ul>
</div>

