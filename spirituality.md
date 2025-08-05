---
layout: default
title: Spirituality
permalink: /spirituality/
description: "Uncover deep spiritual lessons from the most impactful books on purpose, presence, and meaning—summarized in short, inspiring reads."
keywords: "spirituality books, mindfulness, meaning of life, purpose, meditation, consciousness, spiritual growth"
---
{% include category-bar.html %}



<h2 style="text-align: center;">Books About Spirituality</h2>

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
    {% for post in site.categories.spirituality %}
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
