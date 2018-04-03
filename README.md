本项目例子来自[Netty官方文档](http://netty.io/wiki/index.html)。

版本v4.1

## 基础通讯
1. [Echo](./fundamental-echo) ‐ 一个非常基本的 server & client，与官方例子有点不同：client将控制台的输入内容发送给server。
2. [Discard](./fundamental-discard) - client 会持续发消息到 server， server 会丢弃所有的消息。学习 ChannelFutureListener 的使用。