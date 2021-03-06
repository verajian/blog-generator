---
title: Linux 基础命令学习
date: 2018-04-23 15:32:16
tags:
---
linux 命令乍一看不好记，实际它大多都是该命令含义的英文单词缩写。所以，知道命令的含义及其英文单词，那么记起命令来也就比较容易。比如像下面这些基础命令：

| 命令            | 全写             |  缩写     |
| --------        | -----:           | :----:    |
| 创建目录        | make directory   |   mkdir   |
| 删除            | remove           |   rm      |
| 移动 / 重命名   | move             |   mv      |
| 复制            | copy             |   cp      |
| 列出            | list             |   ls      |
| 改变目录        | change directory |   cd      |

命令除了主体，为了精确描述，一般还会带一些选项和参数。比如：

1. ls 
   ls 列出当前目录下的文件及目录
   ls -a 列出当前目录下的所有文件及目录
   ls -l 以详细信息列表的形式，列出当前目录下的文件及目录
   ls -al 以详细信息列表的形式，列出当前目录下的所有文件及目录

2. cat
   cat 查看文件的内容（执行命令后，文件的内容会输出到命令行的屏幕，以供查看）

3. mv
   mv 移动文件位置；若在同一目录下，则是重命名
 
4. touch
   touch 创建文件；如果文件已经存在，则是改变文件的创建时间

除了这些基础命令的选项参数，如果想学习其它命令及其选项参数的话，可以到 [explainshell.com](https://explainshell.com/) 搜索学习
比如这样：
![](https://github.com/verajian/verajian.github.io/blob/master/images/20180423-1.png?raw=true)
