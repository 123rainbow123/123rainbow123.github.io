---
layout: archive
title: "信息可视化作品集"
date: 2017-12-30T11:40:45-04:00
modified:
excerpt: "小渣做的可视化图"
tags: []
image: 
  feature: cccc.jpg
  teaser:
---

在此展示信息可视化作品集，好的丶可改进的及有趣的

<div class="tiles">
{% for post in site.categories.infovis%}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 portfolio 的列出來-->