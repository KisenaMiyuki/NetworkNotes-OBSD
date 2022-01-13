---
aliases: [电子邮件]
---

# Email
**Email**（电子邮件），是最常用的一种[[Network Applications|网络应用]]。

Email 应用常被划分为两个部分：
- ==Email Interface application==，用于为用户提供撰写与阅读邮件的 GUI。
- ==Mail Transfer program==，实际上控制与邮件服务器的收发的程序。

## Transfer
Email 可以从一台电脑发送到另一台电脑，其使用 [[Simple Mail Transfer Protocol]]（SMTP）邮件传输协议。

![[Pasted image 20220113173409.png]]

## Access
可以通过本地邮件应用和网页应用查看邮件。查看邮件所使用的协议与传输时使用的不一样。

![[Pasted image 20220113175952.png]]

- ==本地邮件应用== 可以离线整个邮箱以便脱机工作，并在网络恢复时同步与更新。
- ==网页应用== 可以不受平台限制随时查看邮件，无需下载专用软件。

邮件查看协议只涉及客户端与**1**个邮箱，邮件传输协议涉及**2**个邮箱。
常用的邮件查看协议有：
- ==POP3==（Post Office Protocol ver.3）
- ==IMAP==（Internet Mail Access Protocol）

### POP

POP 的工作原理是联系您的电子邮件服务，然后从该服务下载所有新邮件。 将其下载到电脑或 Mac 后，会从电子邮件服务中删除它们。 这意味着，下载电子邮件后，只能使用同一台计算机 **访问它**。 如果尝试从其他设备访问电子邮件，则之前下载的邮件将不可用。

已发送邮件存储在电脑或 Mac 本地，而不是存储在电子邮件服务器上。

来源：[Microsoft](https://support.microsoft.com/zh-cn/office/imap-%E5%92%8C-pop-%E6%98%AF%E4%BB%80%E4%B9%88-ca2c5799-49f9-4079-aefe-ddca85d5b1c9)

### IMAP

IMAP 允许您从任何设备随时随地访问电子邮件。 当您使用 IMAP 阅读电子邮件时，您实际上不会在计算机上下载或存储它;而是从电子邮件服务读取。 因此，你可以从世界上任何地方的不同设备检查电子邮件：你的手机、计算机、朋友的计算机。
 
IMAP 仅在单击邮件时下载邮件，附件不会自动下载。 这样，您比 POP 能够更快速地检查邮件。

来源：[Microsoft](https://support.microsoft.com/zh-cn/office/imap-%E5%92%8C-pop-%E6%98%AF%E4%BB%80%E4%B9%88-ca2c5799-49f9-4079-aefe-ddca85d5b1c9)

IMAP较省带宽。

## Representation
邮件的显示标准有两个：
- [[Multipurpose Internet Mail Extensions|MIME]]
- RFC2822 Mail Message Format（text-only）
```ad-info
title: 需要进一步调查
```
### Extensible Representation：
- XML