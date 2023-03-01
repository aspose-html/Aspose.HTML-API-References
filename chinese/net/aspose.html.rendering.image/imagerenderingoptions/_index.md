---
title: Class ImageRenderingOptions
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Rendering.Image.ImageRenderingOptions 班级. 代表渲染选项ImageDevice.此选项用于指定输出图像格式压缩分辨率等
type: docs
weight: 4330
url: /zh/net/aspose.html.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

代表渲染选项[`ImageDevice`](../imagedevice/).此选项用于指定输出图像格式、压缩、分辨率等。

```csharp
public class ImageRenderingOptions : RenderingOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | 初始化一个新的实例`ImageRenderingOptions`班级;Png将用作默认图像格式。 |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(ImageFormat) | 初始化一个新的实例`ImageRenderingOptions`具有指定图像格式的类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BackgroundColor](../../aspose.html.rendering/renderingoptions/backgroundcolor/) { get; set; } | 获取或设置Color这将填充每一页的背景。默认值为Transparent. |
| [Compression](../../aspose.html.rendering.image/imagerenderingoptions/compression/) { get; set; } | 设置或获取标记图像文件格式 (TIFF)[`Compression`](../compression/).默认情况下，此属性是LZW. |
| [Css](../../aspose.html.rendering/renderingoptions/css/) { get; } | 得到一个[`CssOptions`](../../aspose.html.rendering/cssoptions/)用于配置 css 属性处理的对象。 |
| [Format](../../aspose.html.rendering.image/imagerenderingoptions/format/) { get; set; } | 设置或获取[`ImageFormat`](../imageformat/).默认情况下，此属性是Png. |
| override [HorizontalResolution](../../aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | 设置或获取输出和内部（在过滤器处理期间使用）图像的水平分辨率，以像素/英寸为单位。默认情况下，此属性为 300 dpi. |
| [PageSetup](../../aspose.html.rendering/renderingoptions/pagesetup/) { get; } | 获取页面设置对象用于配置输出页面设置。 |
| [SmoothingMode](../../aspose.html.rendering.image/imagerenderingoptions/smoothingmode/) { get; set; } | 获取或设置此 Graphics 的渲染质量。 |
| [Text](../../aspose.html.rendering.image/imagerenderingoptions/text/) { get; } | 得到一个[`TextOptions`](../textoptions/)用于文本渲染配置的对象. |
| override [VerticalResolution](../../aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | 设置或获取输出和内部（在过滤器处理期间使用）图像的垂直分辨率，以像素/英寸为单位。默认情况下，此属性为 300 dpi. |

### 也可以看看

* class [RenderingOptions](../../aspose.html.rendering/renderingoptions/)
* 命名空间 [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image/)
* 部件 [Aspose.HTML](../../)


