---
title: git 入门
date: 2018-04-23 17:22:09
tags:
---
git 

# 配置git
1. git config --global user.name 你的英文名
2. git config --global user.email 你的邮箱
等

# 使用git

首先，对最基础的本地git使用进行介绍：

1. git init 初始化 git 仓库，这会在仓库目录创建一个名叫 .git 的目录
   i. git init xxx 创建仓库同时初始化仓库
   ii. mkdir xxx; cd xxx; git init; 先创建仓库，再初始化
   eg:
   ![](https://github.com/verajian/verajian.github.io/blob/master/images/20180424-1.png?raw=true)

2. git add 将文件添加到暂存区
   i. 可以一个一个的添加，比如：
      git add xxx.html
      git add js/xxx.js
   ii. 也可以一次性把当前目录里的所有变动都添加到暂存区 
      git add .
   eg: 
   ![](https://github.com/verajian/verajian.github.io/blob/master/images/20180424-2.png?raw=true)

3. git commit -v 将你 add 过的内容「正式提交」到本地仓库（.git就是本地仓库） 
   这种方式提交，会打开默认的编辑器(比如vim), 让你输入本次提交信息，并且会显示所有变动的详细信息
   eg: 
   ![](https://github.com/verajian/verajian.github.io/blob/master/images/20180424-3.png?raw=true)
   ![](https://github.com/verajian/verajian.github.io/blob/master/images/20180424-4.png?raw=true)
