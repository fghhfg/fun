---
layout: default
---

<ul>
  {% for file in site.static_files %}
    <li>
      <a href="{{ file.path | relative_url }}">{{ file.name }}</a>
    </li>
  {% endfor %}
</ul>
