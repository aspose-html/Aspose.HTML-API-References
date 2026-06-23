---
title: "HTMLDocument"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Constructor HTMLDocument. El constructor HTMLDocument crea un nuevo objeto HTML Document que es una página web cargada en el navegador y sirve como punto de entrada al contenido de la página."
type: docs

url: /es/java/com.aspose.html/htmldocument/htmldocument/
---
## HTMLDocument() {#constructor}

El constructor de HTMLDocument crea un nuevo objeto HTML Document que es una página web cargada en el navegador y que sirve como punto de entrada al contenido de la página.

```java
public HTMLDocument()
```

## Observaciones

Nota: El documento se crea con un valor predeterminado para la propiedad base-url que es igual a 'about:blank'.

Referencia:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Ejemplos

Una vez creado el objeto documento, puede rellenarse posteriormente con elementos HTML. El siguiente fragmento de código muestra el uso del constructor predeterminado HTMLDocument() para crear un documento HTML vacío y guardarlo en un archivo.

```java
import (var document = new HTMLDocument())
{
	// Trabaje con el documento aquí
	...	
	
	// Guarde el documento en un archivo
	document.Save("document.html");
}
```

### Ver también

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Configuration) {#constructor_1}

El constructor de HTMLDocument crea un nuevo objeto HTML Document que es una página web cargada en el navegador y que sirve como punto de entrada al contenido de la página.

```java
public HTMLDocument(Configuration configuration)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| configuración | Configuración | La configuración del entorno, como la política de scripts, la hoja de estilo de usuario personalizada, etc. |

## Observaciones

Nota: El documento se crea con un valor predeterminado para la propiedad base-url que es igual a 'about:blank'.

Referencia:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Ejemplos

El siguiente ejemplo demuestra cómo usar el objeto de configuración para desactivar scripts:

```java
// Prepara código HTML y guárdalo en un archivo
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Crea una instancia de Configuration
import (var configuration = new Configuration())
{
	// Marca 'scripts' como un recurso no confiable
	configuration.Security |= Sandbox.Scripts;

	// Inicializa un documento HTML con la configuración especificada
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// Convertir HTML a PDF
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### Ver también

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url) {#constructor_4}

Carga el documento HTML desde una URL.

Nota: En caso de que proporcione una URL incorrecta que no pueda alcanzarse en este momento, la biblioteca lanza la [`DOMException`](../../../com.aspose.html.dom/domexception/) con el código especializado ‘NetworkError’ para informarle que el recurso seleccionado no se puede encontrar.

```java
public HTMLDocument(Url url)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | La URL del documento HTML a abrir. |

## Observaciones

Referencia:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Ejemplos

Cargue un documento desde la página web 'https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html':

```java
import (var document = new HTMLDocument("https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html"))
{
	// Escriba el contenido del documento en el flujo de salida
	Console.WriteLine(document.DocumentElement.OuterHTML);
}
```

### Ver también

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url, Configuration) {#constructor_5}

Carga el documento HTML desde una URL con la configuración de entorno especificada.

Nota: En caso de que proporcione una URL incorrecta que no pueda alcanzarse en este momento, la biblioteca lanza la [DOMException](T:com.aspose.html.dom.DOMException) con el código especializado ‘NetworkError’ para informarle que el recurso seleccionado no se puede encontrar.

```java
public HTMLDocument(Url url, Configuration configuration)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | Url | La URL del documento HTML a abrir. |
| configuración | Configuración | La configuración del entorno, como la política de scripts, la hoja de estilo de usuario personalizada, etc. |

## Observaciones

Referencia:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Ejemplos

```java
The following example demonstrates how to use the configuration object to disable scripts:

// Prepara código HTML y guárdalo en un archivo
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Crea una instancia de Configuration
import (var configuration = new Configuration())
{
	// Marca 'scripts' como un recurso no confiable
	configuration.Security |= Sandbox.Scripts;

	// Inicializa un documento HTML con la configuración especificada
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// Convertir HTML a PDF
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### Ver también

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String) {#constructor_10}

Carga el documento HTML desde una dirección.

Nota: En caso de que proporcione una URL incorrecta que no pueda alcanzarse en este momento, la biblioteca lanza la [`DOMException`](../../../com.aspose.html.dom/domexception/) con el código especializado ‘NetworkError’ para informarle que el recurso seleccionado no se puede encontrar.

```java
public HTMLDocument(String address)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dirección | Cadena | La dirección del documento HTML a abrir. |

## Observaciones

Referencia:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Ejemplos

Inicialice un documento HTML a partir de una dirección.

```java
import (var document = new HTMLDocument("./my-folder/document.html")))
{
	...
}
```

### Ver también

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Configuration) {#constructor_11}

Carga el documento HTML desde una dirección con la configuración de entorno especificada.

Nota: En caso de que proporcione una URL incorrecta que no pueda alcanzarse en este momento, la biblioteca lanza la [`DOMException`](../../../com.aspose.html.dom/domexception/) con el código especializado ‘NetworkError’ para informarle que el recurso seleccionado no se puede encontrar.

```java
public HTMLDocument(String address, Configuration configuration)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dirección | Cadena | La dirección del documento HTML a abrir. |
| configuración | Configuración | La configuración del entorno, como la política de scripts, la hoja de estilo de usuario personalizada, etc. |

## Observaciones

Referencia:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Ejemplos

```java
// Crea una instancia de Configuration
import (var configuration = new Configuration())
{
	// Marca 'scripts' como un recurso no confiable
	configuration.Security |= Sandbox.Scripts;
	
	using (var document = new HTMLDocument("./my-folder/document.html", configuration)))
	{
		...
	}
}
```

### Ver también

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String) {#constructor_14}

Crea un documento HTML a partir de un contenido String con la base‑uri especificada.

```java
public HTMLDocument(String content, String baseUri)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | El contenido String con el que cargar el documento. |
| baseUri | Cadena | El URI base del documento. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanza una excepción si el parámetro base-uri es nulo. |

## Observaciones

Referencia:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Ejemplos

```java
// Prepare código HTML
var html_code = "<p>Hello World!</p>";

// Inicialice un documento a partir de la variable String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Ver también

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String, Configuration) {#constructor_15}

Crea un documento HTML a partir de un contenido String con la base‑uri y la configuración de entorno especificadas.

```java
public HTMLDocument(String content, String baseUri, Configuration configuration)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | El contenido String con el que cargar el documento. |
| baseUri | Cadena | El URI base del documento. |
| configuración | Configuración | La configuración del entorno, como la política de scripts, la hoja de estilo de usuario personalizada, etc. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanza una excepción si el parámetro base-uri es nulo. |

## Observaciones

Referencia:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Ejemplos

```java
// Prepare código HTML
var html_code = "<p>Hello World!</p>";

// Inicialice un documento a partir de la variable String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Ver también

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url) {#constructor_12}

Crea un documento HTML a partir de un contenido String con la base‑uri especificada.

```java
public HTMLDocument(String content, Url baseUri)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | El contenido String con el que cargar el documento. |
| baseUri | Url | El URI base del documento. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanza una excepción si el parámetro base-uri es nulo. |

## Observaciones

Referencia:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Ejemplos

```java
// Prepare código HTML
var html_code = "<p>Hello World!</p>";

// Inicialice un documento a partir de la variable String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Ver también

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url, Configuration) {#constructor_13}

Crea un documento HTML a partir de un contenido String con la base‑uri y la configuración de entorno especificadas.

```java
public HTMLDocument(String content, Url baseUri, Configuration configuration)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contenido | Cadena | El contenido String con el que cargar el documento. |
| baseUri | Url | El URI base del documento. |
| configuración | Configuración | La configuración del entorno, como la política de scripts, la hoja de estilo de usuario personalizada, etc. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanza una excepción si el parámetro base-uri es nulo. |

## Observaciones

Referencia:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Ejemplos

```java
// Prepare código HTML
var html_code = "<p>Hello World!</p>";

// Inicialice un documento a partir de la variable String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Ver también

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String) {#constructor_8}

Crea un documento HTML a partir del contenido de un [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) con la base‑uri especificada que se utiliza para resolver la ruta de los recursos relativos.

```java
public HTMLDocument(Stream content, String baseUri)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| content | Stream | El contenido del [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) con el que cargar el documento. |
| baseUri | Cadena | El URI base del documento. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanza una excepción si el parámetro base-uri es nulo. |

## Observaciones

Referencia:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Ejemplos

```java
// Cree un objeto de flujo de memoria
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Escriba el código HTML en el objeto de memoria
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Es importante establecer la posición al principio ya que HTMLDocument comienza la lectura exactamente desde la posición actual dentro del flujo
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Inicialice un documento a partir de la variable String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Guarde el documento en un disco
		document.Save("load-from-stream.html");
	}
}
```

### Ver también

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String, Configuration) {#constructor_9}

Crea un documento HTML a partir del contenido de un [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) con la base‑uri y la configuración de entorno especificadas.

```java
public HTMLDocument(Stream content, String baseUri, Configuration configuration)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| content | Stream | El contenido del [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) con el que cargar el documento. |
| baseUri | Cadena | El URI base del documento. |
| configuración | Configuración | La configuración del entorno, como la política de scripts, la hoja de estilo de usuario personalizada, etc. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanza una excepción si el parámetro base-uri es nulo. |

## Observaciones

Referencia:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Ejemplos

```java
// Cree un objeto de flujo de memoria
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Escriba el código HTML en el objeto de memoria
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Es importante establecer la posición al principio ya que HTMLDocument comienza la lectura exactamente desde la posición actual dentro del flujo
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Inicialice un documento a partir de la variable String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Guarde el documento en un disco
		document.Save("load-from-stream.html");
	}
}
```

### Ver también

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url) {#constructor_6}

Crea un documento HTML a partir del contenido de un [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) con la base‑uri especificada que se utiliza para resolver la ruta de los recursos relativos.

```java
public HTMLDocument(Stream content, Url baseUri)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| content | Stream | El contenido del [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) con el que cargar el documento. |
| baseUri | Url | El URI base del documento. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanza una excepción si el parámetro base-uri es nulo. |

