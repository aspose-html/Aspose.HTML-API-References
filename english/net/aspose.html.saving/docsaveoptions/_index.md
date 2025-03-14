---
title: DocSaveOptions Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Saving.DocSaveOptions class. Specific options data class. By assigning properties you can manage rendering characteristics such as resolution page size background color as well as doc specific options such as font embedding. More info see in documentation article
type: docs
weight: 4800
url: /net/aspose.html.saving/docsaveoptions/
---
## DocSaveOptions class

Specific options data class. By assigning properties you can manage rendering characteristics such as resolution, page size, background color as well as doc specific options such as font embedding. More info see in documentation [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#save-options).

```csharp
public class DocSaveOptions : DocRenderingOptions
```

## Public Members
## Constructors

| Name | Description |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | The default constructor. |

## Public Members
## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../aspose.html.rendering/renderingoptions/backgroundcolor/) { get; set; } | Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [Css](../../aspose.html.rendering/renderingoptions/css/) { get; } | Gets a [`CssOptions`](../../aspose.html.rendering/cssoptions/) object which is used for configuration of css properties processing. |
| [DocumentFormat](../../aspose.html.rendering.doc/docrenderingoptions/documentformat/) { get; set; } | Gets or sets the file format of the output document. The default value is DOCX. |
| [FontEmbeddingRule](../../aspose.html.rendering.doc/docrenderingoptions/fontembeddingrule/) { get; set; } | Gets or sets the font embedding rule. The default value is None. |
| virtual [HorizontalResolution](../../aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Sets or gets horizontal resolution for internal (which are used during filters processing) images, in pixels per inch. By default this property is 300 dpi. |
| [PageSetup](../../aspose.html.rendering/renderingoptions/pagesetup/) { get; } | Gets a page setup object is used for configuration output page-set. |
| virtual [VerticalResolution](../../aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Sets or gets vertical resolution for internal (which are used during filters processing) images, in pixels per inch. By default this property is 300 dpi. |

## Remarks

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```csharp
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Drawing;
using Aspose.Html.Saving;
using System;
...
 // Prepare a path to a source HTML file
      string documentPath = Path.Combine(DataDir, "canvas.html");

      // Prepare a path for converted file saving 
      string savePath = Path.Combine(OutputDir, "canvas-output-options.docx");

      // Initialize an HTML document from the file
      using var document = new HTMLDocument(documentPath);

      // Initialize DocSaveOptions. Set up the page-size 600x400 pixels and margins
      var options = new DocSaveOptions();
      options.PageSetup.AnyPage = new Page(new Aspose.Html.Drawing.Size(600, 400), new Margin(10, 10, 10, 10));

      // Convert HTML to DOCX
      Converter.ConvertHTML(document, options, savePath);
```

*OutputDir - custom output folder path.

### See Also

* class [DocRenderingOptions](../../aspose.html.rendering.doc/docrenderingoptions/)
* namespace [Aspose.Html.Saving](../../aspose.html.saving/)
* assembly [Aspose.HTML](../../)
