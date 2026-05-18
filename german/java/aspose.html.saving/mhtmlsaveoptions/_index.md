---
title: "MHTMLSaveOptions‑Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.saving.MHTMLSaveOptions‑Klasse. Stellt MHTML‑Speicheroptionen dar. Durch Zuweisen bestimmter Eigenschaften können Sie die Ressourcenverarbeitung verwalten, z. B. die maximale Verarbeitungstiefe usw. Weitere Informationen finden Sie im Dokumentationsartikel."
type: docs

url: /de/java/com.aspose.html.saving/mhtmlsaveoptions/
---
## MHTMLSaveOptions class

Stellt MHTML-Speicheroptionen dar. Durch Zuweisen spezifischer Eigenschaften können Sie die Ressourcenverarbeitung wie maximale Verarbeitungstiefe usw. verwalten. Weitere Informationen siehe in der Dokumentation [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options).

```java
public class MHTMLSaveOptions : SaveOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MHTMLSaveOptions](mhtmlsaveoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Gibt ein [`ResourceHandlingOptions`](../resourcehandlingoptions/)‑Objekt zurück, das zur Konfiguration der Ressourcenverarbeitung verwendet wird. |

## Hinweise

Vollständige Beispiele und Datendateien finden Sie auf [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Beispiele

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
import System.IO;
...
	 // Erstellen Sie HTML‑Code mit einem Link zu einer anderen Datei und speichern Sie ihn als 'document.html'.
      var code = "<span>Hello, World!!</span> " +
            "<a href='document2.html'>click</a>";
      File.WriteAllText("document.html", code);

      // Erstellen Sie HTML‑Code und speichern Sie ihn als 'document2.html'.
      code = @"<span>Hello, World!!</span>";
      File.WriteAllText("document2.html", code);
       
      String savePath = Path.Combine(OutputDir, "output-options.mht");

      // Ändern Sie den Wert der Ressourcenverknüpfungstiefe auf 1, um das Dokument mit direkt verknüpften Ressourcen zu konvertieren.
      var options = new MHTMLSaveOptions()
      {
        ResourceHandlingOptions =
        {
          MaxHandlingDepth = 1
        }
      };

      // HTML in MHTML konvertieren
      Converter.ConvertHTML("document.html", options, savePath);  
```

### Siehe auch

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
