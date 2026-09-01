---
title: "HTMLDocument.Save"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método de HTMLDocument. Guarda el documento en un archivo local especificado por url. Todos los recursos usados en este documento se guardarán en una carpeta adyacente cuyo nombre se construirá como output_file_name _files."
type: docs

url: /es/java/com.aspose.html/htmldocument/save/
---
## Save(Url) {#save_5}

Guarda el documento en un archivo local especificado por url. Todos los recursos utilizados en este documento se guardarán en una carpeta adyacente, cuyo nombre se construirá como output_file_name + "_files".

```java
public void Save(Url url)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL local [`URL`](../../url/) al archivo de salida. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza si la `url` especificada no es una URL de archivo local válida. |

## Observaciones

Guardar HTML

La mayoría de las tareas que necesita realizar requieren guardar un documento. Una vez que cargue el archivo existente o cree un documento HTML desde cero, puede guardar sus cambios usando uno de los métodos HTMLDocument.Save(). Los métodos permiten guardar HTML en un archivo local especificado por ruta, URL o almacenamiento de salida. Consulte la [documentación](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) para obtener más información sobre el guardado.

Método Save(Url)

Es necesario especificar una ruta Url completa - 'outputFilePath' para guardar el documento HTML. El constructor Url(url) crea una instancia de la clase [`Url`](../../url/) con la url especificada. Luego debe pasar la instancia al método Save(Url). El documento se guardará en el archivo local especificado por url. Todos los recursos usados en este documento se guardarán en una carpeta adyacente, cuyo nombre se construirá como output_file_name + "_files".

Código fuente

Puedes descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Ejemplos

```java
import System;
import System.IO;
import Aspose.Html;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
        
	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(new Url(outputFilePath));
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### Ver también

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler) {#save}

Guarda el contenido del documento y los recursos usando el [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resourceHandler | ResourceHandler | El manejador de recursos [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |

### Ver también

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_10}

Guarda el documento en un archivo local especificado por la ruta. Todos los recursos utilizados en este documento se guardarán en una carpeta adyacente, cuyo nombre se construirá como: output_file_name + "_files".

```java
public void Save(String path)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | Cadena | Ruta del sistema de archivos local al archivo de salida. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza si la `path` especificada no es una ruta de archivo local válida. |

## Observaciones

Guardar HTML

La mayoría de las tareas que necesita realizar requieren guardar un documento. Una vez que cargue el archivo existente o cree un documento HTML desde cero, puede guardar sus cambios usando uno de los métodos HTMLDocument.Save(). Los métodos permiten guardar HTML en un archivo local especificado por ruta, URL o almacenamiento de salida. Consulte la [documentación](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) para obtener más información sobre el guardado.

El método Save(String) recibe como parámetro una ruta del sistema de archivos local a un archivo de salida y guarda un documento HTML en el archivo local especificado por la ruta. Todos los recursos usados en el documento se guardarán en una carpeta adyacente.

Código fuente

Puedes descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Ejemplos

```java
import System;
import System.IO;
import Aspose.Html;
...
 using (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (outputHtmlPath == null)
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(outputFilePath);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output directory path.

### Ver también

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveFormat) {#save_11}

Guarda el documento en un archivo local especificado por ruta. Todos los recursos utilizados en este documento se guardarán en una carpeta adyacente, cuyo nombre se construirá como output_file_name + "_files".

```java
public void Save(String path, HTMLSaveFormat saveFormat)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | Cadena | Ruta del archivo local al archivo de salida. |
| saveFormat | HTMLSaveFormat | Formato en el que se guarda el documento. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza si la `path` especificada no es una ruta de archivo local válida. |

## Observaciones

Guardar HTML

La mayoría de las tareas que necesita realizar requieren guardar un documento. Una vez que cargue el archivo existente o cree un documento HTML desde cero, puede guardar sus cambios usando uno de los métodos HTMLDocument.Save(). Los métodos permiten guardar HTML en un archivo local especificado por ruta, URL o almacenamiento de salida. Consulte la [documentación](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) para obtener más información sobre el guardado.

Save(String, HTMLSaveFormat) Método

Save(String, HTMLSaveFormat) método toma como parámetros una ruta del sistema de archivos local para el archivo de salida y saveFormat. La enumeración [`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) especifica el formato en el que se guarda el documento; puede ser HTML, MHTML y MD. El método guarda el documento HTML en el formato especificado en el archivo local indicado por la ruta. Todos los recursos utilizados en el documento se guardarán en una carpeta adyacente.

Código fuente

Puedes descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Ejemplos

```java
# HTML input file content
<!DOCTYPE html>
<html lang="en"
   xmlns:xml="http://www.w3.org/XML/1998/package">
<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="styles/main.css">
  <title>Title</title>
</head>
<body>
<div id="uniqueIdentifier">Container with ID - identifier</div>
<div class="custom-class">Customized by css class container</div>

<div>
  <p class="pStyle">First styled by pStyle class paragraph</p>
  <p class="pStyle">Second styled by pStyle class paragraph</p>
  <p class="pStyle">Third styled by pStyle class paragraph</p>
  <span class="pStyle">Span styled by pStyle</span>
</div>

<math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>...</mrow>
</math>

<div id="smart class">
  <p id="p1" class="ddd kkk">Paragraph styled by class name =ddd kkk=</p>
  <p id="p2" class="ddd fff">Paragraph styled by class name =ddd fff=</p>
  <p id="p3" class="kkk fff">Paragraph styled by class name =kkk fff=</p>
</div>

</body>
</html>

# C# code
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}
	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtml");
	document.Save(outputFilePath, HTMLSaveFormat.MHTML);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

# Content of result file

MIME-Version: 1.0

Content-Type: Multipart/related; boundary="boundary";type=Text/HTML

--boundary

Content-Type: text/html;

Content-Location: result.mhtml

&lt;!DOCTYPE html&gt;&lt;html lang="en" xmlns:xml="http://www.w3.org/XML/1998/package"&gt;&lt;head&gt;

&lt;meta charset="UTF-8"&gt;

&lt;link rel="stylesheet" href="main.css"&gt;

&lt;title&gt;Título&lt;/title&gt;

&lt;/head&gt;

&lt;body&gt;

&lt;div id="uniqueIdentifier"&gt;Contenedor con ID - identificador&lt;/div&gt;

&lt;div class="custom-class"&gt;Personalizado por la clase css contenedor&lt;/div&gt;

&lt;div&gt;

&lt;p class="pStyle"&gt;Primer párrafo estilizado por la clase pStyle&lt;/p&gt;

&lt;p class="pStyle"&gt;Segundo párrafo estilizado por la clase pStyle&lt;/p&gt;

&lt;p class="pStyle"&gt;Tercer párrafo estilizado por la clase pStyle&lt;/p&gt;

&lt;span class="pStyle"&gt;Span estilizado por pStyle&lt;/span&gt;

&lt;/div&gt;

&lt;math xmlns="http://www.w3.org/1998/Math/MathML"&gt;

&lt;mrow&gt;...&lt;/mrow&gt;

&lt;/math&gt;

&lt;div id="smart class"&gt;

&lt;p id=\"p1\" class=\"ddd kkk\"&gt;Párrafo con estilo por nombre de clase =ddd kkk=&lt;/p&gt;

&lt;p id=\"p2\" class=\"ddd fff\"&gt;Párrafo con estilo por nombre de clase =ddd fff=&lt;/p&gt;

&lt;p id=\"p3\" class=\"kkk fff\"&gt;Párrafo con estilo por nombre de clase =kkk fff=&lt;/p&gt;

&lt;/div&gt;

&lt;div&gt;Hola desde el elemento DIV&lt;/div&gt;&lt;/body&gt;&lt;/html&gt;

--boundary

Tipo de contenido: text/css;

Ubicación del contenido: main.css

.custom-class { color: yellow; background-color: blueviolet; margin-top: 10pt; margin-right: 10pt; margin-bottom: 10pt; margin-left: 10pt; }.pStyle { font-

--boundary--

### Ver también

* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveFormat) {#save_6}

Guarda el documento en un archivo local especificado por url. Todos los recursos utilizados en este documento se guardarán en una carpeta adyacente, cuyo nombre se construirá como output_file_name + "_files".

```java
public void Save(Url url, HTMLSaveFormat saveFormat)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL local al archivo de salida. |
| saveFormat | HTMLSaveFormat | Formato en el que se guarda el documento. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza si la `url` especificada no es una URL de archivo local válida. |

## Observaciones

Guardar HTML

La mayoría de las tareas que necesita realizar requieren guardar un documento. Una vez que cargue el archivo existente o cree un documento HTML desde cero, puede guardar sus cambios usando uno de los métodos HTMLDocument.Save(). Los métodos permiten guardar HTML en un archivo local especificado por ruta, URL o almacenamiento de salida. Consulte la [documentación](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) para obtener más información sobre el guardado.

Save(Url, HTMLSaveFormat) Método

Es necesario especificar una ruta Url completa - 'outputFilePath' para guardar el documento HTML. El constructor Url(url) crea una instancia de la clase [`Url`](../../url/) con la url especificada. La enumeración [`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) especifica el formato en el que se guarda el documento; puede ser HTML, MHTML y formatos MD. Luego debe pasar los parámetros al método Save(url, saveFormat). El documento se guardará en el formato especificado en el archivo local especificado por la url.

Código fuente

Puedes descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Ejemplos

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtml");
	document.Save(new Url(outputFilePath), HTMLSaveFormat.MHTML);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output directory path.

### Ver también

* class [Url](../../url/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveFormat) {#save_1}

Guarda el contenido del documento y los recursos usando el [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveFormat saveFormat)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resourceHandler | ResourceHandler | El manejador de recursos [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveFormat | HTMLSaveFormat | Formato en el que se guarda el documento. |

### Ver también

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveOptions) {#save_12}

Guarda el documento en un archivo local especificado por la ruta. Todos los recursos utilizados en este documento se guardarán en una carpeta adyacente, cuyo nombre se construirá como: output_file_name + "_files".

```java
public void Save(String path, HTMLSaveOptions saveOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | Cadena | Ruta local al archivo de salida. |
| saveOptions | HTMLSaveOptions | El objeto [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) es para la gestión del proceso de manejo de recursos. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza si la `path` especificada no es una ruta de archivo local válida. |

## Observaciones

Guardar HTML

La mayoría de las tareas que necesita realizar requieren guardar un documento. Una vez que cargue el archivo existente o cree un documento HTML desde cero, puede guardar sus cambios usando uno de los métodos HTMLDocument.Save(). Los métodos permiten guardar HTML en un archivo local especificado por ruta, URL o almacenamiento de salida. Consulte la [documentación](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) para obtener más información sobre el guardado.

Save(String, HTMLSaveOptions) Método

El método Save(String, HTMLSaveOptions) toma como parámetros una ruta del sistema de archivos local al archivo de salida, una instancia de la clase [HTMLSaveOptions](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) y guarda un documento HTML con recursos en el archivo local especificado por la ruta. El constructor HTMLSaveOptions() crea una instancia de opciones de guardado que tiene propiedades de [`ResourceHandlingOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) que se utilizan para la configuración del manejo de recursos. Todos los recursos utilizados en el documento se guardarán en una carpeta adyacente.

Código fuente

Puedes descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Ejemplos

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	// Definir instancia de clase de opciones
	var options = new HTMLSaveOptions();
	// Restricción de manejo de páginas
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Ver también

* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveOptions) {#save_7}

Guarda el documento en un archivo local especificado por url. Todos los recursos utilizados en este documento se guardarán en una carpeta adyacente, cuyo nombre se construirá como: output_file_name + "_files".

```java
public void Save(Url url, HTMLSaveOptions saveOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL local [`URL`](../../url/) al archivo de salida. |
| saveOptions | HTMLSaveOptions | El objeto [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) es para la gestión del proceso de manejo de recursos. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza si la `url` especificada no es una URL de archivo local válida. |

## Observaciones

Guardar HTML

La mayoría de las tareas que necesita realizar requieren guardar un documento. Una vez que cargue el archivo existente o cree un documento HTML desde cero, puede guardar sus cambios usando uno de los métodos HTMLDocument.Save(). Los métodos permiten guardar HTML en un archivo local especificado por ruta, URL o almacenamiento de salida. Consulte la [documentación](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) para obtener más información sobre el guardado.

Save(Url, HTMLSaveOptions) Método

Es necesario especificar una ruta Url completa para guardar el documento HTML. El constructor Url(url) crea una instancia de la clase [`Url`](../../url/) con la url especificada. El constructor HTMLSaveOptions() crea una instancia de la clase [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) que tiene propiedades de ResourceHandlingOptions que se utilizan para la configuración del manejo de recursos. El método Save(url, saveOptions) toma parámetros y guarda el documento HTML con recursos en el archivo local especificado por la url.

Código fuente

Puedes descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Ejemplos

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	// Definir instancia de clase de opciones
	var options = new HTMLSaveOptions();
	// Restricción de manejo de páginas
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Ver también

* class [Url](../../url/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveOptions) {#save_2}

Guarda el contenido del documento y los recursos usando el [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveOptions saveOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resourceHandler | ResourceHandler | El manejador de recursos [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | HTMLSaveOptions | Opciones de guardado HTML. |

### Ver también

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MarkdownSaveOptions) {#save_13}

Guarda el documento en un archivo local especificado por la ruta. Todos los recursos utilizados en este documento se guardarán en una carpeta adyacente, cuyo nombre se construirá como: output_file_name + "_files".

```java
public void Save(String path, MarkdownSaveOptions saveOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | Cadena | Ruta local al archivo de salida. |
| saveOptions | MarkdownSaveOptions | El uso del objeto [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [Documentación de Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options). |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza si la `path` especificada no es una ruta de archivo local válida. |

## Observaciones

Guardar HTML

La mayoría de las tareas que necesita realizar requieren guardar un documento. Una vez que cargue el archivo existente o cree un documento HTML desde cero, puede guardar sus cambios usando uno de los métodos HTMLDocument.Save(). Los métodos permiten guardar HTML en un archivo local especificado por ruta, URL o almacenamiento de salida. Consulte la [documentación](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) para obtener más información sobre el guardado.

Save(String, MarkdownSaveOptions) Método

Es necesario especificar una ruta del sistema de archivos local al archivo de salida para guardar el documento. El constructor MarkdownSaveOptions() crea una instancia de la clase [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) que tiene un conjunto de propiedades. Por ejemplo, puede establecer el estilo de formato markdown, usar opciones predefinidas compatibles con GitLab Flavored Markdown y configurar el manejo de recursos. El método Save(path, saveOptions) toma la ruta del sistema de archivos local al archivo de salida y la instancia de opciones como parámetros y guarda el HTML como un documento Markdown con recursos en el archivo local especificado por la ruta.

Código fuente

Puedes descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Ejemplos

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
     
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.md");
	// Definir instancia de clase de opciones
	var options = new MarkdownSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### Ver también

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MarkdownSaveOptions) {#save_8}

Guarda el documento en un archivo local especificado por url. Todos los recursos utilizados en este documento se guardarán en una carpeta adyacente, cuyo nombre se construirá como: output_file_name + "_files".

```java
public void Save(Url url, MarkdownSaveOptions saveOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL local [`URL`](../../url/) al archivo de salida. |
| saveOptions | MarkdownSaveOptions | El uso del objeto [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [documentación](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options). |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza si la `url` especificada no es una URL de archivo local válida. |

## Observaciones

Guardar HTML

La mayoría de las tareas que necesita realizar requieren guardar un documento. Una vez que cargue el archivo existente o cree un documento HTML desde cero, puede guardar sus cambios usando uno de los métodos HTMLDocument.Save(). Los métodos permiten guardar HTML en un archivo local especificado por ruta, URL o almacenamiento de salida. Consulte la [documentación](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) para obtener más información sobre el guardado.

Save(Url, MarkdownSaveOptions) Método

Es necesario especificar una ruta Url completa para guardar el documento. El constructor Url(url) crea una instancia de la clase [`Url`](../../url/) con la url especificada. El constructor MarkdownSaveOptions() crea una instancia de la clase [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) que tiene un conjunto de propiedades. Por ejemplo, puede establecer el estilo de formato Markdown, usar opciones predefinidas compatibles con GitLab Flavored Markdown y configurar el manejo de recursos. El método Save(url, saveOptions) toma la url y las instancias de opciones de guardado como parámetros y guarda el documento con recursos en el archivo local especificado por la url.

Código fuente

Puedes descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Ejemplos

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.md");
	// Definir instancia de clase de opciones
	var options = new MarkdownSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Ver también

* class [Url](../../url/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MarkdownSaveOptions) {#save_3}

Guarda el contenido del documento y los recursos usando el [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, MarkdownSaveOptions saveOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resourceHandler | ResourceHandler | El manejador de recursos [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MarkdownSaveOptions | Opciones de guardado Markdown. |

### Ver también

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MHTMLSaveOptions) {#save_14}

Guarda el documento en un archivo local especificado por la ruta. Todos los recursos utilizados en este documento se guardarán en una carpeta adyacente, cuyo nombre se construirá como: output_file_name + "_files".

```java
public void Save(String path, MHTMLSaveOptions saveOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | Cadena | Ruta local al archivo de salida. |
| saveOptions | MHTMLSaveOptions | El uso del objeto [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [documentación](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options). |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza si la `path` especificada no es una ruta de archivo local válida. |

## Observaciones

Guardar HTML

La mayoría de las tareas que necesita realizar requieren guardar un documento. Una vez que cargue el archivo existente o cree un documento HTML desde cero, puede guardar sus cambios usando uno de los métodos HTMLDocument.Save(). Los métodos permiten guardar HTML en un archivo local especificado por ruta, URL o almacenamiento de salida. Consulte la [documentación](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) para obtener más información sobre el guardado.

Save(String, MHTMLSaveOptions) Método

Es necesario especificar una ruta del sistema de archivos local para el archivo de salida al guardar el documento. El constructor MHTMLSaveOptions() inicializa una instancia de la clase [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) que tiene la propiedad ResourceHandlingOptions, la cual se utiliza para la configuración del manejo de recursos. El método Save(path, saveOptions) toma una ruta del sistema de archivos local para el archivo de salida y una instancia de opciones de guardado como parámetros y guarda el HTML como un documento MHTML en el archivo local especificado por path.

Código fuente

Puedes descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Ejemplos

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtm");
	// Definir instancia de clase de opciones
	var options = new MHTMLSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Ver también

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MHTMLSaveOptions) {#save_9}

Guarda el documento en un archivo local especificado por url. Todos los recursos utilizados en este documento se guardarán en una carpeta adyacente, cuyo nombre se construirá como: output_file_name + "_files".

```java
public void Save(Url url, MHTMLSaveOptions saveOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | URL local al archivo de salida. |
| saveOptions | MHTMLSaveOptions | El uso del objeto [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) le permite ajustar el proceso de renderizado. Para más información, consulte la [documentación](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options). |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza si la `url` especificada no es una URL de archivo local válida. |

## Observaciones

Guardar HTML

La mayoría de las tareas que necesita realizar requieren guardar un documento. Una vez que cargue el archivo existente o cree un documento HTML desde cero, puede guardar sus cambios usando uno de los métodos HTMLDocument.Save(). Los métodos permiten guardar HTML en un archivo local especificado por ruta, URL o almacenamiento de salida. Consulte la [documentación](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) para obtener más información sobre el guardado.

Save(Url, MHTMLSaveOptions) Método

Es necesario especificar una ruta Url completa para guardar el documento. El constructor Url(url) crea una instancia de la clase [`Url`](../../url/) con la url especificada. El constructor MHTMLSaveOptions() inicializa una instancia de la clase [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) que tiene la propiedad ResourceHandlingOptions, la cual se utiliza para la configuración del manejo de recursos. El método Save(url, saveOptions) toma la url y las opciones como parámetros y guarda el HTML como un documento MHTML en el archivo local especificado por url.

Código fuente

Puedes descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Ejemplos

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtm");
	// Definir instancia de clase de opciones
	var options = new MHTMLSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input file path.

*outputHtmlPath - user output folder path.

### Ver también

* class [Url](../../url/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MHTMLSaveOptions) {#save_4}

Guarda el contenido del documento y los recursos usando el [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, MHTMLSaveOptions saveOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resourceHandler | ResourceHandler | El manejador de recursos [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MHTMLSaveOptions | Opciones de guardado MHTML. |

### Ver también

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
