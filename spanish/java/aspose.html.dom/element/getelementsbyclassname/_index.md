---
title: "Element.GetElementsByClassName"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método del elemento. Devuelve un objeto HTMLCollection que contiene todos los elementos dentro del elemento que tienen todas las clases especificadas en el argumento"
type: docs

url: /es/java/com.aspose.html.dom/element/getelementsbyclassname/
---
## Element.GetElementsByClassName method

Devuelve el objeto [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) que contiene todos los elementos dentro de [`element`](../) que tienen todas las clases especificadas en el argumento.

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| classNames | Cadena | La String String que contiene un conjunto no ordenado de tokens únicos separados por espacios que representan clases (nombres de clase) |

### Valor devuelto

Un objeto [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) es una lista similar a una matriz de [`elements`](../).

## Observaciones

Consulte la [especificación](https://dom.spec.whatwg.org/#dom-element-getelementsbyclassname) oficial.

También puede estar interesado en la [documentación](https://docs.aspose.com/html/net/).

Puedes descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Ejemplos

```java
# HTML source content
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Title</title>
</head>
<body>
<div id="divElementContainerId">
	<p class="pStyle">The paragraph styled pStyle class content...</p>
	<p>The second paragraph content...</p>
	<p>The third paragraph content...</p>
	<div class="pStyle">The div element styled pStyle class...</div>
</div>
</body>
</html>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	// El código del usuario va aquí

	Element container = document.GetElementById("divElementContainerId");
	HTMLCollection htmlCollection = container.GetElementsByClassName("pStyle");

	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// El código del usuario va aquí
}
```

*inputHtmlPath - user input html file path.

# Console output

Encontrado: 2

El contenido del párrafo con estilo de clase pStyle...

El elemento div con la clase pStyle...

### Ver también

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