## Observaciones

Referencia:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Ejemplos

```java
// Cree un objeto de flujo de memoria
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Escriba el código HTML en el objeto de memoria
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Es importante establecer la posición al principio ya que HTMLDocument comienza la lectura exactamente desde la posición actual dentro del flujo
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Inicialice un documento a partir de la variable String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Guarde el documento en un disco
		document.Save("load-from-stream.html");
	}
}
```

### Ver también

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url, Configuration) {#constructor_7}

Crea un documento HTML a partir del contenido de un [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) con la base‑uri y la configuración de entorno especificadas.

```java
public HTMLDocument(Stream content, Url baseUri, Configuration configuration)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| content | Stream | El contenido del [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) con el que cargar el documento. |
| baseUri | Url | El URI base del documento. |
| configuración | Configuración | La configuración del entorno, como la política de scripts, la hoja de estilo de usuario personalizada, etc. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanza una excepción si el parámetro base-uri es nulo. |

## Observaciones

Referencia:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Ejemplos

```java
// Cree un objeto de flujo de memoria
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Escriba el código HTML en el objeto de memoria
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Es importante establecer la posición al principio ya que HTMLDocument comienza la lectura exactamente desde la posición actual dentro del flujo
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Inicialice un documento a partir de la variable String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Guarde el documento en un disco
		document.Save("load-from-stream.html");
	}
}
```

### Ver también

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage) {#constructor_2}

Crea un documento HTML a partir del objeto [`RequestMessage`](../../../com.aspose.html.net/requestmessage/).

```java
public HTMLDocument(RequestMessage request)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| request | RequestMessage | El mensaje de solicitud que contiene un [`body`](../../../com.aspose.html.net/requestmessage/content/) con el contenido del documento. |

