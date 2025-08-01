---
layout: default
title: Psychology
permalink: /psychology/
description: "RAGWise delivers short, insightful, and animated book summaries on money, mindset, relationships, spirituality, and personal growth—designed to make life-changing ideas easy to understand and apply."
keywords: "book summaries, book reviews, RAGWise, best books to read, top book recommendations, book insights, personal development books, self-help book summaries, psychology book summaries, finance book summaries
s"
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
<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; padding: 20px;">
  {% for post in site.categories.psychology %}
    <div style="border: 1px solid #ccc; border-radius: 12px; padding: 10px;">
      <a href="{{ post.url | relative_url }}">
        <img src="{{ post.image }}" alt="thumbnail" style="width: 100%; border-radius: 8px;">
        <h3 style="text-align: center;">{{ post.title }}</h3>
      </a>
    </div>
  {% endfor %}
</div>
</div>
