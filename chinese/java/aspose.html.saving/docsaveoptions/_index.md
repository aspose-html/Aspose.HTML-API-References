---
title: "DocSaveOptions 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.saving.DocSaveOptions 类。特定选项数据类。通过设置属性，您可以管理渲染特性，例如分辨率、页面大小、背景颜色，以及文档特定选项，如字体嵌入。更多信息请参阅文档文章。"
type: docs

url: /zh/java/com.aspose.html.saving/docsaveoptions/
---
## DocSaveOptions class

特定选项数据类。通过分配属性，您可以管理渲染特性，例如分辨率、页面大小、背景颜色，以及文档特定选项，例如字体嵌入。更多信息请参阅文档 [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#save-options)。

```java
public class DocSaveOptions : DocRenderingOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) 获取一个用于配置 CSS 属性处理的 [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) 对象。 |
[getDocumentFormat]
[setDocumentFormat] Gets or sets the file format of the output document. The default value is DOCX. |
[getFontEmbeddingRule]
[setFontEmbeddingRule] Gets or sets the font embedding rule. The default value is None. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | 设置或获取内部（在过滤器处理期间使用）图像的水平分辨率，单位为每英寸像素。默认此属性为 300 dpi。 |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) 获取用于配置输出页面设置的页面设置对象。 |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | 设置或获取内部（在过滤器处理期间使用）图像的垂直分辨率，单位为每英寸像素。默认此属性为 300 dpi。 |

## 备注

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.saving;
import System;
...
 // 准备源 HTML 文件的路径。
      String documentPath = Path.Combine(DataDir, "canvas.html");

      // 准备转换后文件的保存路径
      String savePath = Path.Combine(OutputDir, "canvas-output-options.docx");

      // 从文件初始化 HTML 文档。
      using var document = new HTMLDocument(documentPath);

      // 初始化 DocSaveOptions。设置页面尺寸为 600x400 像素以及边距。
      var options = new DocSaveOptions();
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 400), new Margin(10, 10, 10, 10));

      // 将 HTML 转换为 DOCX
      Converter.ConvertHTML(document, options, savePath);
```

*OutputDir - custom output folder path.

### 另请参见

* class [DocRenderingOptions](../../com.aspose.html.rendering.doc/docrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
