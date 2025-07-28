---
layout: default
title: Spirituality
permalink: /spirituality/
---
<nav class="category-bar">
  <a href="/" {% if page.url == "/" %}class="active"{% endif %}>All Posts</a>
  <a href="/personal-development/" {% if page.url == "/personal-development/" %}class="active"{% endif %}>Personal Development</a>
  <a href="/money/" {% if page.url == "/money/" %}class="active"{% endif %}>Money</a>
  <a href="/relationships/" {% if page.url == "/relationships/" %}class="active"{% endif %}>Relationships</a>
  <a href="/spirituality/" {% if page.url == "/spirituality/" %}class="active"{% endif %}>Spirituality</a>
  <a href="/psychology/" {% if page.url == "/psychology/" %}class="active"{% endif %}>Psychology</a>
</nav>


<h2 style="text-align: center;">Book Summaries about Spirituality</h2>

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; padding: 20px;">
  {% for post in site.categories.Money %}
    <div style="border: 1px solid #ccc; border-radius: 12px; padding: 10px;">
      <a href="{{ post.url | relative_url }}">
        <img src="{{ post.image }}" alt="thumbnail" style="width: 100%; border-radius: 8px;">
        <h3 style="text-align: center;">{{ post.title }}</h3>
      </a>
    </div>
  {% endfor %}
</div>
