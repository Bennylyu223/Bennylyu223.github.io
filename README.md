这是吕延青的个人博客仓库
==========
-----
试试博客框架或者自己手撸一个



## 一、github 搭建个人博客
-----

### 1. 新建私人仓库
>Bennylyu223.github.io.git



### 2. try something git
通过实操，掌握一些git中的基本概念以及命令，以投入实际项目。
git的核心概念是**提交**，无论是合并还是变基，都基于提交。
提交又基于两个概念：_快照（checksum）_ 以及 _增量（patch）_ ，这两个概念的存在，催生出提交的一系列有趣的功能
```bash
git log --oneline --decorate --graph --all
```
可用该命令查看提交历史以及分支概况。

此外，还学习了
1. merge 和 rebase 的不同；就我个人而言，忠实还原提交记录较为直观清晰，merge是我的首选。
2. 远程仓库的一些操作 主要围绕三个命令 pull push merge进行。