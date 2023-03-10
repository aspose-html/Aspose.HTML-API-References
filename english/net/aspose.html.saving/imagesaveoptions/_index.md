---
title: ImageSaveOptions Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Saving.ImageSaveOptions class. Specific options data class. It provides properties to manage image result resolution smooting quality format as well as page settings and etc. More info you can obtain in documentation article
type: docs
weight: 4610
url: /net/aspose.html.saving/imagesaveoptions/
---
## ImageSaveOptions class

Specific options data class. It provides properties to manage image result resolution, smooting quality, format as well as page settings and etc. More info you can obtain in documentation [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#save-options).

```csharp
public class ImageSaveOptions : ImageRenderingOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/#constructor)() | Initializes a new instance of the `ImageSaveOptions` class; Png will be used as default image format. |
| [ImageSaveOptions](imagesaveoptions/#constructor_1)(ImageFormat) | Image format [`ImageFormat`](../../aspose.html.rendering.image/imageformat/) based on initialization |

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../aspose.html.rendering/renderingoptions/backgroundcolor/) { get; set; } | Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [Compression](../../aspose.html.rendering.image/imagerenderingoptions/compression/) { get; set; } | Sets or gets Tagged Image File Format (TIFF) [`Compression`](../../aspose.html.rendering.image/compression/). By default this property is LZW. |
| [Css](../../aspose.html.rendering/renderingoptions/css/) { get; } | Gets a [`CssOptions`](../../aspose.html.rendering/cssoptions/) object which is used for configuration of css properties processing. |
| [Format](../../aspose.html.rendering.image/imagerenderingoptions/format/) { get; set; } | Sets or gets [`ImageFormat`](../../aspose.html.rendering.image/imageformat/). By default this property is Png. |
| override [HorizontalResolution](../../aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Sets or gets horizontal resolution for output and internal (which are used during filters processing) images, in pixels per inch. By default this property is 300 dpi. |
| [PageSetup](../../aspose.html.rendering/renderingoptions/pagesetup/) { get; } | Gets a page setup object is used for configuration output page-set. |
| [SmoothingMode](../../aspose.html.rendering.image/imagerenderingoptions/smoothingmode/) { get; set; } | Gets or sets the rendering quality for this Graphics. |
| [Text](../../aspose.html.rendering.image/imagerenderingoptions/text/) { get; } | Gets a [`TextOptions`](../../aspose.html.rendering.image/textoptions/) object which is used for configuration of text rendering. |
| override [VerticalResolution](../../aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Sets or gets vertical resolution for output and internal (which are used during filters processing) images, in pixels per inch. By default this property is 300 dpi. |

## Remarks

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```csharp
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Drawing;
using Aspose.Html.Rendering.Image;
using Aspose.Html.Saving;
...
      // Prepare a path to a source HTML file
      string documentPath = Path.Combine(DataDir, "nature.html");

      // Prepare a path for converted file saving 
      string savePath = Path.Combine(OutputDir, "nature-output-options.png");

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

* class [ImageRenderingOptions](../../aspose.html.rendering.image/imagerenderingoptions/)
* namespace [Aspose.Html.Saving](../../aspose.html.saving/)
* assembly [Aspose.HTML](../../)
