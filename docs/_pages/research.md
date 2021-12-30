---
layout: collection
title: Research
header:
  image: /assets/images/rsrchbanner.jpg
collection: research
permalink: /research/
entries_layout: grid
classes: wide
---


<ul>
    {% for research in site._research %}
    <li>
      <h2>{{ research.name }}</h2>
      <p>{{ research.content | markdownify }}</p>
    </li>
  {% endfor %}
</ul>
