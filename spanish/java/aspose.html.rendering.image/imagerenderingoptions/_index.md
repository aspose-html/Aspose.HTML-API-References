---
title: "Clase ImageRenderingOptions"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.rendering.image.ImageRenderingOptions. Representa las opciones de renderizado para ImageDevice. Estas opciones se utilizan para especificar el formato de imagen de salida, compresión, resolución, etc."
type: docs

url: /es/java/com.aspose.html.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

Representa las opciones de renderizado para [`ImageDevice`](../imagedevice/). Estas opciones se utilizan para especificar el formato de imagen de salida, compresión, resolución, etc.

```java
public class ImageRenderingOptions : RenderingOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | Inicializa una nueva instancia de la clase `ImageRenderingOptions`; se usará PNG como formato de imagen predeterminado. |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(ImageFormat) | Inicializa una nueva instancia de la clase `ImageRenderingOptions` con el formato de imagen especificado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Obtiene un objeto [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) que se utiliza para la configuración del procesamiento de propiedades css. |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Establece o obtiene la resolución horizontal para imágenes de salida e internas (que se usan durante el procesamiento de filtros), en píxeles por pulgada. Por defecto, esta propiedad es 300 ppp. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Obtiene un objeto de configuración de página que se usa para la configuración de la salida del conjunto de páginas. |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) Obtiene un objeto [`TextOptions`](../textoptions/) que se utiliza para la configuración del renderizado de texto. |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Establece o obtiene la resolución vertical para imágenes de salida e internas (que se usan durante el procesamiento de filtros), en píxeles por pulgada. Por defecto, esta propiedad es 300 ppp. |

### Ver también

* class [RenderingOptions](../../com.aspose.html.rendering/renderingoptions/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)
