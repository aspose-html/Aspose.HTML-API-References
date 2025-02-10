---
title: ImageRenderingOptions Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.rendering.image.ImageRenderingOptions class. Represents rendering options for ImageDevice. This options is used to specify output image format compression resolution etc
type: docs
weight: 4550
url: /java/com.aspose.html.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

Represents rendering options for [`ImageDevice`](../imagedevice/). This options is used to specify output image format, compression, resolution etc.

```java
public class ImageRenderingOptions : RenderingOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | Initializes a new instance of the `ImageRenderingOptions` class; Png will be used as default image format. |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(ImageFormat) | Initializes a new instance of the `ImageRenderingOptions` class with specified image format. |

## Properties

| Name | Description |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Gets a [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) object which is used for configuration of css properties processing. |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Sets or gets horizontal resolution for output and internal (which are used during filters processing) images, in pixels per inch. By default this property is 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Gets a page setup object is used for configuration output page-set. |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) Gets a [`TextOptions`](../textoptions/) object which is used for configuration of text rendering. |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Sets or gets vertical resolution for output and internal (which are used during filters processing) images, in pixels per inch. By default this property is 300 dpi. |

### See Also

* class [RenderingOptions](../../com.aspose.html.rendering/renderingoptions/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)
