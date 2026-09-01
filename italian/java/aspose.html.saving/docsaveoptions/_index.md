---
title: "Classe DocSaveOptions"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Classe com.aspose.html.saving.DocSaveOptions. Classe dati di opzioni specifiche. Assegnando le proprietà è possibile gestire le caratteristiche di rendering come risoluzione, dimensione della pagina, colore di sfondo così come opzioni specifiche del documento come l'incorporamento dei font. Per ulteriori informazioni vedere l'articolo della documentazione"
type: docs

url: /it/java/com.aspose.html.saving/docsaveoptions/
---
## DocSaveOptions class

Classe dati di opzioni specifiche. Assegnando le proprietà è possibile gestire le caratteristiche di rendering come risoluzione, dimensione della pagina, colore di sfondo così come opzioni specifiche del documento come l'incorporamento dei font. Maggiori informazioni nella documentazione [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#save-options).

```java
public class DocSaveOptions : DocRenderingOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Ottiene un oggetto [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) che viene utilizzato per la configurazione dell'elaborazione delle proprietà CSS. |
[getDocumentFormat]
[setDocumentFormat] Gets or sets the file format of the output document. The default value is DOCX. |
[getFontEmbeddingRule]
[setFontEmbeddingRule] Gets or sets the font embedding rule. The default value is None. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Imposta o ottiene la risoluzione orizzontale per le immagini interne (utilizzate durante l'elaborazione dei filtri), in pixel per pollice. Per impostazione predefinita questa proprietà è 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Ottiene un oggetto di configurazione della pagina utilizzato per la configurazione dell'output del set di pagine. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Imposta o ottiene la risoluzione verticale per le immagini interne (utilizzate durante l'elaborazione dei filtri), in pixel per pollice. Per impostazione predefinita questa proprietà è 300 dpi. |

## Osservazioni

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.saving;
import System;
...
 // Prepara un percorso a un file HTML di origine
      String documentPath = Path.Combine(DataDir, "canvas.html");

      // Prepara un percorso per il salvataggio del file convertito
      String savePath = Path.Combine(OutputDir, "canvas-output-options.docx");

      // Inizializza un documento HTML dal file
      using var document = new HTMLDocument(documentPath);

      // Inizializza DocSaveOptions. Imposta la dimensione della pagina a 600x400 pixel e i margini
      var options = new DocSaveOptions();
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 400), new Margin(10, 10, 10, 10));

      // Converti HTML in DOCX
      Converter.ConvertHTML(document, options, savePath);
```

*OutputDir - custom output folder path.

### Vedi anche

* class [DocRenderingOptions](../../com.aspose.html.rendering.doc/docrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
