# Bitnami-Redmine 简略使用说明

## 1.软件简介
Redmine是基于ROR框架开发的一套跨平台项目管理系统，是项目管理系统的后起之秀，据说是源于Basecamp的ror版而来，支持多种数据库，除了和DotProject的功能大致相当外，还有不少自己独特的功能，例如提供wiki、新闻台、时间跟踪、feed聚合、导出pdf等，还可以集成其他版本管理系统和BUG跟踪系统，例如SVN、CVS、TD等等。

## 2.注册、登录与激活

### administrator

点击右上方三线标志可以登录和注册。作为administrator，在安装该软件的时候已经注册了账户。在下载完成后直接登录即可。用户名是安装时提示输入为login的项。

![83@`UC3ULFB[[C6`874R{GU.png](https://i.loli.net/2018/09/30/5bb087ee30f56.png)

如果是非adminstrator用户，那么注册后必须等待administator把他的账户激活才可以使用。以下administrator的方式，进入主界面后点击administration：

![03D{%~[$7162Y_JK`U03)FI.png](https://i.loli.net/2018/09/30/5bb0884326f12.png)

 于是会出现：
 
 ![}MS(YE$HP](1O085UTM{}20.png](https://i.loli.net/2018/09/30/5bb088f0677b5.png)
 
 点击users，并且在status中选择registered，选择后会出现一些未激活的用户，点击他们的login：
 
 ![E}C@PVY8)K81P8~_E)X%XV2.png](https://i.loli.net/2018/09/30/5bb08932910b7.png)
 
 这时可以看到这个用户的基本信息，administrator在查看正确无误后可点击activaed选项，稍等片刻后就激活成功了。
 
 ### 非administrator用户
 非administrator的用户账号被激活后就可以登录了，这是非administrator用户的界面：

![1~KG3YC77U`654MU%4B}1@T.png](https://i.loli.net/2018/09/30/5bb08a2191363.png)

## 3.新建一个项目

以下为作为administrator的角色为例子:
登录后点击页面右上角三线标志，会出现project的选项，点击：

![6YZLBZ(A)HMLG6_8N_FH`TW.png](https://i.loli.net/2018/09/30/5bb08cf8311fc.png)

进入后点击New project就可以新建一个项目，以下是完成上面若干步骤后出现的页面：

![DHZVHGTI0UHICIIP2{E(K]Y.png](https://i.loli.net/2018/09/30/5bb08d5bd70e4.png)

![~NNK5IFMPWU42EX4T7BY(2B.png](https://i.loli.net/2018/09/30/5bb08d9abb0f0.png)

可根据提示输入或选择相应的内容，之后点击creat即可。对要输入的内容进行一些简单说明：
I 输入项目的名

II 从下拉列表里选择上级栏目，对项目简单描述

III 填写标识

IV 公开选项:为登录也能看到

V 选择跟踪连接

![6_P808$O2{~KV7{[0B5XB00.png](https://i.loli.net/2018/09/30/5bb08e4ce666c.png)

之后可以在project里看到它：

![333`8TJ]28}7QMZ_ZK~X`ZJ.png](https://i.loli.net/2018/09/30/5bb08e8c52f8b.png)

## 4.发布问题

登录后，点击右上角的三线标志，选择issues。就会出现如下，选择New issues就可以新建问题。根据相应提示输入相关即可（它自动地会把它刚刚新建的项目展示给你），对于要输入的信息给出以下提示：

![$_`DQ$]_GCBALC9ZOKNTU8B.png](https://i.loli.net/2018/09/30/5bb0905a6e4b5.png)

Ⅰ 更新：对该问题进行更新，可以增加或修改属性。打开的界面给新建问题时类似，操作方法也类似。

Ⅱ 登记工时：登记问题可能的耗时，以便形成甘特图，时间进度表。

III 跟踪：选中此项则有跟踪权限的人员可以随时了解该问题的进展。

Ⅳ 副本：为该问题创建一个副本，也可以将它放在其他的栏目下面。

V 复制：将该问题复制，可以选择在原栏目下复制，也可以复制到其他栏目下面。

VI 删除：从栏目中删除该信息。

![@3Z$7D4NL`CDU3}SH]L]3EH.png](https://i.loli.net/2018/09/30/5bb091940d61a.png)

![1_E}DTZZ@6$)OF1[NXZ{0B6.png](https://i.loli.net/2018/09/30/5bb091941bb90.png)

点击确认后就可以得到：

![~95CQ37RP4Z$H_CS5KQ@Z5H.png](https://i.loli.net/2018/09/30/5bb091da05a80.png)


以上是我近期使用总结出来的用途，当然Bitnami-redmine还有很多的用途，我会在今后的工作生活中依依揭晓。
