---
layout: collection
title: "Posts"
permalink: /posts/
classes: wide
---

<ul>
    {% for posts in site._posts %}
    <li>
      <h2>{{ posts.name }}</h2>
      <p>{{ posts.content | markdownify }}</p>
    </li>
  {% endfor %}
</ul>

