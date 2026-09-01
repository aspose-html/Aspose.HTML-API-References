---
title: "Classe XpsSaveOptions"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Classe com.aspose.html.saving.XpsSaveOptions. La classe dati di opzioni specifiche fornisce alcune proprietà per gestire il risultato della conversione. Ad esempio PageSetup specifica le caratteristiche della pagina. Consulta l'articolo della documentazione"
type: docs

url: /it/java/com.aspose.html.saving/xpssaveoptions/
---
## XpsSaveOptions class

La classe dati di opzioni specifiche fornisce alcune proprietà per gestire il risultato della conversione. Ad esempio [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) specifica le caratteristiche della pagina. Consulta la documentazione [articolo](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#save-options).

```java
public class XpsSaveOptions : XpsRenderingOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Ottiene un oggetto [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) che viene utilizzato per la configurazione dell'elaborazione delle proprietà CSS. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Imposta o ottiene la risoluzione orizzontale per le immagini interne (utilizzate durante l'elaborazione dei filtri), in pixel per pollice. Per impostazione predefinita questa proprietà è 300 dpi. |
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
	  String documentPath = Path.Combine(OutputDir, "save-options.html");
      String savePath = Path.Combine(OutputDir, "save-options-output.xps");

      // Prepara il codice HTML e salvalo in un file
      var code = "<h1> XpsSaveOptions Class</h1>\r\n" +
            "<p>Using XpsSaveOptions Class, you can programmatically apply a wide range of conversion parameters such as BackgroundColor, PageSetup, etc.</p>\r\n";

      File.WriteAllText(documentPath, code);

      // Inizializza un documento HTML dal file html
      using var document = new HTMLDocument(documentPath);
       
      // Imposta la dimensione della pagina, i margini e cambia il colore di sfondo in AntiqueWhite
      var options = new XpsSaveOptions()
      {
        BackgroundColor = Color.AntiqueWhite
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(Length.FromInches(4.9f), Length.FromInches(3.5f)), new Margin(30, 20, 10, 10));

      // Converti HTML in XPS
      Converter.ConvertHTML(document, options, savePath); 
```

### Vedi anche

* class [XpsRenderingOptions](../../com.aspose.html.rendering.xps/xpsrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
