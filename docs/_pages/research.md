---
layout: default
title: Research
---

<h1> Research</h1>

<ul>
    {% for research in site._research %}
    <li>
      <h2>{{ research.name }}</h2>
      <p>{{ research.content | markdownify }}</p>
    </li>
  {% endfor %}
</ul>
