---
title: "Clase XpsSaveOptions"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.saving.XpsSaveOptions. La clase de datos de opciones específicas proporciona algunas propiedades para gestionar el resultado de la conversión. Por ejemplo, PageSetup especifica las características de la página. Consulta el artículo de documentación."
type: docs

url: /es/java/com.aspose.html.saving/xpssaveoptions/
---
## XpsSaveOptions class

La clase de datos de opciones específicas proporciona algunas propiedades para gestionar el resultado de la conversión. Por ejemplo, [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) especifica las características de la página. Consulta la documentación [artículo](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#save-options).

```java
public class XpsSaveOptions : XpsRenderingOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) Obtiene un objeto [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) que se usa para la configuración del procesamiento de propiedades css. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | Establece o obtiene la resolución horizontal para imágenes internas (que se usan durante el procesamiento de filtros), en píxeles por pulgada. Por defecto, esta propiedad es 300 dpi. |
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
	  String documentPath = Path.Combine(OutputDir, "save-options.html");
      String savePath = Path.Combine(OutputDir, "save-options-output.xps");

      // Prepara código HTML y guárdalo en un archivo
      var code = "<h1> XpsSaveOptions Class</h1>\r\n" +
            "<p>Using XpsSaveOptions Class, you can programmatically apply a wide range of conversion parameters such as BackgroundColor, PageSetup, etc.</p>\r\n";

      File.WriteAllText(documentPath, code);

      // Inicializa un Documento HTML desde el archivo html
      using var document = new HTMLDocument(documentPath);
       
      // Configura el tamaño de página, los márgenes y cambia el color de fondo a AntiqueWhite
      var options = new XpsSaveOptions()
      {
        BackgroundColor = Color.AntiqueWhite
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(Length.FromInches(4.9f), Length.FromInches(3.5f)), new Margin(30, 20, 10, 10));

      // Convertir HTML a XPS
      Converter.ConvertHTML(document, options, savePath); 
```

### Ver también

* class [XpsRenderingOptions](../../com.aspose.html.rendering.xps/xpsrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
