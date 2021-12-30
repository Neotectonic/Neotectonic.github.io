---
layout: collection
title: Research
permalink: /research/
entries_layout: grid
classes: wide
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
