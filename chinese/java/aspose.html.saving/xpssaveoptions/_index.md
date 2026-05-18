---
title: "XpsSaveOptions Class"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.saving.XpsSaveOptions class. Specific options data class provides few properties to manage conversion result. For example PageSetup specifies page characteristics. Refer to documentation article"
type: docs

url: /zh/java/com.aspose.html.saving/xpssaveoptions/
---
## XpsSaveOptions class

Specific options data class provides few properties to manage conversion result. For example [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) specifies page characteristics. Refer to documentation [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#save-options).

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

      // Prepare HTML code and save it to a file
      var code = "<h1> XpsSaveOptions Class</h1>\r\n" +
            "<p>Using XpsSaveOptions Class, you can programmatically apply a wide range of conversion parameters such as BackgroundColor, PageSetup, etc.</p>\r\n";

      File.WriteAllText(documentPath, code);

      // Initialize an HTML Document from the html file
      using var document = new HTMLDocument(documentPath);
       
      // Set up the page-size, margins and change the background color to AntiqueWhite
      var options = new XpsSaveOptions()
      {
        BackgroundColor = Color.AntiqueWhite
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(Length.FromInches(4.9f), Length.FromInches(3.5f)), new Margin(30, 20, 10, 10));

      // 将 HTML 转换为 XPS
      Converter.ConvertHTML(document, options, savePath); 
```

### 另请参阅

* class [XpsRenderingOptions](../../com.aspose.html.rendering.xps/xpsrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
