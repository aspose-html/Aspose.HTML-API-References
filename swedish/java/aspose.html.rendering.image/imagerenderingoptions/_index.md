---
title: "Klassen ImageRenderingOptions"
second_title: "Aspose.HTML för Java API-referens"
description: "klassen com.aspose.html.rendering.image.ImageRenderingOptions. Representerar renderingsalternativ för ImageDevice. Detta alternativ används för att ange utdataformat, komprimering, upplösning etc."
type: docs

url: /sv/java/com.aspose.html.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

Representerar renderingsalternativ för [`ImageDevice`](../imagedevice/). Detta alternativ används för att ange utdataformat, komprimering, upplösning etc.

```java
public class ImageRenderingOptions : RenderingOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | Initierar en ny instans av klassen `ImageRenderingOptions`; Png kommer att användas som standardbildformat. |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(ImageFormat) | Initierar en ny instans av klassen `ImageRenderingOptions` med angivet bildformat. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Hämtar ett [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) objekt som används för konfiguration av bearbetning av css-egenskaper. |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Ställer in eller hämtar horisontell upplösning för utdata- och interna (som används under filterbehandling) bilder, i pixlar per tum. Som standard är denna egenskap 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Hämtar ett sidinställningsobjekt som används för konfiguration av utdata siduppsättning. |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) Hämtar ett [`TextOptions`](../textoptions/)‑objekt som används för konfiguration av textrendering. |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Ställer in eller hämtar vertikal upplösning för utdata- och interna (som används under filterbehandling) bilder, i pixlar per tum. Som standard är denna egenskap 300 dpi. |

### Se även

* class [RenderingOptions](../../com.aspose.html.rendering/renderingoptions/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)
