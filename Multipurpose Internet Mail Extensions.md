---
aliases: [MIME, 多用途互联网邮件扩展]
---

# **M**ultipurpose **I**nternet **M**ail **E**xtensions
**Multipurpose Internet Mail Extensions**（MIME，多用途互联网邮件扩展），扩展了[[Email|电子邮件]]的功能，使得非文本内容可以被显示和发送。

## 编码
MIME 将 binary file 编码成可打印字符，并由收件人解码。

MIME 允许用户自由选择编码。一般来说，Base64 是使用最多的。
- 发件人在 header 里新增一行用于指定用到的编码
- 发件人可以附上多个附件，并单独指定编码

## 兼容性
MIME 向下兼容，因此 MIME 邮件在不支持它的客户端上依然能够显示，只是无法查看非文本内容。
