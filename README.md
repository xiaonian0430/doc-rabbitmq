# RabbitMQ

## 简介
RabbitMQ是实现了高级消息队列协议（AMQP）的开源消息代理软件（亦称面向消息的中间件）。RabbitMQ服务器是用Erlang语言编写的，而集群和故障转移是构建在开放电信平台框架上的。所有主要的编程语言均有与代理接口通讯的客户端库

**RabbitMQ服务支持下列操作系统：**

- Linux
- WindowsNT 到 10
- Windows Server2003 到 2016
- macOS
- Solaris
- FreeBSD
- TRU64
- VxWorks

**RabbitMQ支持下列编程语言：**

- Python
- Java
- Ruby
- PHP
- C#
- JavaScript
- Go
- Elixir
- Objective-C
- Swift

## 主要特性
可伸缩性：集群服务
消息持久化：从内存持久化消息到硬盘，再从硬盘加载到内存

## 安装
Erlang与RabbitMQ，安装路径都应不含空格符。

Erlang使用了环境变量HOMEDRIVE与HOMEPATH来访问配置文件.erlang.cookie，应注意这两个环境变量的有效性。需要设定环境变量ERLANG_HOME，并把%ERLANG_HOME%\bin加入到全局路径中。

RabbitMQ使用本地computer name作为服务器的地址，因此需要注意其有效性，或者直接解析为127.0.0.1

可能需要在本地网络防火墙打开相应的端口。
