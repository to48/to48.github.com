---
layout: page
title: Jekyll と github を手足のように使えるようになったら楽しいな
tagline: Supporting tagline
---
{% include JB/setup %}

##Jekyll 習得中・・・別ブランチ
とっしゃんのblogへ、ようこそ。  
Jekyll と github をもっと使えるようになったら良いな〜と思いながら、習得も兼ねて手作りしています。

（このページは、ruby + jekyll + jekyll bootstrap で作られています。）

## 最近の投稿
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

