---
title: "HTMLSaveFormat Aufzählung"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.saving.HTMLSaveFormat Aufzählung. Gibt das Format an, in dem das Dokument gespeichert wird. Weitere Informationen zum Speichern von HTMLDocument finden Sie im Artikel"
type: docs

url: /de/java/com.aspose.html.saving/htmlsaveformat/
---
## HTMLSaveFormat enumeration

Gibt das Format an, in dem das Dokument gespeichert wird. Weitere Informationen zum Speichern von [`HTMLDocument`](../../com.aspose.html/htmldocument/) finden Sie im [Artikel](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```java
public enum HTMLSaveFormat
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Original | `0` | Das Dokument wird in seinem Originalformat gespeichert. |
| Markdown | `1` | Dokument wird als Markdown gespeichert. |
| MHTML | `2` | Dokument wird als MHTML gespeichert. |

## Hinweise

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) herunterladen.

## Beispiele

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
  // Bereiten Sie einen Ausgabepfad für das Speichern eines Dokuments vor
  String documentPath = Path.Combine(OutputDir, "save-to-MD.md");

  // HTML-Code vorbereiten
  var html_code = "<H2>Hello World!</H2>";
   
  // Initialisieren Sie ein Dokument aus der String‑Variablen
  using (var document = new HTMLDocument(html_code, "."))
  {
    // Speichern Sie das Dokument als Markdown‑Datei
    document.Save(documentPath, HTMLSaveFormat.Markdown);
  }
```

*OutputDir - user output folder path.

### Siehe auch

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
