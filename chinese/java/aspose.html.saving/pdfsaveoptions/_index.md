---
title: "PdfSaveOptions 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.saving.PdfSaveOptions 类。特定的数据类提供少量属性来管理转换结果。例如 PageSetup 指定页面特性。请参阅文档文章。"
type: docs

url: /zh/java/com.aspose.html.saving/pdfsaveoptions/
---
## PdfSaveOptions class

特定的数据类提供少量属性来管理转换结果。例如 [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) 指定页面特性。请参阅文档 [文章](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions)。

```java
public class PdfSaveOptions : PdfRenderingOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | 默认构造函数。 |

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

## 备注

您可以在 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 上找到完整的示例和数据文件。

## 示例

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
...
 	 // 准备源 HTML 文件的路径。
      String documentPath = Path.Combine(DataDir, "drawing.html");

      // 准备转换后文件的保存路径
      String savePath = Path.Combine(OutputDir, "drawing-options.pdf");

      // 从文件初始化 HTML 文档。
      using var document = new HTMLDocument(documentPath);

      // 初始化 PdfSaveOptions。设置页面尺寸为 600x300 像素，边距，
      // 分辨率并将背景颜色更改为 AliceBlue
      var options = new PdfSaveOptions()
      {         
        HorizontalResolution = 200,
        VerticalResolution = 200,
        BackgroundColor = Color.AliceBlue,
        JpegQuality = 100
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 300), new Margin(20, 10, 10, 10));      

      // 将 HTML 转换为 PDF
      Converter.ConvertHTML(document, options, savePath);
```

### 另请参见

* class [PdfRenderingOptions](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
