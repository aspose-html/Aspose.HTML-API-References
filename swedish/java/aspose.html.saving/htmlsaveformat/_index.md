---
title: "HTMLSaveFormat-enum"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.saving.HTMLSaveFormat-enum. Anger formatet som dokumentet sparas i. Du kan hitta mer information om att spara HTMLDocument i en artikel"
type: docs

url: /sv/java/com.aspose.html.saving/htmlsaveformat/
---
## HTMLSaveFormat enumeration

Anger formatet som dokumentet sparas i. Du kan hitta mer information om att spara [`HTMLDocument`](../../com.aspose.html/htmldocument/) i [artikel](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```java
public enum HTMLSaveFormat
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Original | `0` | Dokumentet kommer att sparas i sitt ursprungliga format. |
| Markdown | `1` | Dokumentet kommer att sparas som Markdown. |
| MHTML | `2` | Dokumentet kommer att sparas som MHTML. |

## Anmärkningar

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exempel

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
  // Förbered en utdataväg för att spara ett dokument.
  String documentPath = Path.Combine(OutputDir, "save-to-MD.md");

  // Förbered HTML‑kod
  var html_code = "<H2>Hello World!</H2>";
   
  // Initiera ett dokument från String‑variabeln
  using (var document = new HTMLDocument(html_code, "."))
  {
    // Spara dokumentet som en Markdown‑fil
    document.Save(documentPath, HTMLSaveFormat.Markdown);
  }
```

*OutputDir - user output folder path.

### Se även

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
