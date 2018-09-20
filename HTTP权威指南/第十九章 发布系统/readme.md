# 内容提要

* 本章讲解以HTTP 为基础的两种重要的Web 内容发布技术：FrontPage 和 Dev.

## FrontPage 为支持发布而座的服务器扩展

* FrontPage 的发布协议在 HTTP 的POST 请求之上实现了一个 RPC(Remote Procedure Cell,远程过程调用) 层。它允许FrontPage 客户端向服务器端发送命令更新网站上的文档，进行搜索以及在多个Web 作者之间进行协作。

## FrontPage 术语表
* 在深入研究 FPSE 定义的RPC 层之前，先了解一下其常用术语。

>> 虚拟服务器

>> 根 Web

>> 子 Web
## FrontPage 的RPC 协议

* FrontPage 客户端与FPSE 使用专门的 RPC 协议通信。该协议构建在 HTTP 的 POST 方法上，它把RPC 的方法及其相关变量嵌入在 POST请求的主题中。

## 略

















