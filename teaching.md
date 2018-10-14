---
layout: default
title: Teaching
---

### Classes
<ul>
  {% for cls in site.teaching %}
    <li>
      <a href="{{ cls.url }}">{{ cls.title }}</a>
    </li>
  {% endfor %}
</ul>