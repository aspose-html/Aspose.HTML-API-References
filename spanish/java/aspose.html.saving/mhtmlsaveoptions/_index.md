---
title: "Clase MHTMLSaveOptions"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.saving.MHTMLSaveOptions. Representa las opciones de guardado MHTML. Al asignar propiedades específicas puedes gestionar el procesamiento de recursos, como la profundidad máxima de manejo, entre otros. Más información en el artículo de documentación."
type: docs

url: /es/java/com.aspose.html.saving/mhtmlsaveoptions/
---
## MHTMLSaveOptions class

Representa opciones de guardado MHTML. Al asignar propiedades específicas puedes gestionar el procesamiento de recursos, como la profundidad máxima de manejo, entre otros. Más información en la documentación [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options).

```java
public class MHTMLSaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MHTMLSaveOptions](mhtmlsaveoptions/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Obtiene un objeto [`ResourceHandlingOptions`](../resourcehandlingoptions/) que se usa para la configuración del manejo de recursos. |

## Observaciones

Puedes encontrar ejemplos completos y archivos de datos en [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Ejemplos

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
import System.IO;
...
	 // Prepara código HTML con un enlace a otro archivo y guárdalo en el archivo como 'document.html'
      var code = "<span>Hello, World!!</span> " +
            "<a href='document2.html'>click</a>";
      File.WriteAllText("document.html", code);

      // Prepara código HTML y guárdalo en el archivo como 'document2.html'
      code = @"<span>Hello, World!!</span>";
      File.WriteAllText("document2.html", code);
       
      String savePath = Path.Combine(OutputDir, "output-options.mht");

      // Cambia el valor de la profundidad de enlace de recursos a 1 para convertir el documento con recursos vinculados directamente
      var options = new MHTMLSaveOptions()
      {
        ResourceHandlingOptions =
        {
          MaxHandlingDepth = 1
        }
      };

      // Convertir HTML a MHTML
      Converter.ConvertHTML("document.html", options, savePath);  
```

### Ver también

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
