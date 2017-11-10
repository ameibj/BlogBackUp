---
title: git学习笔记
date: 2017-11-11 13:11
tags: [git命令]
reward: true
toc: true
comment: true
---

### git删除github远程分支
git push  [远程主机名] :[远程分支名]
例如想删除远程主机 develop 分支，运行下面的命令：
        
        git push origin :develop
        
        注意origin后面有空格
        
        