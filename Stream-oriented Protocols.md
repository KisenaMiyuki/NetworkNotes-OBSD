---
aliases: [Stream Protocols, Stream Paradigm]
---

# Stream-oriented Protocols
**Stream-oriented Protocols**，或者流式传输协议/流式传输模式，是两种常见的网络传输模式之一。另一种是[[Message-oriented Protocols]]。使用流式传输协议的应用例如电话和在线视频。

流式传输意为数据以byte为单位像流水一般传输，并可持续任意时长。

| **Stream-oriented Protocols** |
| ----------------------------- |
| Connection-oriented           |
| 1-to-1 communication          |
| Sequence of bytes             |
| Arbitrary length transfer     |
| TCP                           |

值得注意的是，流式传输需要建立上行和下行的双向连接。为了建立这种连接，我们需要使用[[Client-Server Model]]。