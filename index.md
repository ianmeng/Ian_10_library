---
layout: layout.html
---

# Books

<ul>
{%- for book in collections.book reversed -%}
  <li>
    <a href="{{book.url}}">
      {{ book.data.title }}
    </a>
  </li>
{%- endfor -%}
</ul>

