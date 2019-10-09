## Linux简介

Linux 内核由芬兰人林纳斯·托瓦兹（Linus Torvalds）在上学时出于个人爱好而编写的，是一个基于 POSIX 和 UNIX 的多用户、多任务、支持多线程和多 CPU 的操作系统。

市面上的Linux发行版是将Linux内核常见软件进行了打包，市面上较知名的发行版有：Ubuntu、RedHat、CentOS和Debian 等。

与Windows不同的是，Linux系统的所有操作都是可以用命令行终端完成的。在Linux系统中图形界面并不是的第一操作选择。**学习Linux系统，一是学习Linux系统的组成，二是学习Linux系统的命令行操作。**

## Linux目录

在Linux系统中任何资源和配置都是用文件来体现的，Linux目录是必要掌握的知识点。在Linux系统中`/`是根目录的含义，所有的目录文件都是存放在根目录下面，具体含义如下：

- `/bin`存放着最经常使用的命令；
- `/boot`存放启动Linux时使用的核心文件； 
- `/dev`存放的是Linux的外部设备 ；
- `/etc`存放所有的系统管理所需要的配置文件和子目录；
- `/lib`存放系统最基本的动态连接共享库 ；
- `/home`以用户账号命令的用户主目录；
- `/root`超级管理员的主目录；
- `/tmp`存放临时文件，重启后清空；

## Linux远程登录

这里先介绍最简单的IP与密码的登录方式，假设Linux与你的本机在同一局域网内，使用命令`ssh username@ip  `即可完成登录操作。

## Linux目录管理

在Linux系统中目录是树状结构的，最顶级的目录是根目录`/`。在Linux中目录路径有表示方式：

- 绝对路径：从根目录`/`开始写起的目录路径；
- 相对路径：从当前目录写的相对路径，例如由 `/root/tmp1` 要到 `/root/tmp2` 底下时，可以写成： `cd ../tmp2` 。

在Linux中可以使用如下命令行来处理目录文件：

- `ls`列出目录；
- `cd`跳转目录；
- `pwd`显示当前目录；
- `mkdir`创建新目录；
- `rm`删除文件或目录；
- `cp`复制文件或目录；
- `mv`移动文件或目录；

## Linux磁盘管理

TODO

## Linux文件编辑器

TODO

## Linux学习资料

- [Linux教程-菜鸟教程](https://www.runoob.com/linux/linux-tutorial.html)
- [Linux 简易教学 | 莫烦Python](https://morvanzhou.github.io/tutorials/others/linux-basic/)
- 书籍《鸟哥的Linux私房菜》
- 书籍《Linux/UNIX系统编程手册》

