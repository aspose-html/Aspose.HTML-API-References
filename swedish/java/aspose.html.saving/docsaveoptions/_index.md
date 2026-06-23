---
title: "DocSaveOptions-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.saving.DocSaveOptions-klass. Specifik alternativdataklass. Genom att tilldela egenskaper kan du hantera renderingskaraktäristik såsom upplösning, sidstorlek, bakgrundsfärg samt dokumentspecifika alternativ som teckensnittsinbäddning. Mer information finns i dokumentationsartikeln."
type: docs

url: /sv/java/com.aspose.html.saving/docsaveoptions/
---
## DocSaveOptions class

Specifik dataklass för alternativ. Genom att tilldela egenskaper kan du hantera renderingskarakteristik såsom upplösning, sidstorlek, bakgrundsfärg samt dokumentspecifika alternativ som teckensnitts‑inbäddning. Mer information finns i dokumentationen [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#save-options).

```java
public class DocSaveOptions : DocRenderingOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Hämtar ett [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) objekt som används för konfiguration av bearbetning av css-egenskaper. |
[getDocumentFormat]
[setDocumentFormat] Gets or sets the file format of the output document. The default value is DOCX. |
[getFontEmbeddingRule]
[setFontEmbeddingRule] Gets or sets the font embedding rule. The default value is None. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Ställer in eller hämtar horisontell upplösning för interna (som används under filterbearbetning) bilder, i pixlar per tum. Som standard är denna egenskap 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Hämtar ett sidinställningsobjekt som används för konfiguration av utdata siduppsättning. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Ställer in eller hämtar vertikal upplösning för interna (som används under filterbearbetning) bilder, i pixlar per tum. Som standard är denna egenskap 300 dpi. |

## Anmärkningar

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.saving;
import System;
...
 // Förbered en sökväg till en käll-HTML-fil
      String documentPath = Path.Combine(DataDir, "canvas.html");

      // Förbered en sökväg för att spara den konverterade filen
      String savePath = Path.Combine(OutputDir, "canvas-output-options.docx");

      // Initiera ett HTML-dokument från filen
      using var document = new HTMLDocument(documentPath);

      // Initiera DocSaveOptions. Ställ in sidstorleken 600x400 pixlar och marginaler
      var options = new DocSaveOptions();
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 400), new Margin(10, 10, 10, 10));

      // Konvertera HTML till DOCX
      Converter.ConvertHTML(document, options, savePath);
```

*OutputDir - custom output folder path.

### Se även

* class [DocRenderingOptions](../../com.aspose.html.rendering.doc/docrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
