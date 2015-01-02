---
layout: default
title: "分类"
---
<ul class="list-unstyled">
{% for cat in site.categories %} 
   <a name="{{ cat[0] }}"></a> <!-- 设置锚点 -->
   <h2>{{ cat[0] }} <sub>({{ cat[1].size }})</sub></h2>
     {% for post in cat[1] %} 
    <li><h4><span>{{ post.date | date:"%Y-%m-%d" }}</span>：<a href="{{ post.url }}">{{ post.title }}</a></h4></li>
	{% endfor %} 
{% endfor %} 
</ul>
