---
layout: default
title: Money
permalink: /money/
---

<h1>Posts in Category: Money</h1>

<ul>
  {% for post in site.categories.Money %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> – {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>
