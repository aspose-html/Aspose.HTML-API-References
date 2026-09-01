---
title: "PdfSaveOptions Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.saving.PdfSaveOptions klasse. Specifieke gegevensklasse biedt enkele eigenschappen om het conversieresultaat te beheren. Bijvoorbeeld PageSetup specificeert paginakarakteristieken. Raadpleeg het documentatie‑artikel."
type: docs

url: /nl/java/com.aspose.html.saving/pdfsaveoptions/
---
## PdfSaveOptions class

Specifieke gegevensklasse biedt enkele eigenschappen om het conversieresultaat te beheren. Bijvoorbeeld [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) specificeert paginakarakteristieken. Raadpleeg de documentatie [artikel](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions).

```java
public class PdfSaveOptions : PdfRenderingOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Haalt een [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) object op dat wordt gebruikt voor de configuratie van de verwerking van CSS‑eigenschappen. |
| [getDocumentInfo](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/documentinfo/) Bevat informatie over het uitvoer‑PDF‑document. |
[getEncryption]
[setEncryption] Gets or sets a encryption details. If not set, then no encryption will be performed. |
[getFormFieldBehaviour]
[setFormFieldBehaviour] Specifies the behavior of form fields in the output PDF document. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Stelt de horizontale resolutie in of haalt deze op voor interne (die tijdens filterverwerking worden gebruikt) afbeeldingen, in pixels per inch. Standaard is deze eigenschap 300 dpi. |
[getIsTaggedPdf]
[setIsTaggedPdf] Creates a tag structure if `true`. |
[getJpegQuality]
[setJpegQuality] Specifies the quality of JPEG compression for images (if JPEG compression is used). Default is 95. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Haalt een paginainstellingsobject op dat wordt gebruikt voor de configuratie van de uitvoer‑pagina‑set. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Stelt de verticale resolutie in of haalt deze op voor interne (die tijdens filterverwerking worden gebruikt) afbeeldingen, in pixels per inch. Standaard is deze eigenschap 300 dpi. |

## Opmerkingen

Je kunt volledige voorbeelden en gegevensbestanden vinden op [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Voorbeelden

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
...
 	 // Bereid een pad voor naar een bron‑HTML‑bestand
      String documentPath = Path.Combine(DataDir, "drawing.html");

      // Bereid een pad voor voor het opslaan van het geconverteerde bestand 
      String savePath = Path.Combine(OutputDir, "drawing-options.pdf");

      // Initialiseer een HTML‑document vanuit het bestand
      using var document = new HTMLDocument(documentPath);

      // Initialiseer PdfSaveOptions. Stel de paginagrootte in op 600x300 pixels, marges, 
      // resoluties en wijzig de achtergrondkleur naar AliceBlue 
      var options = new PdfSaveOptions()
      {         
        HorizontalResolution = 200,
        VerticalResolution = 200,
        BackgroundColor = Color.AliceBlue,
        JpegQuality = 100
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 300), new Margin(20, 10, 10, 10));      

      // HTML naar PDF converteren
      Converter.ConvertHTML(document, options, savePath);
```

### Zie ook

* class [PdfRenderingOptions](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
