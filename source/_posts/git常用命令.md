---
title: git常用命令
date: 2019-03-29 22:59:52
tags: 技术
categories: git
---

###### 一、git基本命令

1.git创建分支并提交到远程分支

```
git checkout -b hexo    #创建hexo分支并进入该分支
git branch				#查看以有分支
git push origin hexo	#提交该分支到远程仓库
git branch --set-upstream-to=origin/hexo	#建立本地到远端仓的链接
```

<!-- more -->

2.将一个远程库拷贝到本地

```
git clone https://github.com/linuxgrf/linuxgrf.github.io.git
```

3.检查当前跟踪文件的状态

```
git status
```

4.提交更新

```
git add
git commit -m "说明字符串"	#提交保存到仓库
```

###### 二、git分支管理

1.创建分支命令

```
git branch (branchname)
```

2.切换分支命令

```
git checkout (branchname)
```

3.合并分支

```
git merge (branchname)
```

4.创建新分支并切换到该分支下

```
git checkout -b (branchname)
```

5.删除分支命令

```
git branch -d (branchname)
```



###### 三、查看日志版本

1.列出历史提交记录

```
86155@DESKTOP-O99ELN7 MINGW64 /g/Hexo/linuxgrf.github.io (hexo)
$ git log
```

2.查看历史记录的简洁版本

```
git log --oneline
```

3.查看历史中什么时候出现分支、合并

```
git log --oneline --graph
```

