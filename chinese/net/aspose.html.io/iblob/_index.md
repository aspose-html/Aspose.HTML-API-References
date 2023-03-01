---
title: Interface IBlob
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.IO.IBlob 界面. Blob对象指的是一个字节序列有一个size属性是字节序列中的字节总数type属性是一个ASCII编码的小写字符串表示字节序列的媒体类型.
type: docs
weight: 3700
url: /zh/net/aspose.html.io/iblob/
---
## IBlob interface

Blob对象指的是一个字节序列，有一个size属性是字节序列中的字节总数，type属性是一个ASCII编码的小写字符串，表示字节序列的媒体类型.

```csharp
public interface IBlob
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Size](../../aspose.html.io/iblob/size/) { get; } | 以字节数返回字节序列的大小。 在获取时，符合要求的用户代理必须返回 FileReader 或 FileReaderSync 对象可以读取的字节总数，如果 Blob 没有要读取的字节，则返回 0 . |
| [Type](../../aspose.html.io/iblob/type/) { get; } | 表示 Blob 媒体类型的小写 ASCII 编码字符串。 获取时，用户代理必须返回 Blob 的类型作为小写 ASCII 编码字符串， 这样当它被转换为字节时序列，它是一个可解析的 MIME 类型， 或空字符串 - 0 字节 - 如果无法确定类型。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Slice](../../aspose.html.io/iblob/slice/)(ulong, ulong, string) | 返回一个新的 Blob 对象，其字节范围从可选的开始参数到但不包括可选的结束参数 ，并且类型属性是可选的 contentType 参数的值。 |

### 也可以看看

* 命名空间 [Aspose.Html.IO](../../aspose.html.io/)
* 部件 [Aspose.HTML](../../)


