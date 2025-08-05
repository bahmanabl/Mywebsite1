---
layout: default
title: Psychology
permalink: /psychology/
description: "Explore short summaries of the best psychology books—unlocking deep insights into behavior, decision-making, and the human mind."
keywords: "psychology books, behavior science, human mind, decision making, cognitive bias, book summaries"
---
{% include category-bar.html %}



<h2 style="text-align: center;">Books About Psychology</h2>

<div style="
  background-color: white;
  padding: 20px;
  border-radius: 16px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  margin: 0 auto 20px auto;
  width: 100%;
  box-sizing: border-box;
">
    <div style="
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
  ">
    {% for post in site.categories.psychology %}
      <!-- Post preview box -->
      <div style="border: 1px solid #ccc; border-radius: 12px; padding: 10px;">
        <a href="{{ post.url | relative_url }}">
          <img src="{{ post.image }}" alt="Thumbnail for {{ post.title }}" style="width: 100%; border-radius: 8px;">
          <h3 style="text-align: center;">{{ post.title }}</h3>
        </a>
      </div>
    {% endfor %}
  </div>
</div>
