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
- [x] [DNS Explained | YouTube](https://www.youtube.com/watch?v=72snZctFFtA)

DNS 服务器分为 Root DNS Server、Top-Level Domain (TLD) Servers、Authoritative DNS Server 以及（一般不算进层级里的）Local DNS Server。

Root DNS Server 全球有 13 台。

## DNS Autonomy
DNS 自治：每个组织都能够自由分配或修改域名，无需通知中央权力机关。

每个组织都被允许在层级内运行自己的 DNS 服务器。

## 名字解析
名字解析器的作用就是联系 DNS 服务器解析域名对应的 IP 地址。

每个解析器都记有一台或多台 Local DNS Server 的地址。

## DNS Caching
- [x] 什么是 DNS Caching？

## DNS Records
每个 DNS 项目的结构如下：

    (name, value, type)

name - 域名
value - 类似 IP 地址
type - 说明了 value 到底是什么

一些 type：
- ==A==：直接对应的 IP 地址
- ==MX==：Mail eXchanger
- [x] 什么是 Mail eXchanger？
- ==NS==：转发请求到另一台 DNS 服务器上
- ==CNAME==：把域名重定向到另一台电脑上，便于更换服务器电脑以及在同一台电脑上架设多个服务器（例如 FTP 和邮件）

## DNS 字符库
由于 DNS 使用了 ASCII 字符库，所以很多国际字符无法被表示。
因此 [IETF (互联网工程任务组)](https://zh.wikipedia.org/wiki/%E4%BA%92%E8%81%94%E7%BD%91%E5%B7%A5%E7%A8%8B%E4%BB%BB%E5%8A%A1%E7%BB%84) 使用 Unicode 将这些字符转译成 ASCII 字符。（[IDNA (国际化域名)](https://zh.wikipedia.org/wiki/%E5%9B%BD%E9%99%85%E5%8C%96%E5%9F%9F%E5%90%8D)）
