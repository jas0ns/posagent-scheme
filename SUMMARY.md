POS agent (port oriented socket agent)
=========

针对指定端口的包转发代理服务程序

功能
----
实现类似如下场景：
*  例一：winodws端，War3游戏程序，监听其6112（客户端参数指定）端口，将该端口udp包转发至服务器，
   服务器程序对收到的包进行处理并转发给所有在线的其他客户端，实现简单的war3公网游戏平台。
*  例二：linux端，SMTP邮件服务协议，监听23端口，将其tcp包转发至服务器，
   服务器程序对收到的包存储转发给指定的其他客户端，实现简单邮件服务器或者简单邮件列表。

实现
----
###1）语言
  服务端使用C语言实现，客户端自由选择（选定后需告知）。
###2) 服务器功能模块
  TODO
###3) 客户端功能模块
  TODO
###4）通信接口
  TODO
###5） 其他
  TODO
  
环境
----
*  服务端：linux
*  客户端：linux、windows、……
*  公网测试环境：阿里云ecs

  ![](https://github.com/jas0ns/posagent-scheme/new/master/images/ecs.jpg)


