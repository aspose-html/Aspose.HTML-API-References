---
title: "Element.GetElementsByTagName"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método de Element. Devuelve un objeto HTMLCollection que contiene todos los elementos con un nombre de etiqueta dado en orden de documento"
type: docs

url: /es/java/com.aspose.html.dom/element/getelementsbytagname/
---
## Element.GetElementsByTagName method

Devuelve el objeto [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) que contiene todos los [`elements`](../) con un nombre de etiqueta dado, en orden de documento.

```java
public HTMLCollection GetElementsByTagName(String name)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | El nombre de la etiqueta. Representación en cadena del nombre de la etiqueta. |

### Valor de retorno

Un objeto [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) es una lista similar a una matriz de [`elements`](../).

## Observaciones

Consulte la [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbytagname) oficial.

También puede estar interesado en la [documentation](https://docs.aspose.com/html/net/).

Puedes descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Ejemplos

```java
# Html input content
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

	HTMLCollection htmlCollection = document.GetElementsByTagName("p");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// El código del usuario va aquí
}
```

*inputHtmlPath - user input html file.

# Console output

Encontrado: 3

El contenido del párrafo con estilo de la clase pStyle...

El contenido del segundo párrafo...

El contenido del tercer párrafo...

### Ver también

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
