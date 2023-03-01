---
title: Class OutputStream
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.IO.OutputStream 班级. 代理流包装实际输出流并控制对其的访问 OutputStream包含描述输出流位置的 URI 数据
type: docs
weight: 3750
url: /zh/net/aspose.html.io/outputstream/
---
## OutputStream class

代理流包装实际输出流并控制对其的访问。 `OutputStream`包含描述输出流位置的 URI 数据。

```csharp
public class OutputStream : Stream
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [OutputStream](outputstream/)(Stream, string) | 初始化一个新的实例`OutputStream`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [CanRead](../../aspose.html.io/outputstream/canread/) { get; } | 获取一个值，指示包装的输出流是否支持读取。 |
| override [CanSeek](../../aspose.html.io/outputstream/canseek/) { get; } | 获取一个值，指示包装的输出流是否支持查找。 |
| override [CanWrite](../../aspose.html.io/outputstream/canwrite/) { get; } | 获取一个值，指示包装的输出流是否支持写入。 |
| override [Length](../../aspose.html.io/outputstream/length/) { get; } | 获取包装输出流的字节长度。 |
| override [Position](../../aspose.html.io/outputstream/position/) { get; set; } | 获取或设置包装输出流中的位置。 |
| [Uri](../../aspose.html.io/outputstream/uri/) { get; } | 获取流位置的 URI。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Close](../../aspose.html.io/outputstream/close/)() | 关闭包装输出流和当前流。 |
| override [Flush](../../aspose.html.io/outputstream/flush/)() | 清除包装输出流的所有缓冲区，并使任何缓冲数据写入底层设备。 |
| override [Read](../../aspose.html.io/outputstream/read/)(byte[], int, int) | 从包装的输出 stream 中读取一个字节序列，并按读取的字节数推进流中的位置。 |
| override [Seek](../../aspose.html.io/outputstream/seek/)(long, SeekOrigin) | 设置包装输出流中的位置。 |
| override [SetLength](../../aspose.html.io/outputstream/setlength/)(long) | 设置包装输出流的长度。 |
| override [Write](../../aspose.html.io/outputstream/write/)(byte[], int, int) | 将字节序列写入包装的 output 流，并将该流中的当前位置前进写入的 字节数。 |

### 也可以看看

* 命名空间 [Aspose.Html.IO](../../aspose.html.io/)
* 部件 [Aspose.HTML](../../)


