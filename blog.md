---
layout: default
title: Blog · Abraham Thomas
---

## 2020
<ul>
  {% for post in site.posts %}
    <li>
      <span style="color: #A9A9A9;">{{ post.date | date: "%Y-%m-%d" }}:</span> 
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

----

[Subscribe via RSS](https://abrahamthomas.info/feed.xml)