---
title: "HTMLSaveOptions Class"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.saving.HTMLSaveOptions class. Representerar HTML-sparalternativ. Genom att tilldela specifika egenskaper kan du hantera resursbearbetning såsom maximal hanteringsdjup med mera. Mer information finns i dokumentationsartikeln"
type: docs

url: /sv/java/com.aspose.html.saving/htmlsaveoptions/
---
## HTMLSaveOptions class

Representerar HTML-sparalternativ. Genom att tilldela specifika egenskaper kan du hantera resursbehandling såsom maximal hanteringsdjup med mera. Mer information finns i dokumentationen [article](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```java
public class HTMLSaveOptions : SaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [HTMLSaveOptions](htmlsaveoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
[getDocumentType]
[setDocumentType] Gets or sets the output document type. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Hämtar ett [`ResourceHandlingOptions`](../resourcehandlingoptions/)‑objekt som används för konfiguration av resurshantering. |
[getSerializeInputValue]
[setSerializeInputValue] This option controls whether to serialize the value of the [`HTMLInputElement`](../../com.aspose.html/htmlinputelement/)'s or the [`HTMLTextAreaElement`](../../com.aspose.html/htmltextareaelement/)'s "value" property into the "value" attribute. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [AUTO](../../com.aspose.html.saving/htmlsaveoptions/auto/) | Dokumenttypen för utdata kommer att väljas automatiskt. |
| const [HTML](../../com.aspose.html.saving/htmlsaveoptions/html/) | Dokumentet kommer att sparas som HTML. |
| const [XHTML](../../com.aspose.html.saving/htmlsaveoptions/xhtml/) | Dokumentet kommer att sparas som XHTML. |

## Anmärkningar

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exempel

```java
import Aspose.Html;
import com.aspose.html.dom.svg;
import com.aspose.html.saving;
import System;
...
     // Förbered en utdataväg för ett HTML-dokument 
      String documentPath = Path.Combine(OutputDir, "save-with-linked-file.html");

      // Förbered en enkel HTML-fil med ett länkat dokument
      File.WriteAllText(documentPath, "<p>Hello World!</p>" +
                      "<a href='linked.html'>linked file</a>");

      // Förbered en enkel länkat HTML-fil
      File.WriteAllText(Path.Combine(OutputDir, "linked.html"), "<p>Hello linked file!</p>");

      // Läs in "save-with-linked-file.html" i minnet
      using (var document = new HTMLDocument(documentPath))
      {
        // Skapa en instans av sparalternativ
        var options = new HTMLSaveOptions();

        // Följande rad med värdet '0' avbryter alla andra länkade HTML-filer när detta objekt sparas
        // Om du tar bort den här raden eller ändrar värdet till '1' kommer filen 'linked.html' också att sparas till utdata-mappen
        options.ResourceHandlingOptions.MaxHandlingDepth = 1;

        // Spara dokumentet med sparalternativen
        document.Save(Path.Combine(OutputDir, "save-with-linked-file_out.html"), options);
      }
```

*OutputDir - user output folder.

### Se även

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
