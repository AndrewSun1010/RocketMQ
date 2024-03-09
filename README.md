# RocketMQ学习笔记

## 官方QuickStart

网址：

[apache/rocketmq: Apache RocketMQ is a cloud native messaging and streaming platform, making it simple to build event-driven applications. (github.com)](https://github.com/apache/rocketmq)

**运行nameserver和broker**

注：运行broker时采用wsl的ubuntu内存不够，需在runbroker.sh和runserver.sh文件中更改默认JVM大小

见黑马程序员RocketMQ-01.md文档

## 采用双主双从搭建broker集群

由于采用wsl很难采取两个不同ip的ubuntu服务器，故改用vaware

[给 WSL2 设置静态 IP 地址 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/380779630#:~:text=Name -Eq WSLNat | Remove-NetNat -Confirm%3A%24False New-NetNat -Name,(WSL) 这个网络适配器，然后将其所有已有的 IP 地址删除，然后为其添加 192.168.50.1%2F24 的 IP 地址)
