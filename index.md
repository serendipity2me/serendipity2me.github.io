---
layout: home
author_profile: true
header:
  overlay_image: /assets/images/header.jpg
  overlay_filter: 0.5
  caption: "기록이 쌓여가는 작은 연구실"
title: "Welcome to My Music Lab"
excerpt: "음악을 연구하고, 배우며, 함께 성장하는 공간"
---

## 🎵 About This Blog
안녕하세요! 이 블로그는 **음악을 공부하고 연구하는 기록 공간**입니다.  
사운드 디자인, 리듬 분석, 미디 프로그래밍, 그리고 다양한 음악적 생각들을 자유롭게 적어 내려갑니다.

> "지금의 내가 내일의 나를 만든다."

블로그를 통해 저의 성장을 함께 지켜봐 주세요! 😊

---

## ✍️ Latest Posts
<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>

---

## 🛠 Categories
{% for category in site.categories %}
- [{{ category[0] }}](/categories/#{{ category[0] | slugify }})
{% endfor %}

---

## 📬 Contact
궁금한 점이나 함께 이야기 나누고 싶으신 분은 [Contact](/contact/) 페이지를 통해 언제든 편하게 연락 주세요!
