---
title: "HTMLSaveFormat Enumeración"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.saving.HTMLSaveFormat enumeración. Especifica el formato en el que se guarda el documento. Puedes encontrar más información sobre cómo guardar HTMLDocument en el artículo"
type: docs

url: /es/java/com.aspose.html.saving/htmlsaveformat/
---
## HTMLSaveFormat enumeration

Especifica el formato en el que se guarda el documento. Puedes encontrar más información sobre cómo guardar [`HTMLDocument`](../../com.aspose.html/htmldocument/) en [artículo](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```java
public enum HTMLSaveFormat
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Original | `0` | El documento se guardará en su formato original. |
| Markdown | `1` | El documento se guardará como Markdown. |
| MHTML | `2` | El documento se guardará como MHTML. |

## Observaciones

Puedes descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Ejemplos

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
  // Prepara una ruta de salida para guardar un documento
  String documentPath = Path.Combine(OutputDir, "save-to-MD.md");

  // Prepara código HTML
  var html_code = "<H2>Hello World!</H2>";
   
  // Inicializa un documento a partir de la variable String
  using (var document = new HTMLDocument(html_code, "."))
  {
    // Guarda el documento como un archivo Markdown
    document.Save(documentPath, HTMLSaveFormat.Markdown);
  }
```

*OutputDir - user output folder path.

### Ver también

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
