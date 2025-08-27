---
title: "HOME"
layout: default
lang: en
nav:
  order: 1
permalink: /
---

# Zhourl Group

{% capture text %}

College of Physics and Optoelectronic Engineering, Harbin Engineering University...

{%
  include button.html
  link="/en/research/"
  text="Research"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}

{%
  include feature.html
  image="images/background2.png"
  link="/en/research/"
  title="Research"
  text=text
%}

{% capture text %}
Project introduction...

{%
  include button.html
  link="/en/projects/"
  text="Projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}

{%
  include feature.html
  image="images/background2.png"
  link="/en/projects/"
  title="Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}
Team introduction...

{%
  include button.html
  link="/en/team/"
  text="Team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}

{%
  include feature.html
  image="images/background2.png"
  link="/en/team/"
  title="Team"
  text=text
%}

