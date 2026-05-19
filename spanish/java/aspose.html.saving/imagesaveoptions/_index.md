---
title: "Clase ImageSaveOptions"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.saving.ImageSaveOptions. Clase de datos de opciones específicas. Proporciona propiedades para gestionar la resolución del resultado de la imagen, suavizado, calidad, formato, así como la configuración de página, etc. Puede obtener más información en el artículo de documentación."
type: docs

url: /es/java/com.aspose.html.saving/imagesaveoptions/
---
## ImageSaveOptions class

Clase de datos de opciones específicas. Proporciona propiedades para gestionar la resolución del resultado de la imagen, la calidad de suavizado, el formato, así como la configuración de página, etc. Puedes obtener más información en la documentación [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#save-options).

```java
public class ImageSaveOptions : ImageRenderingOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/#constructor)() | Inicializa una nueva instancia de la clase `ImageSaveOptions`; Png se usará como formato de imagen predeterminado. |
| [ImageSaveOptions](imagesaveoptions/#constructor_1)(ImageFormat) | Formato de imagen [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/) basado en la inicialización |

## Propiedades

| Nombre | Descripción |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../../com.aspose.html.rendering.image/compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Obtiene un objeto [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) que se utiliza para la configuración del procesamiento de propiedades css. |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | Establece o obtiene la resolución horizontal para imágenes de salida e internas (que se usan durante el procesamiento de filtros), en píxeles por pulgada. Por defecto, esta propiedad es 300 ppp. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Obtiene un objeto de configuración de página que se usa para la configuración de la salida del conjunto de páginas. |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) Obtiene un objeto [`TextOptions`](../../com.aspose.html.rendering.image/textoptions/) que se usa para la configuración del renderizado de texto. |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | Establece o obtiene la resolución vertical para imágenes de salida e internas (que se usan durante el procesamiento de filtros), en píxeles por pulgada. Por defecto, esta propiedad es 300 ppp. |

## Observaciones

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
      // Prepara una ruta a un archivo HTML fuente
      String documentPath = Path.Combine(DataDir, "nature.html");

      // Prepare una ruta para guardar el archivo convertido
      String savePath = Path.Combine(OutputDir, "nature-output-options.png");

      // Inicializa un documento HTML desde el archivo
      using var document = new HTMLDocument(documentPath);

      // Inicialice ImageSaveOptions       
      var options = new ImageSaveOptions()
      {
        SmoothingMode = SmoothingMode.Default,
        HorizontalResolution = 100,
        VerticalResolution = 100,
        BackgroundColor = Color.Beige
      };

      // Convertir HTML a PNG
      Converter.ConvertHTML(document, options, savePath);
```

### Ver también

* class [ImageRenderingOptions](../../com.aspose.html.rendering.image/imagerenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
