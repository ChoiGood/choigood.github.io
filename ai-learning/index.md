---
layout: default
title: AI Learning
permalink: /ai-learning/
---

{% include navigation.html %}

# AI Learning Log

AI 활용, 개발 및 AI 시스템 제작을 공부하며 기록하는 공간입니다.

## Learning Roadmap

12주 동안 AI 활용부터 AI 응용 프로그램 개발, AI 시스템 제작까지 단계적으로 학습합니다.

[12주 AI 학습 로드맵 확인하기](./roadmap/)

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
