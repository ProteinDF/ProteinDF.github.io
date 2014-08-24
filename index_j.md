---
layout: page
title: "ProteinDF software package"
description: ""
---
{% include JB/setup %}

[English](./index.html)
[Japanese](./index_j.html)

![ProteinDF logo](img/PDFLOGO.jpg "ProteinDF logo")

## Abount
ProteinDF はオープンソースの量子化学計算ソフトウェアパッケージです。

## News
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>  {% endfor %}
</ul>

## License
ProteinDFはGNU GPL v3に基づいて配布されます。
ソースコードはGithubから取得できます。

## バグ・要望
バグを発見された場合はご連絡ください。
また機能追加などのご要望もお知らせ下さい。
