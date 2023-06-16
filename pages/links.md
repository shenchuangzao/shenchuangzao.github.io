---
layout: page
title: 创造科学网站链接
description: 
keywords: 友情链接
comments: true
menu: 链接
permalink: /links/
---

> 中文

<ul>
{% for link in site.data.links %}
  {% if link.src == 'cn' %}
  <li><a href="{{ link.url }}" target="_blank">{{ link.name}}</a></li>
  {% endif %}
{% endfor %}
</ul>

> 英文

<ul>
{% for link in site.data.links %}
  {% if link.src == 'en' %}
  <li><a href="{{ link.url }}" target="_blank">{{ link.name}}</a></li>
  {% endif %}
{% endfor %}
</ul>


> 日文

<ul>
{% for link in site.data.links %}
  {% if link.src == 'jp' %}
  <li><a href="{{ link.url }}" target="_blank">{{ link.name}}</a></li>
  {% endif %}
{% endfor %}
</ul>
