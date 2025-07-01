---
layout: home
title: 내 블로그에 오신 것을 환영합니다
---

# 환영합니다!

이 페이지는 minimal-mistakes 테마용 기본 홈 페이지입니다.  
여기에 사이트 소개나 공지사항 등을 작성할 수 있습니다.

---

## 최근 게시물

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

---

필요한 경우 내용을 자유롭게 수정해서 사용하세요!
