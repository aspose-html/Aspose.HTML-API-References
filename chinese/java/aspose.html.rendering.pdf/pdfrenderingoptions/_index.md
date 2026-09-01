---
title: "PdfRenderingOptions 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.rendering.pdf.PdfRenderingOptions 类。表示用于 PdfDevice 的渲染选项"
type: docs

url: /zh/java/com.aspose.html.rendering.pdf/pdfrenderingoptions/
---
## PdfRenderingOptions class

表示用于 [`PdfDevice`](../pdfdevice/) 的渲染选项。

```java
public class PdfRenderingOptions : RenderingOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfRenderingOptions](pdfrenderingoptions/)() | 初始化 `PdfRenderingOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) 获取一个用于配置 CSS 属性处理的 [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) 对象。 |
| [getDocumentInfo](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/documentinfo/) 包含关于输出 PDF 文档的信息。 |
[getEncryption]
[setEncryption] Gets or sets a encryption details. If not set, then no encryption will be performed. |
[getFormFieldBehaviour]
[setFormFieldBehaviour] Specifies the behavior of form fields in the output PDF document. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | 设置或获取内部（在过滤器处理期间使用）图像的水平分辨率，单位为每英寸像素。默认此属性为 300 dpi。 |
[getIsTaggedPdf]
[setIsTaggedPdf] Creates a tag structure if `true`. |
[getJpegQuality]
[setJpegQuality] Specifies the quality of JPEG compression for images (if JPEG compression is used). Default is 95. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) 获取用于配置输出页面设置的页面设置对象。 |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | 设置或获取内部（在过滤器处理期间使用）图像的垂直分辨率，单位为每英寸像素。默认此属性为 300 dpi。 |

### 另请参见

* class [RenderingOptions](../../com.aspose.html.rendering/renderingoptions/)
* package [com.aspose.html.rendering.pdf](../../com.aspose.html.rendering.pdf/)
* package [Aspose.HTML](../../)
