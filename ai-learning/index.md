---
layout: default
title: AI Learning
permalink: /ai-learning/
---

# AI Learning Log

AI 활용, 개발 및 AI 시스템 제작을 공부하며 기록하는 공간입니다.

## Learning History

{% assign ai_posts = site.posts | where_exp: "post", "post.categories contains 'AI Learning'" %}

{% for post in ai_posts %}
### [{{ post.title }}]({{ post.url | relative_url }})

<small>{{ post.date | date: "%Y-%m-%d" }}</small>

{{ post.excerpt | strip_html | truncate: 150 }}

---
{% else %}
아직 등록된 학습 기록이 없습니다.
{% endfor %}
