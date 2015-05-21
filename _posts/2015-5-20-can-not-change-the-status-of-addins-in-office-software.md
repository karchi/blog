---
layout: post
title: "解决：无法更改HKEY_LOCAL_MACHINE中注册的Office加载项的连接状态"
categories: ["技术"]
tags: ["问题","office","加载项","权限","注册表"]
date: 2015-5-20 23:50:34
---
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;问：想更改word、excel等office软件中各个加载项的状态，出现“无法更改HKEY_LOCAL_MACHINE中注册的Office加载项的连接状态”的提示，各加载项的状态无法更改，请问如何解决？

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;答：该问题是由于win7系统的管理员权限设置所导致的。找到office软件所在的文件夹（以笔者的软件位置为例，在C:\Program Files\Microsoft Office\Office12），右键点击office软件图标，选择“以管理员身份运行”，打开软件后再进入设置卡的加载项一栏进行设置，即可解决以上问题。
