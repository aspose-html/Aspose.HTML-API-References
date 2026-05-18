---
title: "PdfSaveOptions Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.saving.PdfSaveOptions Klasse. Spezifische Datenklasse bietet einige Eigenschaften zur Verwaltung des Konvertierungsergebnisses. Zum Beispiel gibt PageSetup die Seiteneigenschaften an. Siehe den Dokumentationsartikel"
type: docs

url: /de/java/com.aspose.html.saving/pdfsaveoptions/
---
## PdfSaveOptions class

Spezifische Datenklasse bietet einige Eigenschaften zur Verwaltung des Konvertierungsergebnisses. Zum Beispiel gibt [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) die Seiteneigenschaften an. Siehe die Dokumentation [Artikel](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions).

```java
public class PdfSaveOptions : PdfRenderingOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Gibt ein [`CssOptions`](../../com.aspose.html.rendering/cssoptions/)‑Objekt zurück, das für die Konfiguration der Verarbeitung von CSS‑Eigenschaften verwendet wird. |
| [getDocumentInfo](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/documentinfo/) Enthält Informationen über das ausgegebene PDF-Dokument. |
[getEncryption]
[setEncryption] Gets or sets a encryption details. If not set, then no encryption will be performed. |
[getFormFieldBehaviour]
[setFormFieldBehaviour] Specifies the behavior of form fields in the output PDF document. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Legt die horizontale Auflösung für interne (bei der Filterverarbeitung verwendete) Bilder fest oder gibt sie zurück, gemessen in Pixel pro Zoll. Standardmäßig beträgt diese Eigenschaft 300 dpi. |
[getIsTaggedPdf]
[setIsTaggedPdf] Creates a tag structure if `true`. |
[getJpegQuality]
[setJpegQuality] Specifies the quality of JPEG compression for images (if JPEG compression is used). Default is 95. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Gibt ein Seiten‑Setup‑Objekt zurück, das für die Konfiguration des Ausgabeseiten‑Sets verwendet wird. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Legt die vertikale Auflösung für interne (bei der Filterverarbeitung verwendete) Bilder fest oder gibt sie zurück, gemessen in Pixel pro Zoll. Standardmäßig beträgt diese Eigenschaft 300 dpi. |

## Hinweise

Vollständige Beispiele und Datendateien finden Sie auf [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Beispiele

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
...
 	 // Bereiten Sie einen Pfad zu einer Quell-HTML-Datei vor
      String documentPath = Path.Combine(DataDir, "drawing.html");

      // Bereiten Sie einen Pfad für das Speichern der konvertierten Datei vor
      String savePath = Path.Combine(OutputDir, "drawing-options.pdf");

      // Initialisieren Sie ein HTML-Dokument aus der Datei
      using var document = new HTMLDocument(documentPath);

      // Initialisiere PdfSaveOptions. Lege die Seitengröße 600x300 Pixel, Ränder, 
      // Auflösungen und ändere die Hintergrundfarbe zu AliceBlue 
      var options = new PdfSaveOptions()
      {         
        HorizontalResolution = 200,
        VerticalResolution = 200,
        BackgroundColor = Color.AliceBlue,
        JpegQuality = 100
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 300), new Margin(20, 10, 10, 10));      

      // HTML in PDF konvertieren
      Converter.ConvertHTML(document, options, savePath);
```

### Siehe auch

* class [PdfRenderingOptions](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
