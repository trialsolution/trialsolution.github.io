---
layout: default
title: Publications 
subtitle: List of publications
---

<div id="post">
  <h2>Archive ({{ site.publications | size }} items)</h2>
  <ul>
    {% for post in site.publications %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="/trialsolution{{ post.url }}">{{ post.title }}</a> <span>({{ post.subtitle }})</span> <span>{{ post.abstract }}</span></li>
    {% endfor %}
  </ul>
</div>

