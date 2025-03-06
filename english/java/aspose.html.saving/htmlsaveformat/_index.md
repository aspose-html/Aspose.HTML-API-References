---
title: HTMLSaveFormat Enum
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.saving.HTMLSaveFormat enum. Specifies format in which document is saved. You can find more info about saving HTMLDocument in article
type: docs

url: /java/com.aspose.html.saving/htmlsaveformat/
---
## HTMLSaveFormat enumeration

Specifies format in which document is saved. You can find more info about saving [`HTMLDocument`](../../com.aspose.html/htmldocument/) in [article](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```java
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

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
  // Prepare an output path for a document saving
  String documentPath = Path.Combine(OutputDir, "save-to-MD.md");

  // Prepare HTML code
  var html_code = "<H2>Hello World!</H2>";
   
  // Initialize a document from the String variable
  using (var document = new HTMLDocument(html_code, "."))
  {
    // Save the document as a Markdown file
    document.Save(documentPath, HTMLSaveFormat.Markdown);
  }
```

*OutputDir - user output folder path.

### See Also

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
