---
title: PdfSaveOptions Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Saving.PdfSaveOptions class. Specific data class provides few properties to manage conversion result. For example PageSetup specifies page characteristics. Refer to documentation article
type: docs
weight: 4660
url: /net/aspose.html.saving/pdfsaveoptions/
---
## PdfSaveOptions class

Specific data class provides few properties to manage conversion result. For example [`PageSetup`](../../aspose.html.rendering/pagesetup/) specifies page characteristics. Refer to documentation [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions).

```csharp
public class PdfSaveOptions : PdfRenderingOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../aspose.html.rendering/renderingoptions/backgroundcolor/) { get; set; } | Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [Css](../../aspose.html.rendering/renderingoptions/css/) { get; } | Gets a [`CssOptions`](../../aspose.html.rendering/cssoptions/) object which is used for configuration of css properties processing. |
| [DocumentInfo](../../aspose.html.rendering.pdf/pdfrenderingoptions/documentinfo/) { get; } | Contains information about the output PDF document. |
| [Encryption](../../aspose.html.rendering.pdf/pdfrenderingoptions/encryption/) { get; set; } | Gets or sets a encryption details. If not set, then no encryption will be performed. |
| [FormFieldBehaviour](../../aspose.html.rendering.pdf/pdfrenderingoptions/formfieldbehaviour/) { get; set; } | Specifies the behavior of form fields in the output PDF document. |
| virtual [HorizontalResolution](../../aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Sets or gets horizontal resolution for internal (which are used during filters processing) images, in pixels per inch. By default this property is 300 dpi. |
| [JpegQuality](../../aspose.html.rendering.pdf/pdfrenderingoptions/jpegquality/) { get; set; } | Specifies the quality of JPEG compression for images (if JPEG compression is used). Default is 95. |
| [PageSetup](../../aspose.html.rendering/renderingoptions/pagesetup/) { get; } | Gets a page setup object is used for configuration output page-set. |
| virtual [VerticalResolution](../../aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Sets or gets vertical resolution for internal (which are used during filters processing) images, in pixels per inch. By default this property is 300 dpi. |

## Remarks

You can find complete examples and data files on [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```csharp
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;
using System;
...
 	 // Prepare a path to a source HTML file
      string documentPath = Path.Combine(DataDir, "drawing.html");

      // Prepare a path for converted file saving 
      string savePath = Path.Combine(OutputDir, "drawing-options.pdf");

      // Initialize an HTML document from the file
      using var document = new HTMLDocument(documentPath);

      // Initialize PdfSaveOptions. Set up the page-size 600x300 pixels, margins, 
      // resolutions and change the background color to AliceBlue 
      var options = new PdfSaveOptions()
      {         
        HorizontalResolution = 200,
        VerticalResolution = 200,
        BackgroundColor = Color.AliceBlue,
        JpegQuality = 100
      };
      options.PageSetup.AnyPage = new Page(new Aspose.Html.Drawing.Size(600, 300), new Margin(20, 10, 10, 10));      

      // Convert HTML to PDF
      Converter.ConvertHTML(document, options, savePath);
```

### See Also

* class [PdfRenderingOptions](../../aspose.html.rendering.pdf/pdfrenderingoptions/)
* namespace [Aspose.Html.Saving](../../aspose.html.saving/)
* assembly [Aspose.HTML](../../)
