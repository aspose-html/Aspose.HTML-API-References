---
title: "Clase DocSaveOptions"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.saving.DocSaveOptions. Clase de datos de opciones específicas. Al asignar propiedades puedes gestionar características de renderizado como resolución, tamaño de página, color de fondo, así como opciones específicas del documento como la incrustación de fuentes. Más información en el artículo de documentación"
type: docs

url: /es/java/com.aspose.html.saving/docsaveoptions/
---
## DocSaveOptions class

Clase de datos de opciones específicas. Al asignar propiedades puedes gestionar características de renderizado como resolución, tamaño de página, color de fondo, así como opciones específicas del documento como la incrustación de fuentes. Más información en la documentación [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#save-options).

```java
public class DocSaveOptions : DocRenderingOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Obtiene un objeto [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) que se utiliza para la configuración del procesamiento de propiedades css. |
[getDocumentFormat]
[setDocumentFormat] Gets or sets the file format of the output document. The default value is DOCX. |
[getFontEmbeddingRule]
[setFontEmbeddingRule] Gets or sets the font embedding rule. The default value is None. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Establece o obtiene la resolución horizontal para imágenes internas (que se usan durante el procesamiento de filtros), en píxeles por pulgada. Por defecto, esta propiedad es 300 dpi. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Obtiene un objeto de configuración de página que se usa para la configuración de la salida del conjunto de páginas. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Establece o obtiene la resolución vertical para imágenes internas (que se usan durante el procesamiento de filtros), en píxeles por pulgada. Por defecto, esta propiedad es 300 dpi. |

## Observaciones

Puede descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.saving;
import System;
...
 // Prepara una ruta a un archivo HTML fuente
      String documentPath = Path.Combine(DataDir, "canvas.html");

      // Prepare una ruta para guardar el archivo convertido
      String savePath = Path.Combine(OutputDir, "canvas-output-options.docx");

      // Inicializa un documento HTML desde el archivo
      using var document = new HTMLDocument(documentPath);

      // Inicializa DocSaveOptions. Configura el tamaño de página 600x400 píxeles y los márgenes
      var options = new DocSaveOptions();
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 400), new Margin(10, 10, 10, 10));

      // Convertir HTML a DOCX
      Converter.ConvertHTML(document, options, savePath);
```

*OutputDir - custom output folder path.

### Ver también

* class [DocRenderingOptions](../../com.aspose.html.rendering.doc/docrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
