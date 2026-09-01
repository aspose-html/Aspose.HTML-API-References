---
title: "XpsSaveOptions 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.saving.XpsSaveOptions 类。特定选项数据类提供少量属性以管理转换结果。例如，PageSetup 指定页面特性。请参阅文档文章。"
type: docs

url: /zh/java/com.aspose.html.saving/xpssaveoptions/
---
## XpsSaveOptions class

特定选项数据类提供少量属性以管理转换结果。例如 [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) 指定页面特性。请参阅文档 [文章](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#save-options)。

```java
public class XpsSaveOptions : XpsRenderingOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) 获取一个用于配置 CSS 属性处理的 [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) 对象。 |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | 设置或获取内部（在过滤器处理期间使用）图像的水平分辨率，单位为每英寸像素。默认此属性为 300 dpi。 |
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
	  String documentPath = Path.Combine(OutputDir, "save-options.html");
      String savePath = Path.Combine(OutputDir, "save-options-output.xps");

      // 准备 HTML 代码并将其保存到文件。
      var code = "<h1> XpsSaveOptions Class</h1>\r\n" +
            "<p>Using XpsSaveOptions Class, you can programmatically apply a wide range of conversion parameters such as BackgroundColor, PageSetup, etc.</p>\r\n";

      File.WriteAllText(documentPath, code);

      // 从 html 文件初始化 HTML 文档。
      using var document = new HTMLDocument(documentPath);
       
      // 设置页面尺寸、边距并将背景颜色更改为 AntiqueWhite。
      var options = new XpsSaveOptions()
      {
        BackgroundColor = Color.AntiqueWhite
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(Length.FromInches(4.9f), Length.FromInches(3.5f)), new Margin(30, 20, 10, 10));

      // 将 HTML 转换为 XPS
      Converter.ConvertHTML(document, options, savePath); 
```

### 另请参见

* class [XpsRenderingOptions](../../com.aspose.html.rendering.xps/xpsrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
