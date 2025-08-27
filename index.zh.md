---
title: "首页"
lang: zh
nav:
  order: 1
permalink: /zh/
---

# 周仁来课题组

哈尔滨工程大学物理与光电子工程学院...

{% include section.html %}

## 课题组研究内容

{% capture text %}

研究方向：飞秒光纤激光技术及其应用；新型锁模激光技术..

{%
  include button.html
  link="/zh/research/"
  text="论文"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}

{%
  include feature.html
  image="images/background2.png"
  link="/zh/research/"
  title="研究内容"
  text=text
%}

{% capture text %}
项目介绍...

{%
  include button.html
  link="/zh/projects/"
  text="项目"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}

{%
  include feature.html
  image="images/background2.png"
  link="/zh/projects/"
  title="研究项目"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}
团队介绍...

{%
  include button.html
  link="/zh/team/"
  text="研究团队"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
{% endcapture %}

{%
  include feature.html
  image="images/background2.png"
  link="/zh/team/"
  title="团队"
  text=text
%}

