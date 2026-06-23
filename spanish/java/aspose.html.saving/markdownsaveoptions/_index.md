---
title: "Clase MarkdownSaveOptions"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.saving.MarkdownSaveOptions. Representa las opciones de guardado Markdown. Por ejemplo, puedes establecer el estilo de formato markdown usando opciones compatibles predefinidas de GitLab Flavored Markdown y configurar el manejo de recursos. Consulta más información en el artículo."
type: docs

url: /es/java/com.aspose.html.saving/markdownsaveoptions/
---
## MarkdownSaveOptions class

Representa opciones de guardado Markdown. Por ejemplo, puedes establecer el estilo de formato markdown, usar opciones compatibles predefinidas de GitLab Flavored Markdown y configurar el manejo de recursos. Consulta más información en [artículo](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options).

```java
public class MarkdownSaveOptions : SaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | Inicializa una nueva instancia de la clase `MarkdownSaveOptions`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [getDefault](../../com.aspose.html.saving/markdownsaveoptions/default/) Devuelve un conjunto de opciones que son compatibles con la documentación Markdown predeterminada. |
| static [getGit](../../com.aspose.html.saving/markdownsaveoptions/git/) Devuelve un conjunto de opciones que son compatibles con GitLab Flavored Markdown. |
[getFeatures]
[setFeatures] Flag set that controls which elements are converted to markdown. |
[getFormatter]
[setFormatter] Gets or sets the markdown formatting style. |
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
	 // Prepare una ruta para guardar el archivo convertido
      String savePath = Path.Combine(OutputDir, "options-output.md");

      // Prepara código HTML y guárdalo en el archivo
      var code = "<h1>Header 1</h1>" +
            "<h2>Header 2</h2>" +
            "<p>Hello, World!!</p>" +
            "<a href='aspose.com'>aspose</a>";
      File.WriteAllText(Path.Combine(OutputDir, "options.html"), code);

      // Crea una instancia de SaveOptions y configura la regla: 
      // - solo los elementos <a> y <p> se convertirán a Markdown
      var options = new MarkdownSaveOptions();
      options.Features = MarkdownFeatures.Link | MarkdownFeatures.AutomaticParagraph;

      // Llama al método ConvertHTML para convertir el HTML a Markdown.
      Converter.ConvertHTML(Path.Combine(OutputDir, "options.html"), options, savePath);
```

### Ver también

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
