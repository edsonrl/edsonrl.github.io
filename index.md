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

I am currently a postdoc in the "Scalable Database Systems" group at University of Passau, led by prof. Stefanie Scherzinger.

I received my PhD (2016-2020) from the University of Paraná, Brazil, under the supervision of prof. Eduardo Cunha de Almeida. Before that, I worked as a software engineer (2014-2016) at the SnT, University of Luxembourg, under the supervision of professors Dr. Yves Le Traon and Dr. Eduardo Cunha de Almeida.

My research interest is on data analytics and data-intensive systems (Google Scholar, Google Patents, DBLP, and Lattes).

## Services

<ul>
{% for service in site.data.services %}
  <li>
    <p>
      {{ service.type }}. {{ service.event }}
    </p>
  </li>
{% endfor %}
</ul>


## Selected Publications.

<ul>
{% for publication in site.data.publications %}
  <ul>
    <li>
      {{ publication.title }}. {{ publication.authors }}. {{ publication.venue }}
    </li>
  </ul>
{% endfor %}
</ul>


