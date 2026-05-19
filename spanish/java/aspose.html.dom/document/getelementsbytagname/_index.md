---
title: "Document.GetElementsByTagName"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método del documento. El método getElementsByTagName de la interfaz Document devuelve una HTMLCollection de elementos con el nombre de etiqueta dado"
type: docs

url: /es/java/com.aspose.html.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

El método getElementsByTagName de la interfaz [`Document`](../) devuelve una [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) de elementos con el nombre de etiqueta dado.

Se busca en todo el documento, incluido el nodo raíz. La [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) devuelta es dinámica, lo que significa que se actualiza automáticamente para mantenerse sincronizada con el árbol DOM sin necesidad de volver a llamar a document.getElementsByTagName().

```java
public HTMLCollection GetElementsByTagName(String tagname)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tagname | String | Una cadena que representa el nombre de los elementos. La cadena especial \"*\" representa todos los elementos. |

### Valor de retorno

Una [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) dinámica de los elementos encontrados en el orden en que aparecen en el árbol.

## Observaciones

Consulte la [especificación](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname) oficial.

El contenido práctico de desarrollo web se puede encontrar en [w3schools](https://www.w3schools.com/jsref/met_document_getelementsbytagname.asp).

Puedes descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Ejemplos

```java
var elements = document.GetElementsByTagName(name);
```

```java
#HTML content
<div>
	<p class="pStyle">First styled by pStyle class paragraph</p>
	<p class="pStyle">Second styled by pStyle class paragraph</p>
	<p class="pStyle">Third styled by pStyle class paragraph</p>
	<span class="pStyle">Span styled by pStyle</span>
</div>
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

import (var document = new HTMLDocument(inputHtmlPath))
{
    HTMLCollection htmlCollection = document.GetElementsByTagName("p");
    Console.WriteLine($"Found: {htmlCollection.Length}" );
    foreach (Element element in htmlCollection)
    {
      Console.WriteLine(element.InnerHTML);
    }

    // El código del usuario va aquí
}
```

# Console output

Encontrado: 6

Primero con estilo de la clase de párrafo pStyle

Segundo con estilo de la clase de párrafo pStyle

Tercero con estilo de la clase de párrafo pStyle

Párrafo con estilo por nombre de clase =ddd kkk=

Párrafo con estilo por nombre de clase =ddd fff=

Párrafo con estilo por nombre de clase =kkk fff=

*inputHtmlPath - user input html file path

### Ver también

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
