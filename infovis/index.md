---
layout: archive
title: "信息可视化作品集"
date: 2017-12-30T11:40:45-04:00
modified:
excerpt: "信息可视化笔记与作品"
tags: []
image: 
  feature: 
  teaser:
---

我的第一份不太成熟的Tableau作品
1. 这是一张我的老师要求我们做的作品，我选择了博物馆、海洋馆、蜡像馆、科技馆、美术馆、艺术馆，我跑出了大约55000+的数据。
2. 我用Python代码将数据抓出来，在这个过程中使用到了高德地图的API。
3. 在进行了简单的数据清理之后，我将数据上传至了Tableau，做成了地图的形式，将种类进行了颜色的区分，可以很清楚的在地图上分开四者，并且知道其大致的分布。

信息可视化期末作品：
1. 下图是科技馆、艺术馆、美术馆、蜡像馆、海洋馆、博物馆在全国范围的分布，做成了地图形式。
![image](https://161013034.github.io/images/ditu.png)
2. 下图是科技馆、艺术馆、美术馆、蜡像馆、海洋馆、博物馆在全国各省的总数条形图，可以对比看出哪个省份总数量最多。
![image](https://161013034.github.io/images/tiaoxintu2.png)
3. 下图是科技馆、艺术馆、美术馆、蜡像馆、海洋馆、博物馆在全国各省的数量的表格分析，直观的数据量配上颜色的深浅更有利于分析。
![image](https://161013034.github.io/images/biaoge.png)
4. 下图是科技馆、艺术馆、美术馆、蜡像馆、海洋馆、博物馆在全国各省的数量条形图分析，可以通过颜色的比较看出各省什么展馆最多。
![image](https://161013034.github.io/images/tiaoxintu.png)
5. 下图是科技馆、艺术馆、美术馆、蜡像馆、海洋馆、博物馆在全国数量饼图分析，可以通过所占面积大小看出展馆在全国的数量。
![image](https://161013034.github.io/images/bintu.png)

<div class="tiles">
{% for post in site.categories.portfolio %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 portfolio 的列出來-->
