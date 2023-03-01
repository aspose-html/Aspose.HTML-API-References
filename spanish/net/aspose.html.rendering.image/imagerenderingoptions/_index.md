---
title: Class ImageRenderingOptions
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Rendering.Image.ImageRenderingOptions clase. Representa las opciones de representación paraImageDevice . Esta opción se utiliza para especificar el formato de la imagen de salida la compresión la resolución etc.
type: docs
weight: 4330
url: /es/net/aspose.html.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

Representa las opciones de representación para[`ImageDevice`](../imagedevice/) . Esta opción se utiliza para especificar el formato de la imagen de salida, la compresión, la resolución, etc.

```csharp
public class ImageRenderingOptions : RenderingOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | Inicializa una nueva instancia del`ImageRenderingOptions` clase;Png se utilizará como formato de imagen predeterminado. |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(ImageFormat) | Inicializa una nueva instancia del`ImageRenderingOptions` clase con formato de imagen especificado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BackgroundColor](../../aspose.html.rendering/renderingoptions/backgroundcolor/) { get; set; } | Obtiene o estableceColorque llenará el fondo de cada página. El valor predeterminado esTransparent . |
| [Compression](../../aspose.html.rendering.image/imagerenderingoptions/compression/) { get; set; } | Establece u obtiene el formato de archivo de imagen etiquetado (TIFF)[`Compression`](../compression/) . Por defecto esta propiedad esLZW . |
| [Css](../../aspose.html.rendering/renderingoptions/css/) { get; } | Obtiene un[`CssOptions`](../../aspose.html.rendering/cssoptions/) objeto que se utiliza para la configuración del procesamiento de propiedades css. |
| [Format](../../aspose.html.rendering.image/imagerenderingoptions/format/) { get; set; } | Establece o obtiene[`ImageFormat`](../imageformat/) . Por defecto esta propiedad esPng . |
| override [HorizontalResolution](../../aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Establece u obtiene la resolución horizontal para imágenes de salida e internas (que se utilizan durante el procesamiento de filtros), en píxeles por pulgada. Por defecto esta propiedad es 300 dpi. |
| [PageSetup](../../aspose.html.rendering/renderingoptions/pagesetup/) { get; } | Obtiene un objeto de configuración de página que se utiliza para configurar el conjunto de páginas de salida. |
| [SmoothingMode](../../aspose.html.rendering.image/imagerenderingoptions/smoothingmode/) { get; set; } | Obtiene o establece la calidad de representación de este Graphics. |
| [Text](../../aspose.html.rendering.image/imagerenderingoptions/text/) { get; } | Obtiene un[`TextOptions`](../textoptions/) objeto que se utiliza para la configuración de la representación de texto. |
| override [VerticalResolution](../../aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Establece u obtiene la resolución vertical para imágenes de salida e internas (que se utilizan durante el procesamiento de filtros), en píxeles por pulgada. Por defecto esta propiedad es 300 dpi. |

### Ver también

* class [RenderingOptions](../../aspose.html.rendering/renderingoptions/)
* espacio de nombres [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image/)
* asamblea [Aspose.HTML](../../)


