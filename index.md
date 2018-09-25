---
layout: home
author_profile: true
mathjax: true
sidebar:
  nav: sidebar-sample
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
