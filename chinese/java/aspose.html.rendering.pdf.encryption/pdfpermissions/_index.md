---
title: "PdfPermissions 枚举"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.rendering.pdf.encryption.PdfPermissions 枚举。此枚举表示 PDF 的用户权限。"
type: docs

url: /zh/java/com.aspose.html.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

此枚举表示用户对 PDF 的权限。

```java
[Flags]
public enum PdfPermissions
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| PrintDocument | `4` | (安全处理程序版本 2) 打印文档。(安全处理程序版本 3 或更高) 打印文档（可能不是最高质量水平，取决于是否也设置了 PrintingQuality）。 |
| ModifyContent | `8` | 通过除 ModifyTextAnnotations、FillForm 和 11 控制之外的操作修改文档内容。 |
| ExtractContent | `10` | (安全处理程序版本 2) 复制或以其他方式从文档中提取文本和图形，包括提取文本和图形（以支持残障用户的可访问性或出于其他目的）。(安全处理程序版本 3 或更高) 通过除 ExtractContentWithDisabilities 控制之外的操作复制或以其他方式从文档中提取文本和图形。 |
| ModifyTextAnnotations | `20` | 添加或修改文本注释，填写交互式表单字段，并且如果同时设置了 ModifyContent，则创建或修改交互式表单字段（包括签名字段）。 |
| FillForm | `100` | (安全处理程序版本 3 或更高) 填写现有的交互式表单字段（包括签名字段），即使 ModifyTextAnnotations 已清除。 |
| ExtractContentWithDisabilities | `200` | (安全处理程序版本 3 或更高) 提取文本和图形（以支持残障用户的可访问性或出于其他目的）。 |
| AssembleDocument | `400` | (安全处理程序版本 3 或更高) 组装文档（插入、旋转或删除页面并创建书签或缩略图），即使 ModifyContent 已清除。 |
| PrintingQuality | `800` | (安全处理程序版本 3 或更高) 将文档打印为一种可以生成 PDF 内容忠实数字副本的表示形式。当此位被清除（且第 3 位被设置）时，打印仅限于外观的低级表示，可能质量下降。 |

### 另请参阅

* package [com.aspose.html.rendering.pdf.encryption](../../com.aspose.html.rendering.pdf.encryption/)
* package [Aspose.HTML](../../)
