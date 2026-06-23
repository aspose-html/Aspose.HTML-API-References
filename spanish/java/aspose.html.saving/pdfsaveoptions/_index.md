---
title: "Clase PdfSaveOptions"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.saving.PdfSaveOptions clase. Esta clase de datos específica proporciona algunas propiedades para gestionar el resultado de la conversión. Por ejemplo, PageSetup especifica las características de la página. Consulte el artículo de documentación."
type: docs

url: /es/java/com.aspose.html.saving/pdfsaveoptions/
---
## PdfSaveOptions class

Esta clase de datos específica proporciona algunas propiedades para gestionar el resultado de la conversión. Por ejemplo, [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) especifica las características de la página. Consulte la documentación [artículo](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions).

```java
public class PdfSaveOptions : PdfRenderingOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Obtiene un objeto [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) que se usa para la configuración del procesamiento de propiedades css. |
| [getDocumentInfo](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/documentinfo/) Contiene información sobre el documento PDF de salida. |
[getEncryption]
[setEncryption] Gets or sets a encryption details. If not set, then no encryption will be performed. |
[getFormFieldBehaviour]
[setFormFieldBehaviour] Specifies the behavior of form fields in the output PDF document. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Establece o obtiene la resolución horizontal para imágenes internas (que se usan durante el procesamiento de filtros), en píxeles por pulgada. Por defecto, esta propiedad es 300 dpi. |
[getIsTaggedPdf]
[setIsTaggedPdf] Creates a tag structure if `true`. |
[getJpegQuality]
[setJpegQuality] Specifies the quality of JPEG compression for images (if JPEG compression is used). Default is 95. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) Obtiene un objeto de configuración de página que se usa para la configuración de la salida del conjunto de páginas. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | Establece o obtiene la resolución vertical para imágenes internas (que se usan durante el procesamiento de filtros), en píxeles por pulgada. Por defecto, esta propiedad es 300 dpi. |

## Observaciones

Puedes encontrar ejemplos completos y archivos de datos en [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
...
 	 // Prepara una ruta a un archivo HTML fuente
      String documentPath = Path.Combine(DataDir, "drawing.html");

      // Prepare una ruta para guardar el archivo convertido
      String savePath = Path.Combine(OutputDir, "drawing-options.pdf");

      // Inicializa un documento HTML desde el archivo
      using var document = new HTMLDocument(documentPath);

      // Inicialice PdfSaveOptions. Configure el tamaño de página 600x300 píxeles, márgenes, 
      // resoluciones y cambie el color de fondo a AliceBlue 
      var options = new PdfSaveOptions()
      {         
        HorizontalResolution = 200,
        VerticalResolution = 200,
        BackgroundColor = Color.AliceBlue,
        JpegQuality = 100
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 300), new Margin(20, 10, 10, 10));      

      // Convertir HTML a PDF
      Converter.ConvertHTML(document, options, savePath);
```

### Ver también

* class [PdfRenderingOptions](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
