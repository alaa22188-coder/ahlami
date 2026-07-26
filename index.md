---
layout: default
title: الرئيسية
---

# أهلاً بك في موقع أحلامي!

## أحدث تفسيرات الأحلام:

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> — {{ post.date | date: "%Y/%m/%d" }}
    </li>
  {% endfor %}
</ul>
