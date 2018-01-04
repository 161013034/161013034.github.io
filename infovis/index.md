---
layout: default
title:  "可视化设计作品集"
date:   2017-12-07 23:45:15 +0800
categories: infovis
---

<div class='tableau1' style='width:800; height:600;'> 
<iframe src="">https://public.tableau.com/profile/.5484#!/vizhome/_18156/1?publish=yes</iframe> 
</div>
<div class="tiles">
{% for post in site.categories.portfolio %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 portfolio 的列出來-->
