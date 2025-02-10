---
title: ImageSaveOptions Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.saving.ImageSaveOptions class. Specific options data class. It provides properties to manage image result resolution smooting quality format as well as page settings and etc. More info you can obtain in documentation article
type: docs
weight: 4830
url: /java/com.aspose.html.saving/imagesaveoptions/
---
## ImageSaveOptions class

Specific options data class. It provides properties to manage image result resolution, smooting quality, format as well as page settings and etc. More info you can obtain in documentation [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#save-options).

```java
public class ImageSaveOptions : ImageRenderingOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/#constructor)() | Initializes a new instance of the `ImageSaveOptions` class; Png will be used as default image format. |
| [ImageSaveOptions](imagesaveoptions/#constructor_1)(ImageFormat) | Image format [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/) based on initialization |

## Properties

| Name | Description |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../../com.aspose.html.rendering.image/compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Gets a [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) object which is used for configuration of css properties processing. |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Sets or gets horizontal resolution for output and internal (which are used during filters processing) images, in pixels per inch. By default this property is 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Gets a page setup object is used for configuration output page-set. |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) Gets a [`TextOptions`](../../com.aspose.html.rendering.image/textoptions/) object which is used for configuration of text rendering. |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Sets or gets vertical resolution for output and internal (which are used during filters processing) images, in pixels per inch. By default this property is 300 dpi. |

## Remarks

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
      // Prepare a path to a source HTML file
      String documentPath = Path.Combine(DataDir, "nature.html");

      // Prepare a path for converted file saving 
      String savePath = Path.Combine(OutputDir, "nature-output-options.png");

      // Initialize an HTML document from the file
      using var document = new HTMLDocument(documentPath);

      // Initialize ImageSaveOptions       
      var options = new ImageSaveOptions()
      {
        SmoothingMode = SmoothingMode.Default,
        HorizontalResolution = 100,
        VerticalResolution = 100,
        BackgroundColor = Color.Beige
      };

      // Convert HTML to PNG
      Converter.ConvertHTML(document, options, savePath);
```

### See Also

* class [ImageRenderingOptions](../../com.aspose.html.rendering.image/imagerenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
