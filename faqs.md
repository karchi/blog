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
9. 如果你想使用你某篇文章的链接，标签`post_url`可以满足你的需求:`{ % post_url 2010-07-21-name-of-post % }`。当使用post_url标签时，不需要写文件后缀名。还可以用Markdown为文章生成超链接：`[ Name of Link ]( { {site.baseurl} }{ % post_url 2010-07-21-name-of-post % } )`
10. jekyll中文介绍：<http://jekyllcn.com/>
11. Jekyll 语法简单笔记：<http://github.tiankonguse.com/blog/2014/11/10/jekyll-study/>
12. jekyll 模板：<http://jekyllthemes.org/>

<br>

####网址收藏：
1,Markdown语法：<http://wowubuntu.com/markdown/basic.html>、<http://xuexiii.org/wiki/index.php/Markdown>  
2,git文章收藏:  
Git分支管理策略: <http://www.ruanyifeng.com/blog/2012/07/git.html>    
Git查看、删除、重命名远程分支和tag: <http://zengrong.net/post/1746.htm>

