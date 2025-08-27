---
title: 团队
lang: zh
nav:
  order: 4
permalink: /zh/team/
---

<!--# {% include icon.html icon="fa-solid fa-users" %}Team-->
# 团队

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

