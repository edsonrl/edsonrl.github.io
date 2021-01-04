---
layout: default
---

<ul>
{% for navigation in site.data.navigation %}
  <li>
    <a href="https://erlfilho.github.io/{{ navigation.link }}">
      {{ navigation.name }}
    </a>
  </li>
{% endfor %}
</ul>

{% include about.md %}

