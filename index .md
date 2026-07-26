---
layout: default
title: الرئيسية
---

# أهلاً بك في موقع احلامي!.

## أحدث تفسيرات الاحلام:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> — {{ post.date | date_to_string }}
    </li>
  {% endfor %}
</ul>
