# Linux-Notes

#### 一：学习笔记

Date: 2016-10-14

这里包含了慕课网课程 ——《Linux达人养成计划 Ⅰ》的课堂笔记。文章有 word、html、pdf 三种版本，内容一致。

其中 pdf 单行本下载地址为 [Linux Notes.pdf | Google Drive](https://drive.google.com/open?id=0B-swxIcRWt5Ea0NZVF9DdHZLeW8)

内容为 Tony 老师所授内容以及自己在 CentOs 7 上的演示。

* 命令格式
* 目录处理命令（上）
* 目录处理命令（下）
* 常见目录作用
* 链接命令
* 文件搜索命令locate
* 命令搜索命令
* 文件搜索命令find
* 字符串搜索命令grep
* 帮助命令man
* 其他帮助命令
* 压缩命令1
* 压缩命令2
* 关机与重启命令
* 挂载命令
* 用户登录查看命令
* Shell 概述
* 脚本执行方式
* 别名与快捷键
* 历史命令
* 输出重定向
* 管道符
* 通配符

#### 二、编写环境

Linux 版本为 CentOs 7，使用工具为 VirtualBox 以及 Xshell 5。

#### 三、补充

Tony 老师用的是 CentOs 6.3 的版本，视频中部分内容并不适合 CentOs 7 的学习。

可以参考我之前写的文章 [虚拟机装 CentOs 7 黑屏解决办法](https://gaea2.github.io/2016/10/05/%E8%99%9A%E6%8B%9F%E6%9C%BA%E8%A3%85%20CentOs%207%20%E9%BB%91%E5%B1%8F%E8%A7%A3%E5%86%B3%E5%8A%9E%E6%B3%95/)，其他内容在 Linux Notes (本文 中将有所涉及。如

> [root@localhost ~]# runlevel
N 3
代表一开机N 就进入了 字符界面(3 也就是完全多用户；前一个数字(N 代表上一个级别，后一个数字(3 是当前级别
不过，需要注意的是，在systemd掌权后，inittab不再起作用，也没有了“运行级”的概念。也就是说，以上有点过时了。
参考 http://blog.csdn.net/smstong/article/details/39317491
以及 http://www.tuicool.com/articles/zmYf2yN

#### 四、结语

希望能对初学 Linux 的同学有所帮助。如有不足欢迎在 issue 中指正。
