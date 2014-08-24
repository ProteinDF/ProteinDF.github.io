---
layout: page
title: ProteinDF software package
---
{% include JB/setup %}

![ProteinDF logo](img/PDFLOGO.jpg "ProteinDF logo")

## About
ProteinDF is a free and open source quantum chemistry calculation software package.

## News
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>  {% endfor %}
</ul>

## License

ProteinDF is licensed under the GNU GPL v3.
The source code can be found on the Github.

## Bugs

If you find any bugs, please let me know.
And if you have a suggestion for improvement, please let me know.
