---
layout: default
title: Money
permalink: /Mywebsite1/categories/money/
---

<h1>Posts in Category: Money</h1>

<div style="display: flex; flex-wrap: wrap; gap: 1.5rem; justify-content: space-between;">
  {% for post in site.categories.Money %}
    <div style="flex: 1 1 30%; min-width: 260px;">
      <a href="{{ post.url | relative_url }}" style="text-decoration: none; color: inherit;">
        {% if post.image %}
          <img src="{{ post.image }}" alt="{{ post.title }}" style="width: 100%; border-radius: 8px; margin-bottom: 0.5rem;">
        {% endif %}
        <h3 style="margin: 0; font-weight: bold; font-size: 1.1rem;">
          {{ post.title }}
        </h3>
      </a>
    </div>
  {% endfor %}
</div>
