---
title: "Classe ImageSaveOptions"
second_title: "Aspose.HTML per Java Riferimento API"
description: "classe com.aspose.html.saving.ImageSaveOptions. Classe di dati di opzioni specifiche. Fornisce proprietà per gestire la risoluzione del risultato immagine, l'anti-aliasing, la qualità, il formato così come le impostazioni della pagina e altro. Maggiori informazioni sono disponibili nell'articolo della documentazione"
type: docs

url: /it/java/com.aspose.html.saving/imagesaveoptions/
---
## ImageSaveOptions class

Classe dati di opzioni specifiche. Fornisce proprietà per gestire la risoluzione dell'immagine risultante, la qualità di smussatura, il formato così come le impostazioni della pagina, ecc. Maggiori informazioni sono disponibili nella documentazione [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#save-options).

```java
public class ImageSaveOptions : ImageRenderingOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/#constructor)() | Inizializza una nuova istanza della classe `ImageSaveOptions`; Png verrà utilizzato come formato immagine predefinito. |
| [ImageSaveOptions](imagesaveoptions/#constructor_1)(ImageFormat) | Formato immagine [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/) basato sull'inizializzazione |

## Proprietà

| Nome | Descrizione |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../../com.aspose.html.rendering.image/compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Ottiene un oggetto [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) che viene utilizzato per la configurazione dell'elaborazione delle proprietà CSS. |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Imposta o ottiene la risoluzione orizzontale per le immagini di output e interne (utilizzate durante l'elaborazione dei filtri), in pixel per pollice. Per impostazione predefinita questa proprietà è 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Ottiene un oggetto di configurazione della pagina utilizzato per la configurazione dell'output del set di pagine. |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) Ottiene un oggetto [`TextOptions`](../../com.aspose.html.rendering.image/textoptions/) che viene utilizzato per la configurazione del rendering del testo. |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Imposta o ottiene la risoluzione verticale per le immagini di output e interne (utilizzate durante l'elaborazione dei filtri), in pixel per pollice. Per impostazione predefinita questa proprietà è 300 dpi. |

## Osservazioni

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Esempi

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
      // Prepara un percorso a un file HTML di origine
      String documentPath = Path.Combine(DataDir, "nature.html");

      // Prepara un percorso per il salvataggio del file convertito
      String savePath = Path.Combine(OutputDir, "nature-output-options.png");

      // Inizializza un documento HTML dal file
      using var document = new HTMLDocument(documentPath);

      // Inizializza ImageSaveOptions       
      var options = new ImageSaveOptions()
      {
        SmoothingMode = SmoothingMode.Default,
        HorizontalResolution = 100,
        VerticalResolution = 100,
        BackgroundColor = Color.Beige
      };

      // Converti HTML in PNG
      Converter.ConvertHTML(document, options, savePath);
```

### Vedi anche

* class [ImageRenderingOptions](../../com.aspose.html.rendering.image/imagerenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
