## 什么是Git
git是一个`分布式`的`版本控制系统`,Linus Torvalds 为了帮助管理 Linux 内核开发而开发的一个开放源码的版本控制软件
## 如何使用Git
### Git安装
macos终端下,利用homebrew 安装
```
$  brew install git
```
### Git常用指令
使用当前目录作为 Git 仓库，我们只需使它初始化。
```  
$ git init 
```
当前目录下有几个文件想要纳入版本控制，需要先用 git add 命令告诉 Git 开始对这些文件进行跟踪，然后提交一个commit作为此次更改的注释

```
git add .
git commit -m '初始化项目版本'
```




