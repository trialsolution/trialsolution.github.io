---
layout: default
title: Publications 
subtitle: List of publications
---

<div id="post">
  <h2>Publications ({{ site.posts | size }} items)</h2>
  <ul>
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="/trialsolution.github.com{{ post.url }}">{{ post.title }}</a> <span>({{ post.abstract }})</span></li>
    {% endfor %}
  </ul>
</div>

