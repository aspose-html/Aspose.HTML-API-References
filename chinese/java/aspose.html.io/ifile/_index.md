---
title: "IFile 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.io.IFile 接口。File 对象是具有 name 属性（该属性为 String 类型）的 Blob 对象，可通过构造函数在 Web 应用中创建，或引用底层操作系统文件系统中的文件的字节序列。"
type: docs

url: /zh/java/com.aspose.html.io/ifile/
---
## IFile interface

File 对象是具有 name 属性（字符串）的 Blob 对象；它可以通过构造函数在 Web 应用中创建，或是对底层（操作系统）文件系统中文件的字节序列的引用。

```java
public interface IFile : IBlob
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getLastModified](../../com.aspose.html.io/ifile/lastmodified/) 文件的最后修改日期。获取时，如果用户代理能够提供此信息，则必须返回一个 long long，表示自 Unix 纪元以来的毫秒数，即文件最后一次修改的时间。 |
| [getName](../../com.aspose.html.io/ifile/name/) 文件的名称。获取时，必须返回文件的名称，类型为 String。 |

### 另请参见

* interface [IBlob](../iblob/)
* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)
