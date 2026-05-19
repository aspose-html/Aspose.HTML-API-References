---
title: "Clase HTMLSaveOptions"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.saving.HTMLSaveOptions class. Representa opciones de guardado HTML. Asignando propiedades específicas puedes gestionar el procesamiento de recursos, como la profundidad máxima de manejo, entre otros. Más información en el artículo de documentación"
type: docs

url: /es/java/com.aspose.html.saving/htmlsaveoptions/
---
## HTMLSaveOptions class

Representa opciones de guardado HTML. Al asignar propiedades específicas puedes gestionar el procesamiento de recursos, como la profundidad máxima de manejo, entre otros. Más información en la documentación [article](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```java
public class HTMLSaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [HTMLSaveOptions](htmlsaveoptions/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
[getDocumentType]
[setDocumentType] Gets or sets the output document type. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) Obtiene un objeto [`ResourceHandlingOptions`](../resourcehandlingoptions/) que se usa para la configuración del manejo de recursos. |
[getSerializeInputValue]
[setSerializeInputValue] This option controls whether to serialize the value of the [`HTMLInputElement`](../../com.aspose.html/htmlinputelement/)'s or the [`HTMLTextAreaElement`](../../com.aspose.html/htmltextareaelement/)'s "value" property into the "value" attribute. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [AUTO](../../com.aspose.html.saving/htmlsaveoptions/auto/) | El tipo de documento de salida se seleccionará automáticamente. |
| const [HTML](../../com.aspose.html.saving/htmlsaveoptions/html/) | El documento se guardará como HTML. |
| const [XHTML](../../com.aspose.html.saving/htmlsaveoptions/xhtml/) | El documento se guardará como XHTML. |

## Observaciones

Puedes descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Ejemplos

```java
import Aspose.Html;
import com.aspose.html.dom.svg;
import com.aspose.html.saving;
import System;
...
     // Prepara una ruta de salida para un documento HTML
      String documentPath = Path.Combine(OutputDir, "save-with-linked-file.html");

      // Prepara un archivo HTML sencillo con un documento enlazado
      File.WriteAllText(documentPath, "<p>Hello World!</p>" +
                      "<a href='linked.html'>linked file</a>");

      // Prepara un archivo HTML enlazado sencillo
      File.WriteAllText(Path.Combine(OutputDir, "linked.html"), "<p>Hello linked file!</p>");

      // Carga el "save-with-linked-file.html" en memoria
      using (var document = new HTMLDocument(documentPath))
      {
        // Crea una instancia de opciones de guardado
        var options = new HTMLSaveOptions();

        // La siguiente línea con valor '0' corta todos los demás archivos HTML vinculados al guardar esta instancia
        // Si eliminas esta línea o cambias el valor a '1', el archivo 'linked.html' también se guardará en la carpeta de salida
        options.ResourceHandlingOptions.MaxHandlingDepth = 1;

        // Guarda el documento con las opciones de guardado
        document.Save(Path.Combine(OutputDir, "save-with-linked-file_out.html"), options);
      }
```

*OutputDir - user output folder.

### Ver también

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
