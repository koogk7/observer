---
layout: page
title: observer
---

글이 두 갈래로 나뉩니다 — **개인 에세이**와 **중국어 수업(江遥)**.

## 📝 에세이

<ul>
{% for post in site.categories.essay %}
  <li>{{ post.date | date: "%Y-%m-%d" }} · <a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

## 📚 中文 수업 · 江遥

<ul>
{% for post in site.categories['zh-class'] %}
  <li>{{ post.date | date: "%Y-%m-%d" }} · <a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
