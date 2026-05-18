---
title: "ImageRenderingOptions Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.rendering.image.ImageRenderingOptions Klasse. Stellt Rendering-Optionen für ImageDevice dar. Diese Optionen werden verwendet, um Ausgabeformat, Kompression, Auflösung usw. anzugeben."
type: docs

url: /de/java/com.aspose.html.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

Stellt Rendering-Optionen für [`ImageDevice`](../imagedevice/) dar. Diese Optionen werden verwendet, um Ausgabeformat, Kompression, Auflösung usw. anzugeben.

```java
public class ImageRenderingOptions : RenderingOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | Initialisiert eine neue Instanz der `ImageRenderingOptions`-Klasse; PNG wird als Standardbildformat verwendet. |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(ImageFormat) | Initialisiert eine neue Instanz der `ImageRenderingOptions`-Klasse mit dem angegebenen Bildformat. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Gibt ein [`CssOptions`](../../com.aspose.html.rendering/cssoptions/)‑Objekt zurück, das für die Konfiguration der Verarbeitung von CSS‑Eigenschaften verwendet wird. |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Setzt oder liest die horizontale Auflösung für Ausgabe- und interne (die bei der Filterverarbeitung verwendet werden) Bilder, in Pixel pro Zoll. Standardmäßig ist diese Eigenschaft 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Gibt ein Seiten‑Setup‑Objekt zurück, das für die Konfiguration des Ausgabeseiten‑Sets verwendet wird. |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) Gibt ein [`TextOptions`](../textoptions/) Objekt zurück, das zur Konfiguration des Text-Renderings verwendet wird. |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Setzt oder liest die vertikale Auflösung für Ausgabe- und interne (die bei der Filterverarbeitung verwendet werden) Bilder, in Pixel pro Zoll. Standardmäßig ist diese Eigenschaft 300 dpi. |

### Siehe auch

* class [RenderingOptions](../../com.aspose.html.rendering/renderingoptions/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)
