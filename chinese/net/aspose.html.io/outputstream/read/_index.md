---
title: OutputStream.Read
second_title: Aspose.HTML for .NET API 参考
description: OutputStream 方法. 从包装的输出 stream 中读取一个字节序列并按读取的字节数推进流中的位置
type: docs
weight: 100
url: /zh/net/aspose.html.io/outputstream/read/
---
## OutputStream.Read method

从包装的输出 stream 中读取一个字节序列，并按读取的字节数推进流中的位置。

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| buffer | Byte[] | 字节数组。当此方法返回时，缓冲区包含指定的 字节数组，其中 offset 和 (offset + count - 1) 之间的值替换为 从包装输出流中读取的字节。 |
| offset | Int32 | 缓冲区中从零开始的字节偏移量，从该偏移量开始存储来自包装输出流的数据 read 。 |
| count | Int32 | 要从包装的输出流中读取的最大字节数。 |

### 返回值

读入缓冲区的总字节数。如果当前没有那么多字节可用，则这可能小于请求的字节数 ，或者如果已到达流的末尾，则为零 (0) 。

### 也可以看看

* class [OutputStream](../)
* 命名空间 [Aspose.Html.IO](../../outputstream/)
* 部件 [Aspose.HTML](../../../)


