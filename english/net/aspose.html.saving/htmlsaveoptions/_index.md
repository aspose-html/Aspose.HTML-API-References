---
title: HTMLSaveOptions Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Saving.HTMLSaveOptions class. Represents HTML save options. By assigning specific properties you can manage resource processing such as max handling depth and so on. More info see in documentation article
type: docs
weight: 4760
url: /net/aspose.html.saving/htmlsaveoptions/
---
## HTMLSaveOptions class

Represents HTML save options. By assigning specific properties you can manage resource processing such as max handling depth and so on. More info see in documentation [article](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```csharp
public class HTMLSaveOptions : SaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [HTMLSaveOptions](htmlsaveoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [DocumentType](../../aspose.html.saving/htmlsaveoptions/documenttype/) { get; set; } | Gets or sets the output document type. |
| [ResourceHandlingOptions](../../aspose.html.saving/saveoptions/resourcehandlingoptions/) { get; } | Gets a [`ResourceHandlingOptions`](../resourcehandlingoptions/) object which is used for configuration of resources handling. |
| [SerializeInputValue](../../aspose.html.saving/htmlsaveoptions/serializeinputvalue/) { get; set; } | This option controls whether to serialize the value of the [`HTMLInputElement`](../../aspose.html/htmlinputelement/)'s or the [`HTMLTextAreaElement`](../../aspose.html/htmltextareaelement/)'s "value" property into the "value" attribute. |

## Fields

| Name | Description |
| --- | --- |
| const [AUTO](../../aspose.html.saving/htmlsaveoptions/auto/) | The output document type will be selected automatically. |
| const [HTML](../../aspose.html.saving/htmlsaveoptions/html/) | The document will be saved as HTML. |
| const [XHTML](../../aspose.html.saving/htmlsaveoptions/xhtml/) | The document will be saved as XHTML. |

## Remarks

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Examples

```csharp
using Aspose.Html;
using Aspose.Html.Dom.Svg;
using Aspose.Html.Saving;
using System;
...
     // Prepare an output path for an HTML document 
      string documentPath = Path.Combine(OutputDir, "save-with-linked-file.html");

      // Prepare a simple HTML file with a linked document
      File.WriteAllText(documentPath, "<p>Hello World!</p>" +
                      "<a href='linked.html'>linked file</a>");

      // Prepare a simple linked HTML file
      File.WriteAllText(Path.Combine(OutputDir, "linked.html"), "<p>Hello linked file!</p>");

      // Load the "save-with-linked-file.html" into memory
      using (var document = new HTMLDocument(documentPath))
      {
        // Create a save options instance
        var options = new HTMLSaveOptions();

        // The following line with value '0' cuts off all other linked HTML-files while saving this instance
        // If you remove this line or change value to the '1', the 'linked.html' file will be saved as well to the output folder
        options.ResourceHandlingOptions.MaxHandlingDepth = 1;

        // Save the document with the save options
        document.Save(Path.Combine(OutputDir, "save-with-linked-file_out.html"), options);
      }
```

*OutputDir - user output folder.

### See Also

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Html.Saving](../../aspose.html.saving/)
* assembly [Aspose.HTML](../../)
