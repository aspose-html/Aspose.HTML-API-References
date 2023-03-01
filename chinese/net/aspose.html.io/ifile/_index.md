---
title: Interface IFile
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.IO.IFile 界面. File对象是一个Blob对象name属性是一个字符串它可以通过构造函数在 Web 应用程序中创建或者是对来自底层 OS 文件系统的文件的字节序列的引用
type: docs
weight: 3720
url: /zh/net/aspose.html.io/ifile/
---
## IFile interface

File对象是一个Blob对象，name属性是一个字符串；它可以通过构造函数在 Web 应用程序中创建，或者是对来自底层 (OS) 文件系统的文件的字节序列的引用。

```csharp
public interface IFile : IBlob
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [LastModified](../../aspose.html.io/ifile/lastmodified/) { get; } | 文件的最后修改日期。在获取时，如果用户代理可以提供此信息， 这必须返回一个 long long 设置为文件最后一次修改的时间，作为自 Unix 纪元以来的毫秒数。 |
| [Name](../../aspose.html.io/ifile/name/) { get; } | 文件名。 获取时，必须以字符串形式返回文件名。 |

### 也可以看看

* interface [IBlob](../iblob/)
* 命名空间 [Aspose.Html.IO](../../aspose.html.io/)
* 部件 [Aspose.HTML](../../)


