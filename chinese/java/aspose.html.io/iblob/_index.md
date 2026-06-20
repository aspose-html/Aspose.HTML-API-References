---
title: "IBlob 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.io.IBlob 接口。Blob 对象表示字节序列，具有 size 属性（字节序列的总字节数）和 type 属性（小写的 ASCII 编码 String，表示字节序列的媒体类型）。"
type: docs

url: /zh/java/com.aspose.html.io/iblob/
---
## IBlob interface

Blob 对象指代一个字节序列，并具有 size 属性，表示该字节序列的总字节数，以及 type 属性，这是一个小写的 ASCII 编码字符串，表示该字节序列的媒体类型。

```java
public interface IBlob
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getSize](../../com.aspose.html.io/iblob/size/) 返回字节序列的大小（字节数）。获取时，符合规范的用户代理必须返回可由 FileReader 或 FileReaderSync 对象读取的总字节数，如果 Blob 没有可读取的字节，则返回 0。 |
| [getType](../../com.aspose.html.io/iblob/type/) 表示 Blob 媒体类型的小写 ASCII 编码 String。获取时，用户代理必须返回 Blob 的类型，作为小写的 ASCII 编码 String，使其转换为字节序列后为可解析的 MIME 类型；如果无法确定类型，则返回空字符串（0 字节）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [slice](../../com.aspose.html.io/iblob/slice/)(ulong, ulong, String) | 返回一个新的 Blob 对象，其字节范围从可选的 start 参数开始，但不包括可选的 end 参数，并且其 type 属性的值为可选的 contentType 参数。 |

### 另请参见

* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)
