---
title: Enum PdfPermissions
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Rendering.Pdf.Encryption.PdfPermissions 枚举. 此枚举表示用户对 pdf 的权限
type: docs
weight: 4420
url: /zh/net/aspose.html.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

此枚举表示用户对 pdf 的权限。

```csharp
[Flags]
public enum PdfPermissions
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| PrintDocument | `4` | （修订版 2 的安全处理程序）打印文档。 （修订版 3 或更高版本的安全处理程序）打印文档（可能不是最高质量级别，取决于是否还设置了 PrintingQuality）。 |
| ModifyContent | `8` | 通过 ModifyTextAnnotations、FillForm 和 11. 控制的操作以外的操作修改文档的内容 |
| ExtractContent | `10` | 修订版 2 的安全处理程序）复制或以其他方式从文档中提取文本和图形， 包括提取文本和图形（以支持残障用户的可访问性或用于其他目的）。 （修订版 3 或更高版本的安全处理程序）复制或者通过 ExtractContentWithDisabilities. 控制的操作以外的操作从文档中提取文本和图形 |
| ModifyTextAnnotations | `20` | 添加或修改文本注释，填写交互式表单域，如果还设置了 ModifyContent，则创建或修改交互式表单域（包括签名域）。 |
| FillForm | `100` | （修订版 3 或更高版本的安全处理程序）填写现有的交互式表单字段（包括签名字段），即使 ModifyTextAnnotations 已清除。 |
| ExtractContentWithDisabilities | `200` | （修订版 3 或更高版本的安全处理程序）提取文本和图形（以支持残障用户的可访问性或用于其他目的）。 |
| AssembleDocument | `400` | （修订版 3 或更高版本的安全处理程序）组合文档（插入、旋转或删除页面并创建书签或缩略图图像），即使 ModifyContent 是明确的。 |
| PrintingQuality | `800` | （修订版 3 或更高版本的安全处理程序）将文档打印为可以生成 PDF 内容的忠实数字副本的表示形式。 当该位清零（并且设置位 3）时，打印限制为低- 外观的级别表示，可能质量下降。 |

### 也可以看看

* 命名空间 [Aspose.Html.Rendering.Pdf.Encryption](../../aspose.html.rendering.pdf.encryption/)
* 部件 [Aspose.HTML](../../)


