---
layout: layout.html
---

# Books

<ul>
{%- for post in collections.post reversed -%}
  <li>
    <a href="{{post.url}}">
      {{ post.data.title}}
    </a>
  </li>
{%- endfor -%}
</ul>

