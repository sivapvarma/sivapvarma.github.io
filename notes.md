---
layout: default
title: Notes
---

### Notes
<ul>
  {% for note in site.notes %}
    <li>
      <a href="{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

