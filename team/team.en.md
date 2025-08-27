---
title: Team
lang: en
nav:
  order: 4
permalink: /en/team/
---

<!--# {% include icon.html icon="fa-solid fa-users" %}Team-->
# Team

{% include section.html %}

{% assign groups = site.data.members | group_by: "role" %}

{% for group in groups %}
  <h3>{{ group.name | replace: "-", " " | capitalize }}</h3>
  <div class="team-group">
    {% for d in group.items %}
      {%
        include portrait.html
        lookup=d.slug
        style="default"
      %}
    {% endfor %}
  </div>
{% endfor %}



