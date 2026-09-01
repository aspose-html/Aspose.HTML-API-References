---
title: "Classe ImageRenderingOptions"
second_title: "Aspose.HTML per Java Riferimento API"
description: "classe com.aspose.html.rendering.image.ImageRenderingOptions. Rappresenta le opzioni di rendering per ImageDevice. Questa opzione è usata per specificare il formato dell'immagine di output, compressione, risoluzione, ecc."
type: docs

url: /it/java/com.aspose.html.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

Rappresenta le opzioni di rendering per [`ImageDevice`](../imagedevice/). Questa opzione è usata per specificare il formato dell'immagine di output, compressione, risoluzione, ecc.

```java
public class ImageRenderingOptions : RenderingOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | Inizializza una nuova istanza della classe `ImageRenderingOptions`; PNG verrà usato come formato immagine predefinito. |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(ImageFormat) | Inizializza una nuova istanza della classe `ImageRenderingOptions` con il formato immagine specificato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Ottiene un oggetto [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) che viene utilizzato per la configurazione dell'elaborazione delle proprietà CSS. |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Imposta o ottiene la risoluzione orizzontale per le immagini di output e interne (utilizzate durante l'elaborazione dei filtri), in pixel per pollice. Per impostazione predefinita questa proprietà è 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Ottiene un oggetto di configurazione della pagina utilizzato per la configurazione dell'output del set di pagine. |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) Ottiene un oggetto [`TextOptions`](../textoptions/) che è usato per la configurazione del rendering del testo. |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Imposta o ottiene la risoluzione verticale per le immagini di output e interne (utilizzate durante l'elaborazione dei filtri), in pixel per pollice. Per impostazione predefinita questa proprietà è 300 dpi. |

### Vedi anche

* class [RenderingOptions](../../com.aspose.html.rendering/renderingoptions/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)
