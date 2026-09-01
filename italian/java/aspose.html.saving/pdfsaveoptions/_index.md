---
title: "Classe PdfSaveOptions"
second_title: "Aspose.HTML per Java Riferimento API"
description: "classe com.aspose.html.saving.PdfSaveOptions. Questa classe di dati specifica fornisce alcune proprietà per gestire il risultato della conversione. Ad esempio PageSetup specifica le caratteristiche della pagina. Consulta l'articolo della documentazione"
type: docs

url: /it/java/com.aspose.html.saving/pdfsaveoptions/
---
## PdfSaveOptions class

La classe di dati specifica fornisce alcune proprietà per gestire il risultato della conversione. Ad esempio [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) specifica le caratteristiche della pagina. Consulta la documentazione [articolo](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions).

```java
public class PdfSaveOptions : PdfRenderingOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Ottiene un oggetto [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) che viene utilizzato per la configurazione dell'elaborazione delle proprietà CSS. |
| [getDocumentInfo](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/documentinfo/) Contiene informazioni sul documento PDF di output. |
[getEncryption]
[setEncryption] Gets or sets a encryption details. If not set, then no encryption will be performed. |
[getFormFieldBehaviour]
[setFormFieldBehaviour] Specifies the behavior of form fields in the output PDF document. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Imposta o ottiene la risoluzione orizzontale per le immagini interne (utilizzate durante l'elaborazione dei filtri), in pixel per pollice. Per impostazione predefinita questa proprietà è 300 dpi. |
[getIsTaggedPdf]
[setIsTaggedPdf] Creates a tag structure if `true`. |
[getJpegQuality]
[setJpegQuality] Specifies the quality of JPEG compression for images (if JPEG compression is used). Default is 95. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Ottiene un oggetto di configurazione della pagina utilizzato per la configurazione dell'output del set di pagine. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Imposta o ottiene la risoluzione verticale per le immagini interne (utilizzate durante l'elaborazione dei filtri), in pixel per pollice. Per impostazione predefinita questa proprietà è 300 dpi. |

## Osservazioni

È possibile trovare esempi completi e file di dati su [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
...
 	 // Prepara un percorso a un file HTML di origine
      String documentPath = Path.Combine(DataDir, "drawing.html");

      // Prepara un percorso per il salvataggio del file convertito
      String savePath = Path.Combine(OutputDir, "drawing-options.pdf");

      // Inizializza un documento HTML dal file
      using var document = new HTMLDocument(documentPath);

      // Inizializza PdfSaveOptions. Imposta la dimensione della pagina 600x300 pixel, i margini, 
      // le risoluzioni e cambia il colore di sfondo in AliceBlue 
      var options = new PdfSaveOptions()
      {         
        HorizontalResolution = 200,
        VerticalResolution = 200,
        BackgroundColor = Color.AliceBlue,
        JpegQuality = 100
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 300), new Margin(20, 10, 10, 10));      

      // Converti HTML in PDF
      Converter.ConvertHTML(document, options, savePath);
```

### Vedi anche

* class [PdfRenderingOptions](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
