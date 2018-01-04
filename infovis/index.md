---
layout: archive
title: "信息可视化作品集"
date: 2017-12-30T11:40:45-04:00
modified:
excerpt: "信息可视化笔记与作品"
tags: []
image: 
  feature: smilec.jpg
  teaser:
---

信息可视化入门
1. 信息可视化（Information visualization）是一个跨学科领域，旨在研究大规模非数值型信息资源的视觉呈现（如软件系统之中众多的文件或者一行行的程序代码）。通过利用图形图像方面的技术与方法，帮助人们理解和分析数据。（via:百度百科）
2. 再次我需要向你介绍一个软件，Tableau
- Tableau 帮助任何人快速分析、可视化并分享信息。超过 42,000 家客户通过使用 Tableau 在办公室或随时随地快速获得结果。数以万计的用户使用Tableau Public在博客与网站中分享数据。
- [Tableau下载网站](https://www.tableau.com/zh-cn/products/desktop)
- [Tableau相关教学视频](https://public.tableau.com/zh-cn/)，你可以通过这个网址进行基础的学习。
- [炫酷的可视化](https://public.tableau.com/en-us/s/gallery)，这个网站上面会选出由世界各地的Tableau爱好者每天上传的最优秀的的tableau作品

Tableau的产品特性
1. 轻松整合。共享内置于 Tableau Desktop 的分析视角。
2. 交互性。您可以过滤、排序并深入挖掘特定的详细信息。
3. 完全免费。只需下载即可开始浏览数据。

我的第一份不太成熟的Tableau作品
1. 这是一张我的老师要求我们做的作品。
2. 我用Python代码将数据抓出来，在这个过程中使用到了高德地图的API。
3. 在进行了简单的数据清理之后，我将数据上传至了Tableau，做成了地图的形式，将种类进行了颜色的区分，可以很清楚的在地图上分开四者，并且知道其大致的分布。
(http://161013034.guthub.io/images/xiaguanzi.png)

<div class="tiles">
{% for post in site.categories.portfolio %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 portfolio 的列出來-->
