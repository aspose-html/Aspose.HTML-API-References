---
title: "MHTMLSaveOptions-Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.saving.MHTMLSaveOptions class. Stellt MHTML-Speicheroptionen dar. Durch Zuweisen bestimmter Eigenschaften können Sie die Ressourcenverarbeitung verwalten, z. B. die maximale Verarbeitungstiefe usw. Weitere Informationen siehe im Dokumentationsartikel"
type: docs

url: /de/java/com.aspose.html.saving/mhtmlsaveoptions/
---
## MHTMLSaveOptions class

Stellt MHTML-Speicheroptionen dar. Durch Zuweisen spezifischer Eigenschaften können Sie die Ressourcenverarbeitung wie maximale Verarbeitungstiefe usw. verwalten. Weitere Informationen finden Sie in der Dokumentation [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options).

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
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Gibt ein [`ResourceHandlingOptions`](../resourcehandlingoptions/) Objekt zurück, das für die Konfiguration der Ressourcenverwaltung verwendet wird. |

## Hinweise

Sie finden vollständige Beispiele und Datendateien auf [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Beispiele

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
import System.IO;
...
	 // Bereiten Sie HTML-Code mit einem Link zu einer anderen Datei vor und speichern Sie ihn in die Datei 'document.html'
      var code = "<span>Hello, World!!</span> " +
            "<a href='document2.html'>click</a>";
      File.WriteAllText("document.html", code);

      // Bereiten Sie HTML-Code vor und speichern Sie ihn in die Datei 'document2.html'
      code = @"<span>Hello, World!!</span>";
      File.WriteAllText("document2.html", code);
       
      String savePath = Path.Combine(OutputDir, "output-options.mht");

      // Ändern Sie den Wert der Ressourcenverknüpfungstiefe auf 1, um das Dokument mit direkt verknüpften Ressourcen zu konvertieren
      var options = new MHTMLSaveOptions()
      {
        ResourceHandlingOptions =
        {
          MaxHandlingDepth = 1
        }
      };

      // HTML zu MHTML konvertieren
      Converter.ConvertHTML("document.html", options, savePath);  
```

### Siehe auch

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
