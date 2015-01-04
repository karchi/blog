---
layout: default
title: "备忘"
---

备忘录
======

####建blog小tips：
1. 生成文件目录树：`tree [e:\blog\] /F>>list.txt`
2. `<span class="glyphicon glyphicon-time"></span>` 会插入一个小时钟<span class="glyphicon glyphicon-time"></span>。
3. `&raquo;` 会插入一个双箭头&raquo;。
4. 评论  
> 	\< !-- Blog Comments -->  
> 	\< div class="media">  
> 	\{ % include comment.html %}   
> 	\< /div>  

5. 分类。`category: blog`、`category: "blog"`、`categories: [blog,rss]`。
6. jekyll变量：<http://jekyllrb.com/docs/variables/>
7. Note that the `post` variable only exists inside the `for` loop above. If you wish to access the currently-rendering page/posts’s variables (the variables of the post/page that has the `for` loop in it), use the `page` variable instead.
8. 统计词数： `{ { page.content | number_of_words } }` `{{ page.content | number_of_words }}`，更多转换可参考：<http://jekyllrb.com/docs/templates/>

<br>

####网址收藏：
1,Markdown语法：<http://wowubuntu.com/markdown/basic.html>、<http://xuexiii.org/wiki/index.php/Markdown>  
2,git文章收藏:  
Git分支管理策略: <http://www.ruanyifeng.com/blog/2012/07/git.html>    
Git查看、删除、重命名远程分支和tag: <http://zengrong.net/post/1746.htm>

