---
title: "Enum HTMLSaveFormat"
second_title: "Riferimento API Aspose.HTML per Java"
description: "enum com.aspose.html.saving.HTMLSaveFormat. Specifica il formato in cui il documento viene salvato. Puoi trovare maggiori informazioni sul salvataggio di HTMLDocument nell'articolo"
type: docs

url: /it/java/com.aspose.html.saving/htmlsaveformat/
---
## HTMLSaveFormat enumeration

Specifica il formato in cui il documento viene salvato. Puoi trovare maggiori informazioni sul salvataggio di [`HTMLDocument`](../../com.aspose.html/htmldocument/) nell'[articolo](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```java
public enum HTMLSaveFormat
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Original | `0` | Il documento verrà salvato nel suo formato originale. |
| Markdown | `1` | Il documento verrà salvato come Markdown. |
| MHTML | `2` | Il documento verrà salvato come MHTML. |

## Osservazioni

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Esempi

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
  // Prepara un percorso di output per il salvataggio di un documento
  String documentPath = Path.Combine(OutputDir, "save-to-MD.md");

  // Prepara il codice HTML
  var html_code = "<H2>Hello World!</H2>";
   
  // Inizializza un documento dalla variabile String
  using (var document = new HTMLDocument(html_code, "."))
  {
    // Salva il documento come file Markdown
    document.Save(documentPath, HTMLSaveFormat.Markdown);
  }
```

*OutputDir - user output folder path.

### Vedi anche

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
