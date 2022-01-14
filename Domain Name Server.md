---
aliases: [DNS, 域名服务器]
---

# Domain Name Server
**域名系统**（英语：**D**omain **N**ame **S**ystem，缩写：**DNS**）是互联网的一项服务。它作为将域名和 IP 地址相互映射的一个分布式数据库，能够使人更方便地访问互联网。DNS 使用 TCP 和 UDP 端口 53。当前，对于每一级域名长度的限制是 63 个字符，域名总长度则不能超过 253 个字符。 [[Wikipedia](https://zh.wikipedia.org/wiki/%E5%9F%9F%E5%90%8D%E7%B3%BB%E7%BB%9F) ]

DNS 也使用了[[Client-Server Model]]。

## 分布式
为了缓解访问压力、提高效率、避免「鸡蛋放一个篮子里」问题以及方便维护，DNS 服务器被做成分布式的。

## 域名语法
![](https://www.weboftwo.com/wp-content/uploads/2018/04/structure-of-domain-name-weboftwo.png)

Top Level Domain：例如 .com .edu .gov .net .org

## DNS 服务器的层级
- [ ] [DNS Explained | YouTube](https://www.youtube.com/watch?v=72snZctFFtA)

DNS 服务器分为 Root DNS Server、Top-Level Domain (TLD) Servers、Authoritative DNS Server 以及（一般不算进层级里的）Local DNS Server。

Root DNS Server 全球有 13 台。
