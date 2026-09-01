---
title: "HTMLSaveOptions-Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.saving.HTMLSaveOptions-Klasse. Stellt HTML-Speicheroptionen dar. Durch Zuweisen bestimmter Eigenschaften können Sie die Ressourcenverarbeitung verwalten, z. B. die maximale Verarbeitungstiefe usw. Weitere Informationen finden Sie im Dokumentationsartikel."
type: docs

url: /de/java/com.aspose.html.saving/htmlsaveoptions/
---
## HTMLSaveOptions class

Stellt HTML-Speicheroptionen dar. Durch Zuweisen spezifischer Eigenschaften können Sie die Ressourcenverarbeitung wie maximale Verarbeitungstiefe usw. verwalten. Weitere Informationen finden Sie in der Dokumentation [article](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```java
public class HTMLSaveOptions : SaveOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [HTMLSaveOptions](htmlsaveoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
[getDocumentType]
[setDocumentType] Gets or sets the output document type. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Gibt ein [`ResourceHandlingOptions`](../resourcehandlingoptions/) Objekt zurück, das für die Konfiguration der Ressourcenverwaltung verwendet wird. |
[getSerializeInputValue]
[setSerializeInputValue] This option controls whether to serialize the value of the [`HTMLInputElement`](../../com.aspose.html/htmlinputelement/)'s or the [`HTMLTextAreaElement`](../../com.aspose.html/htmltextareaelement/)'s "value" property into the "value" attribute. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [AUTO](../../com.aspose.html.saving/htmlsaveoptions/auto/) | Der Ausgabetyp des Dokuments wird automatisch ausgewählt. |
| const [HTML](../../com.aspose.html.saving/htmlsaveoptions/html/) | Das Dokument wird als HTML gespeichert. |
| const [XHTML](../../com.aspose.html.saving/htmlsaveoptions/xhtml/) | Das Dokument wird als XHTML gespeichert. |

## Hinweise

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) herunterladen.

## Beispiele

```java
import Aspose.Html;
import com.aspose.html.dom.svg;
import com.aspose.html.saving;
import System;
...
     // Bereiten Sie einen Ausgabepfad für ein HTML-Dokument vor.
      String documentPath = Path.Combine(OutputDir, "save-with-linked-file.html");

      // Erstellen Sie eine einfache HTML-Datei mit einem verknüpften Dokument.
      File.WriteAllText(documentPath, "<p>Hello World!</p>" +
                      "<a href='linked.html'>linked file</a>");

      // Erstellen Sie eine einfache verknüpfte HTML-Datei.
      File.WriteAllText(Path.Combine(OutputDir, "linked.html"), "<p>Hello linked file!</p>");

      // Laden Sie die "save-with-linked-file.html" in den Speicher.
      using (var document = new HTMLDocument(documentPath))
      {
        // Erstellen Sie eine Instanz von Speicheroptionen.
        var options = new HTMLSaveOptions();

        // Die folgende Zeile mit dem Wert '0' schneidet alle anderen verknüpften HTML-Dateien ab, während diese Instanz gespeichert wird
        // Wenn Sie diese Zeile entfernen oder den Wert auf '1' ändern, wird die Datei 'linked.html' ebenfalls in den Ausgabordner gespeichert
        options.ResourceHandlingOptions.MaxHandlingDepth = 1;

        // Speichern Sie das Dokument mit den Speicheroptionen
        document.Save(Path.Combine(OutputDir, "save-with-linked-file_out.html"), options);
      }
```

*OutputDir - user output folder.

### Siehe auch

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