## Observaciones

Por definición, un manejador de mensajes es una clase que recibe una solicitud Web y devuelve una respuesta Web. En otras palabras, un manejador de mensajes se utiliza para procesar una solicitud de servicio Web durante la entrada y/o para procesar la respuesta durante la salida.

Por favor, visite nuestro [sitio de documentación](https://docs.aspose.com/html/net/message-handlers/) para ver más escenarios sobre cómo usar este constructor.

Referencia:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Ver también

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage, Configuration) {#constructor_3}

Crea un documento HTML a partir del objeto [RequestMessage](T:com.aspose.html.net.RequestMessage).

```java
public HTMLDocument(RequestMessage request, Configuration configuration)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| request | RequestMessage | El mensaje de solicitud que contiene un [body](P:com.aspose.html.net.RequestMessage.Content) con el contenido del documento. |
| configuración | Configuración | La configuración del entorno, como la política de scripts, la hoja de estilo de usuario personalizada, etc. |

## Observaciones

Por definición, un manejador de mensajes es una clase que recibe una solicitud Web y devuelve una respuesta Web. En otras palabras, un manejador de mensajes se utiliza para procesar una solicitud de servicio Web durante la entrada y/o para procesar la respuesta durante la salida.

Por favor, visite nuestro [sitio de documentación](https://docs.aspose.com/html/net/message-handlers/) para ver más escenarios sobre cómo usar este constructor.

Referencia:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Ver también

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
