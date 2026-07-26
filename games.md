---
layout: default
title: "قسم ألعاب واختبارات"
permalink: /games/
---

# 🎮 قسم ألعاب واختبارات الترفيهية

## الإضافات المتاحة حالياً في هذا القسم:

<ul>
  {% for post in site.categories.games %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> 
      <p style="font-size: 14px; color: #666; margin: 5px 0;">{{ post.description }}</p>
    </li>
  {% endfor %}
</ul>
