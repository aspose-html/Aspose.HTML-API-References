---
title: ImageRenderingOptions Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Rendering.Image.ImageRenderingOptions class. Represents rendering options for ImageDevice. This options is used to specify output image format compression resolution etc
type: docs
weight: 4550
url: /net/aspose.html.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

Represents rendering options for [`ImageDevice`](../imagedevice/). This options is used to specify output image format, compression, resolution etc.

```csharp
public class ImageRenderingOptions : RenderingOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | Initializes a new instance of the `ImageRenderingOptions` class; Png will be used as default image format. |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(*[ImageFormat](../imageformat/)*) | Initializes a new instance of the `ImageRenderingOptions` class with specified image format. |

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../aspose.html.rendering/renderingoptions/backgroundcolor/) { get; set; } | Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [Compression](../../aspose.html.rendering.image/imagerenderingoptions/compression/) { get; set; } | Sets or gets Tagged Image File Format (TIFF) [`Compression`](../compression/). By default this property is LZW. |
| [Css](../../aspose.html.rendering/renderingoptions/css/) { get; } | Gets a [`CssOptions`](../../aspose.html.rendering/cssoptions/) object which is used for configuration of css properties processing. |
| [Format](../../aspose.html.rendering.image/imagerenderingoptions/format/) { get; set; } | Sets or gets [`ImageFormat`](../imageformat/). By default this property is Png. |
| override [HorizontalResolution](../../aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Sets or gets horizontal resolution for output and internal (which are used during filters processing) images, in pixels per inch. By default this property is 300 dpi. |
| [PageSetup](../../aspose.html.rendering/renderingoptions/pagesetup/) { get; } | Gets a page setup object is used for configuration output page-set. |
| [Text](../../aspose.html.rendering.image/imagerenderingoptions/text/) { get; } | Gets a [`TextOptions`](../textoptions/) object which is used for configuration of text rendering. |
| [UseAntialiasing](../../aspose.html.rendering.image/imagerenderingoptions/useantialiasing/) { get; set; } | Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| override [VerticalResolution](../../aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Sets or gets vertical resolution for output and internal (which are used during filters processing) images, in pixels per inch. By default this property is 300 dpi. |

### See Also

* class [RenderingOptions](../../aspose.html.rendering/renderingoptions/)
* namespace [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image/)
* assembly [Aspose.HTML](../../)
