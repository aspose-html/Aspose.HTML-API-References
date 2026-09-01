---
title: "Document.GetElementsByClassName"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método Document. El método getElementsByClassName de la interfaz Document devuelve un objeto similar a una matriz con todos los elementos hijos que tienen todos los nombres de clase especificados."
type: docs

url: /es/java/com.aspose.html.dom/document/getelementsbyclassname/
---
## Document.GetElementsByClassName method

El método getElementsByClassName de la interfaz [`Document`](../) devuelve un objeto similar a una matriz con todos los elementos hijos que tienen todos los nombres de clase especificados.

Cuando se llama sobre el objeto document, se busca en todo el documento, incluido el nodo raíz. También puede llamar a getElementsByClassName() sobre cualquier elemento; devolverá solo los elementos que sean descendientes del elemento raíz especificado con los nombres de clase dados.

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| classNames | Cadena | La String String que contiene un conjunto no ordenado de tokens únicos separados por espacios que representan clases (nombres de clase) |

### Valor devuelto

Una [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) en vivo de los elementos encontrados.

## Observaciones

Consulte la [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname) oficial.

El contenido práctico de desarrollo web se puede encontrar en [w3schools](https://www.w3schools.com/jsref/met_element_getelementsbyclassname.asp).

Puedes descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Ejemplos

```java
var elements = document.GetElementsByClassName("red test");
```

```java
// Contenido HTML
<div class="custom-class">Customized by css class container</div>

// Código C#
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("custom-class");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// El código del usuario va aquí
}
```

// Salida de consola

Encontrado: 1

Personalizado por la clase css container

*inputHtmlPath - user input html file path

```java
// Estilos CSS
.ddd{
	padding: 10pt;
}

.kkk{
	background-color: chartreuse;
}

// Contenido HTML
<div id="smart class">
	<p id="p1" class="ddd kkk">Paragraph styled by class name =ddd kkk=</p>
	<p id="p2" class="ddd fff">Paragraph styled by class name =ddd fff=</p>
	<p id="p3" class="kkk fff">Paragraph styled by class name =kkk fff=</p>
</div>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("ddd");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
		Console.WriteLine($"Element type: {element.GetType()}");
	}
         
	// El código del usuario va aquí
}
```

# Console output

Encontrado: 2

Párrafo con estilo por el nombre de clase =ddd kkk=

Tipo de elemento: Aspose.Html.HTMLParagraphElement

Párrafo con estilo por el nombre de clase =ddd fff=

Tipo de elemento: Aspose.Html.HTMLParagraphElement

*inputHtmlPath - user input html file path

```java
// Estilos CSS
.pStyle{
  font-
}

# HTML content
<div>
	<p class="pStyle">First styled by pStyle class paragraph</p>
	<p class="pStyle">Second styled by pStyle class paragraph</p>
	<p class="pStyle">Third styled by pStyle class paragraph</p>
	<span class="pStyle">Span styled by pStyle</span>
</div>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("pStyle");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
		Console.WriteLine($"Element type: {element.GetType()}");
	}
         
	// El código del usuario va aquí
}
```

# Console output

Encontrado: 4

Primero con estilo por la clase pStyle del párrafo

Tipo de elemento: Aspose.Html.HTMLParagraphElement

Segundo con estilo por la clase pStyle del párrafo

Tipo de elemento: Aspose.Html.HTMLParagraphElement

Tercero con estilo por la clase pStyle del párrafo

Tipo de elemento: Aspose.Html.HTMLParagraphElement

Span estilizado por pStyle

Tipo de elemento: Aspose.Html.HTMLElement

*inputHtmlPath - user input html file path

### Ver también

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
