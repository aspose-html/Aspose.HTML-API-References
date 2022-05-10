---
title: PdfSaveOptions
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 4720
url: /net/aspose.html.saving/pdfsaveoptions/
---
## PdfSaveOptions class

Specific data class provides few properties to manage conversion result. For example [`PageSetup`](../../aspose.html.rendering/pagesetup) specifies page characteristics. Refer to documentation [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions).

```csharp
public class PdfSaveOptions : PdfRenderingOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions)() | The default constructor. |

### Remarks

You can find complete examples and data files on [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

### Examples

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

* class [PdfRenderingOptions](../../aspose.html.rendering.pdf/pdfrenderingoptions)
* namespace [Aspose.Html.Saving](../../aspose.html.saving)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->