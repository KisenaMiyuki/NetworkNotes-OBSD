# Communication Model
提供了一种用于了解信息如何发送与接受的模型。
https://www.youtube.com/watch?v=OY1JsGFZprc

## Data communications
这个分类适用于 lower-layer communication aspects。
例如 signaling, device interfaces, and hardware related issues

## Computer communication
这个分类适用于 higher-layer aspects。
例如 network protocols, applications, and software related issues

## Model（Shannon-Weaver‘s）
**Information Source** - 信息源，生成信息/数据
↓
**Message** - 信息本身
↓
==Transmitter/Encoder== - 编码器，将信息/数据转换成信号
↓
*Channel* - 通道，传输媒介
（噪音会在这里混入）
↓
==Receiver/Decoder== - 解码器，将信号转换回信息/数据
↓
**Destination** - 目的地，消费信息/数据

## Noise
- [ ] 噪音到底是在哪里介入的？为什么增强信号也会增强噪音？

*Signal To Noise Ratio (SNR)*【信噪比】
单位：deciBel（dB）【分贝】

计算公式等：[Wikipedia](https://zh.wikipedia.org/wiki/%E4%BF%A1%E5%99%AA%E6%AF%94)