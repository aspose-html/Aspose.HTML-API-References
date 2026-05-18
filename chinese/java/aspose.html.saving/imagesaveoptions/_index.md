---
title: "ImageSaveOptions 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.saving.ImageSaveOptions 类。特定的选项数据类。它提供属性以管理图像结果的分辨率、平滑、质量、格式以及页面设置等。更多信息可在文档文章中获取。"
type: docs

url: /zh/java/com.aspose.html.saving/imagesaveoptions/
---
## ImageSaveOptions class

特定选项数据类。它提供属性以管理图像结果分辨率、平滑质量、格式以及页面设置等。更多信息请参阅文档 [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#save-options)。

```java
public class ImageSaveOptions : ImageRenderingOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/#constructor)() | 初始化 `ImageSaveOptions` 类的新实例；默认使用 Png 作为图像格式。 |
| [ImageSaveOptions](imagesaveoptions/#constructor_1)(ImageFormat) | 基于初始化的图像格式 [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/) |

## 属性

| 名称 | 描述 |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../../com.aspose.html.rendering.image/compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) 获取一个用于配置 CSS 属性处理的 [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) 对象。 |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | 设置或获取输出和内部（用于过滤器处理期间）图像的水平分辨率，单位为每英寸像素。默认情况下此属性为 300 dpi。 |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) 获取用于配置输出页面设置的页面设置对象。 |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) 获取一个用于文本渲染配置的 [`TextOptions`](../../com.aspose.html.rendering.image/textoptions/) 对象。 |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | 设置或获取输出和内部（用于过滤器处理期间）图像的垂直分辨率，单位为每英寸像素。默认情况下此属性为 300 dpi。 |

## 备注

您可以从 [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) 下载完整的示例和数据文件。

## 示例

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
      // Prepare a path to a source HTML file
      String documentPath = Path.Combine(DataDir, "nature.html");

      // 为转换后的文件保存准备路径
      String savePath = Path.Combine(OutputDir, "nature-output-options.png");

      // Initialize an HTML document from the file
      using var document = new HTMLDocument(documentPath);

      // 初始化 ImageSaveOptions       
      var options = new ImageSaveOptions()
      {
        SmoothingMode = SmoothingMode.Default,
        HorizontalResolution = 100,
        VerticalResolution = 100,
        BackgroundColor = Color.Beige
      };

      // 将 HTML 转换为 PNG
      Converter.ConvertHTML(document, options, savePath);
```

### 另请参阅

* class [ImageRenderingOptions](../../com.aspose.html.rendering.image/imagerenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
