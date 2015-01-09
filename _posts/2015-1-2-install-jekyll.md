---
layout: post
title: "如何在本机搭建jekyll环境"
categories: ["技术",]
tags: ["blog","jekyll","命令行","github","website","建站","ruby","指南","问题"]
date: 2015-1-2 12:17:00
excerpt: "本文主要介绍在本地搭建jekyll环境，使本机也能预览托管在github上的网站效果，以便上传至服务器后能正确展示。"
---
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;本文主要介绍在本地搭建jekyll环境，使本机也能预览托管在github上的网站效果，以便上传至服务器后能正确展示。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;主要参考了jekyll项目的介绍：<http://jekyllrb.com/docs/windows/#installation>。由于karchi我是在windows平台上安装的，所以也参考了windows平台上的安装指南：<http://jekyll-windows.juthilo.com/>。

1. 首先，在<http://rubyinstaller.org/downloads/> 下载Ruby，karchi我下载的是ruby2.1.5。安装的时候选取“Add Ruby executables to your PATH”打勾。**安装目录绝对不要有空格！！**例如E:\Program Files\ 这样的格式就不行，会引起后边一些很麻烦的问题。  
![安装ruby](http://7tsz4l.com1.z0.glb.clouddn.com/安装ruby.jpg-water)  

2. 第二步是安装the Ruby DevKit，下载地址也是：<http://rubyinstaller.org/downloads/> ，在左边找到DEVELOPMENT KIT，选择相对应的版本下载。  
![选择rubyket版本](http://7tsz4l.com1.z0.glb.clouddn.com/选择RubyDevKit版本.jpg-water)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;下载的是一个自解压文件，双击它释放到一个文件夹，例如E:\RubyDevKit，**安装目录也绝对不要有空格！！**，运行命令行模式（win + R，然后输入cmd打开），进入解压缩的文件夹（命令是cd E:\RubyDevKit）。（此时可更新一下，但应该不是必须的，输入命令：`gem update --system`。）输入初始化命令：`ruby dk.rb init`、以及安装命令：`ruby dk.rb install`。

3. 接下来是安装jekyll，在命令行模式输入：`gem install jekyll`。看到最后出现类似“31 gems installed”就说明安装成功。

4. 然后安装Rdiscount，这个是用来解析Markdown标记的解析包。命令：`gem install rdiscount`。也可以安装其他解析包，安装命令类似。

5. windows下还需要安装多一个：`gem install wdm`。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;至此，本地环境搭建完成。再接下来就是编写网站，主要是首页index.html、设置文件_config.yml等，这需要用到一些网站设计的知识，可参考别人写好的模板。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;本地预览：将写好的网站文件放入一个文件夹内，运行命令：`jekyll server`。然后打开浏览器输入地址`http://127.0.0.1:4000/` 就可以预览网站效果。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;如果想将blog托管在github，就将网站的各种文件上传至github。（这又是一项大工程，容karchi我以后有时间再叙。）

-------以下是无关内容-------

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;后记：在blogbus上写了近10年的博客无故被锁，虽然经打电话、发邮件沟通后得以解封，不过karchi我已经对国内运营商失望至极，于是自己动手重新搭建一个，也因此有了以上这篇文章。唉，技术宅都是逼出来的。以此作为karchi我2015年blog生活的开端吧。