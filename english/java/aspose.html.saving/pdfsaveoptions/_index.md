---
title: PdfSaveOptions Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.saving.PdfSaveOptions class. Specific data class provides few properties to manage conversion result. For example PageSetup specifies page characteristics. Refer to documentation article
type: docs
weight: 4680
url: /java/com.aspose.html.saving/pdfsaveoptions/
---
## PdfSaveOptions class

Specific data class provides few properties to manage conversion result. For example [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) specifies page characteristics. Refer to documentation [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions).

```java
public class PdfSaveOptions : PdfRenderingOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Gets a [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) object which is used for configuration of css properties processing. |
| [getDocumentInfo](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/documentinfo/) Contains information about the output PDF document. |
[getEncryption]
[setEncryption] Gets or sets a encryption details. If not set, then no encryption will be performed. |
[getFormFieldBehaviour]
[setFormFieldBehaviour] Specifies the behavior of form fields in the output PDF document. |
[getHorizontalResolution]
[setHorizontalResolution] Sets or gets horizontal resolution for internal (which are used during filters processing) images, in pixels per inch. By default this property is 300 dpi. |
[getJpegQuality]
[setJpegQuality] Specifies the quality of JPEG compression for images (if JPEG compression is used). Default is 95. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Gets a page setup object is used for configuration output page-set. |
[getVerticalResolution]
[setVerticalResolution] Sets or gets vertical resolution for internal (which are used during filters processing) images, in pixels per inch. By default this property is 300 dpi. |

## Remarks

You can find complete examples and data files on [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import com.aspose.html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
...
 	 // Prepare a path to a source HTML file
      String documentPath = Path.Combine(DataDir, "drawing.html");

      // Prepare a path for converted file saving 
      String savePath = Path.Combine(OutputDir, "drawing-options.pdf");

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
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 300), new Margin(20, 10, 10, 10));      

      // Convert HTML to PDF
      Converter.ConvertHTML(document, options, savePath);
```

### See Also

* class [PdfRenderingOptions](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
