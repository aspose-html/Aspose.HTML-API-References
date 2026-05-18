---
title: "ImageRenderingOptions 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.rendering.image.ImageRenderingOptions 类。表示 ImageDevice 的渲染选项。此选项用于指定输出图像格式、压缩、分辨率等"
type: docs

url: /zh/java/com.aspose.html.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

表示 [`ImageDevice`](../imagedevice/) 的渲染选项。此选项用于指定输出图像格式、压缩、分辨率等。

```java
public class ImageRenderingOptions : RenderingOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | 初始化 `ImageRenderingOptions` 类的新实例；默认使用 PNG 作为图像格式。 |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(ImageFormat) | 使用指定的图像格式初始化 `ImageRenderingOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) 获取一个用于配置 CSS 属性处理的 [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) 对象。 |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | 设置或获取输出和内部（用于过滤器处理期间）图像的水平分辨率，单位为每英寸像素。默认情况下此属性为 300 dpi。 |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) 获取用于配置输出页面设置的页面设置对象。 |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) 获取用于配置文本渲染的 [`TextOptions`](../textoptions/) 对象。 |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | 设置或获取输出和内部（用于过滤器处理期间）图像的垂直分辨率，单位为每英寸像素。默认情况下此属性为 300 dpi。 |

### 另请参阅

* class [RenderingOptions](../../com.aspose.html.rendering/renderingoptions/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)
