---
title: DocSaveOptions Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.saving.DocSaveOptions class. Specific options data class. By assigning properties you can manage rendering characteristics such as resolution page size background color as well as doc specific options such as font embedding. More info see in documentation article
type: docs
weight: 4600
url: /java/com.aspose.html.saving/docsaveoptions/
---
## DocSaveOptions class

Specific options data class. By assigning properties you can manage rendering characteristics such as resolution, page size, background color as well as doc specific options such as font embedding. More info see in documentation [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#save-options).

```java
public class DocSaveOptions : DocRenderingOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Gets a [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) object which is used for configuration of css properties processing. |
[getDocumentFormat]
[setDocumentFormat] Gets or sets the file format of the output document. The default value is DOCX. |
[getFontEmbeddingRule]
[setFontEmbeddingRule] Gets or sets the font embedding rule. The default value is None. |
[getHorizontalResolution]
[setHorizontalResolution] Sets or gets horizontal resolution for internal (which are used during filters processing) images, in pixels per inch. By default this property is 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Gets a page setup object is used for configuration output page-set. |
[getVerticalResolution]
[setVerticalResolution] Sets or gets vertical resolution for internal (which are used during filters processing) images, in pixels per inch. By default this property is 300 dpi. |

## Remarks

You can download the complete examples and data files from [GitHub](https://github.com/com.aspose.html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Examples

```java
import com.aspose.html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.saving;
import System;
...
 // Prepare a path to a source HTML file
      String documentPath = Path.Combine(DataDir, "canvas.html");

      // Prepare a path for converted file saving 
      String savePath = Path.Combine(OutputDir, "canvas-output-options.docx");

      // Initialize an HTML document from the file
      using var document = new HTMLDocument(documentPath);

      // Initialize DocSaveOptions. Set up the page-size 600x400 pixels and margins
      var options = new DocSaveOptions();
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 400), new Margin(10, 10, 10, 10));

      // Convert HTML to DOCX
      Converter.ConvertHTML(document, options, savePath);
```

*OutputDir - custom output folder path.

### See Also

* class [DocRenderingOptions](../../com.aspose.html.rendering.doc/docrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
