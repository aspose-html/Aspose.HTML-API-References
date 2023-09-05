---
title: HTMLSaveFormat Enum
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Saving.HTMLSaveFormat enum. Specifies format in which document is saved. You can find more info about saving HTMLDocument in article
type: docs
weight: 4740
url: /net/aspose.html.saving/htmlsaveformat/
---
## HTMLSaveFormat enumeration

Specifies format in which document is saved. You can find more info about saving [`HTMLDocument`](../../aspose.html/htmldocument/) in [article](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```csharp
public enum HTMLSaveFormat
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Original | `0` | The document will be saved in its original format. |
| Markdown | `1` | Document will be saved as Markdown. |
| MHTML | `2` | Document will be saved as MHTML. |

## Remarks

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Examples

```csharp
using System.IO;
using Aspose.Html;
using Aspose.Html.Saving;
...
  // Prepare an output path for a document saving
  string documentPath = Path.Combine(OutputDir, "save-to-MD.md");

  // Prepare HTML code
  var html_code = "<H2>Hello World!</H2>";
   
  // Initialize a document from the string variable
  using (var document = new HTMLDocument(html_code, "."))
  {
    // Save the document as a Markdown file
    document.Save(documentPath, HTMLSaveFormat.Markdown);
  }
```

*OutputDir - user output folder path.

### See Also

* namespace [Aspose.Html.Saving](../../aspose.html.saving/)
* assembly [Aspose.HTML](../../)
