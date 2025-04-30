---
title: "환영합니다"
layout: default
---

# 환영합니다!
이 블로그에 오신 것을 환영합니다.  


---

## 최근 글
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>
