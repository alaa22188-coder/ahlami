---
layout: default
title: الرئيسية
---

# أهلاً بك في موقعي الجديد!

هنا سأقوم بنشر المقالات والألعاب الستاتيك الخاصة بي.

## أحدث الإضافات والمقالات:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> — {{ post.date | date_to_string }}
    </li>
  {% endfor %}
</ul>
