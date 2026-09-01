---
title: "ImageRenderingOptions-klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.rendering.image.ImageRenderingOptions-klasse. Vertegenwoordigt renderopties voor ImageDevice. Deze opties worden gebruikt om het uitvoerbeeldformaat, compressie, resolutie enz. te specificeren"
type: docs

url: /nl/java/com.aspose.html.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

Vertegenwoordigt renderopties voor [`ImageDevice`](../imagedevice/). Deze opties worden gebruikt om het uitvoerbeeldformaat, compressie, resolutie enz. te specificeren.

```java
public class ImageRenderingOptions : RenderingOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | Initialiseert een nieuw exemplaar van de `ImageRenderingOptions`-klasse; Png wordt gebruikt als standaardbeeldformaat. |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(ImageFormat) | Initialiseert een nieuw exemplaar van de `ImageRenderingOptions`-klasse met het opgegeven beeldformaat. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Haalt een [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) object op dat wordt gebruikt voor de configuratie van de verwerking van CSS‑eigenschappen. |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Stelt de horizontale resolutie in of haalt deze op voor uitvoer- en interne (die tijdens filterverwerking worden gebruikt) afbeeldingen, in pixels per inch. Standaard is deze eigenschap 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Haalt een paginainstellingsobject op dat wordt gebruikt voor de configuratie van de uitvoer‑pagina‑set. |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) Haalt een [`TextOptions`](../textoptions/) object op dat wordt gebruikt voor de configuratie van tekstrendering. |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Stelt de verticale resolutie in of haalt deze op voor uitvoer- en interne (die tijdens filterverwerking worden gebruikt) afbeeldingen, in pixels per inch. Standaard is deze eigenschap 300 dpi. |

### Zie ook

* class [RenderingOptions](../../com.aspose.html.rendering/renderingoptions/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)
