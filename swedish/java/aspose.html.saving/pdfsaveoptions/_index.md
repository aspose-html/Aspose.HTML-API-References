---
title: "PdfSaveOptions-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.saving.PdfSaveOptions-klass. Specifik dataklass tillhandahåller några egenskaper för att hantera konverteringsresultatet. Till exempel specificerar PageSetup sidans egenskaper. Se dokumentationsartikel."
type: docs

url: /sv/java/com.aspose.html.saving/pdfsaveoptions/
---
## PdfSaveOptions class

Specifik dataklass tillhandahåller några egenskaper för att hantera konverteringsresultatet. Till exempel [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) specificerar sidans egenskaper. Se dokumentations[artikel](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions).

```java
public class PdfSaveOptions : PdfRenderingOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Hämtar ett [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) objekt som används för konfiguration av bearbetning av css-egenskaper. |
| [getDocumentInfo](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/documentinfo/) Innehåller information om det utgående PDF-dokumentet. |
[getEncryption]
[setEncryption] Gets or sets a encryption details. If not set, then no encryption will be performed. |
[getFormFieldBehaviour]
[setFormFieldBehaviour] Specifies the behavior of form fields in the output PDF document. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Ställer in eller hämtar horisontell upplösning för interna (som används under filterbearbetning) bilder, i pixlar per tum. Som standard är denna egenskap 300 dpi. |
[getIsTaggedPdf]
[setIsTaggedPdf] Creates a tag structure if `true`. |
[getJpegQuality]
[setJpegQuality] Specifies the quality of JPEG compression for images (if JPEG compression is used). Default is 95. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Hämtar ett sidinställningsobjekt som används för konfiguration av utdata siduppsättning. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Ställer in eller hämtar vertikal upplösning för interna (som används under filterbearbetning) bilder, i pixlar per tum. Som standard är denna egenskap 300 dpi. |

## Anmärkningar

Du kan hitta kompletta exempel och datafiler på [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exempel

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
...
 	 // Förbered en sökväg till en käll-HTML-fil
      String documentPath = Path.Combine(DataDir, "drawing.html");

      // Förbered en sökväg för att spara den konverterade filen
      String savePath = Path.Combine(OutputDir, "drawing-options.pdf");

      // Initiera ett HTML-dokument från filen
      using var document = new HTMLDocument(documentPath);

      // Initiera PdfSaveOptions. Ställ in sidstorleken 600x300 pixlar, marginaler, 
      // upplösningar och ändra bakgrundsfärgen till AliceBlue 
      var options = new PdfSaveOptions()
      {         
        HorizontalResolution = 200,
        VerticalResolution = 200,
        BackgroundColor = Color.AliceBlue,
        JpegQuality = 100
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 300), new Margin(20, 10, 10, 10));      

      // Konvertera HTML till PDF
      Converter.ConvertHTML(document, options, savePath);
```

### Se även

* class [PdfRenderingOptions](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
