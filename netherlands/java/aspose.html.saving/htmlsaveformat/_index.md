---
title: "HTMLSaveFormat Enum"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.saving.HTMLSaveFormat enum. Specificeert het formaat waarin het document wordt opgeslagen. Meer informatie over het opslaan van HTMLDocument vindt u in het artikel"
type: docs

url: /nl/java/com.aspose.html.saving/htmlsaveformat/
---
## HTMLSaveFormat enumeration

Specificeert het formaat waarin het document wordt opgeslagen. Meer informatie over het opslaan van [`HTMLDocument`](../../com.aspose.html/htmldocument/) vindt u in [artikel](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```java
public enum HTMLSaveFormat
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Original | `0` | Het document wordt opgeslagen in het oorspronkelijke formaat. |
| Markdown | `1` | Document wordt opgeslagen als Markdown. |
| MHTML | `2` | Document wordt opgeslagen als MHTML. |

## Opmerkingen

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Voorbeelden

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
  // Bereid een uitvoerpad voor voor het opslaan van een document
  String documentPath = Path.Combine(OutputDir, "save-to-MD.md");

  // Bereid HTML-code voor
  var html_code = "<H2>Hello World!</H2>";
   
  // Initialiseer een document vanuit de String-variabele
  using (var document = new HTMLDocument(html_code, "."))
  {
    // Sla het document op als een Markdown-bestand
    document.Save(documentPath, HTMLSaveFormat.Markdown);
  }
```

*OutputDir - user output folder path.

### Zie ook

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
