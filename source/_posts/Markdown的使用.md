---
title: hexo下Markdown的使用
date: 2019-03-29 00:06:27
categories: Hexo教程
tags: 技术
password: 123
---

**一、创建文章**

在站点文件夹中打开 git bash，输入如下命令创建文章，其中 `title` 为文章的标题

*$ hexo new "title"*

当输入命令后，就会在 `source/_post` 文件夹下创建一个文件，命名为：`title.md`

这个文件就是将要发布到网站上的原始文件，用于记录文章内容。

<!-- more -->

**二、编写文章**

###### 1、Markdown 简介

*Markdown 是一种可以使用普通文本编辑器编写的 **标记语言**，通过简单的 **标记语法**，它可以使普通文本内容具有一定的格式*

###### 2、Markdown语法

**Typora 快捷键：**

*Ctrl+1：一级标题*

*Ctrl+2：二级标题*

*Ctrl+3：三级标题*

Ctrl+4：四级标题

Ctrl+5：五级标题

Ctrl+6 ：六级标题

*Ctrl+0：段落*

###### 3、粗体、斜体、删除线和下划线

**Markdown 语法：**

```
*斜体*
**粗体**
***加粗斜体***
~~删除线~~
1234
```

**Typora 快捷键：**

Ctrl+I：斜体

Ctrl+B：粗体

Ctrl+U：下划线

Alt+Shift+5：删除线

###### 4、引用块

> 1.>文字引用
>
> ###### 5、代码块
>
> **Markdown 语法：**
>
> ```
> `行内代码`
> 
> ​```
> 多行代码
> 多行代码
> ​```
> ```
>
> **Typora 快捷键：**
>
> 行内代码：Ctrl+Shift+`
>
> 多行代码：Ctrl+Shift+K
>
> 

