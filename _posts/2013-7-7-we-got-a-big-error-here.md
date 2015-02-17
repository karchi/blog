---
layout: post
title: "暗黑破坏神2 diablo II 出现“We got a big error here”问题的解决方法"
categories: ["技术"]
tags: ["游戏","diablo","问题"]
date: 2013-7-7 17:20:00
---
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;暗黑破坏神 2 （diablo II）出现“We got a big error here”问题的解决方法。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;karchi我的diablo II 版本为1.13，装了大箱子和hackmap地图补丁，Win 7 系统。问题的症状是**有时进入游戏会出现“We got a big error here”的错误**。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;karchi我做了以下几个步骤以后，就可以正常进入游戏了，不知道具体是哪一步起了作用，各位可以都试试。

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;解决方法如下：

1.运行regedit注册表编辑器，删除HKEY_CURRENT_USER\Software\Blizzard Entertainment\Diablo II 子项下的“InstallPath”和“Save Path”两个键值。最好再重启一下电脑。大部分情况下，做完这步就可以进入游戏了。

2.第一个步骤不行的话，再进行第二个步骤：删除掉暗黑目录下的所有日志文件，即名称为“D??????.TXT”的文件。备份、再删除掉暗黑目录下“default.key”和“bncache.dat”两个文件。“bncache.dat”这个文件可能不存在，不管它。完工！

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;如果做完以上步骤还是不行的话，请删除游戏重装，百度贴吧暗吧置顶帖里有相关游戏资源，质量靠谱。再不行的话。。。别玩游戏了快回去看书复习！
	