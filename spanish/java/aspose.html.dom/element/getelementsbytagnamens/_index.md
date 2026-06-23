---
title: "Element.GetElementsByTagNameNS"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método de Element. Devuelve un objeto HTMLCollection que contiene todos los elementos con un nombre local dado y una cadena de URI de paquete en orden de documento"
type: docs

url: /es/java/com.aspose.html.dom/element/getelementsbytagnamens/
---
## Element.GetElementsByTagNameNS method

Devuelve un objeto [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) que contiene todos los [`elements`](../) con un nombre local dado y una cadena de URI de paquete en orden de documento.

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| packageURI | Cadena | La representación de cadena del URI del paquete. |
| localName | Cadena | Representación en cadena del nombre local. |

### Valor devuelto

Un objeto [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) es una lista similar a una matriz de [`elements`](../).

## Observaciones

Consulte la [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbytagnamens) oficial.

También puede estar interesado en la [documentación](https://docs.aspose.com/html/net/).

Puedes descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Ejemplos

```java
# .xhtml input file content
<!DOCTYPE html>
<html lang="en"
   xmlns="http://www.w3.org/1999/xhtml"
   xmlns:custom="http://www.company.com">
<head>
	<meta charset="UTF-8"/>
	<link rel="stylesheet" href="/styles/main.css"/>
	<title>Title</title>
</head>
<body>
<custom:customtag>
	Custom package custom tag content goes here...
</custom:customtag>
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

	HTMLCollection htmlCollection = document.GetElementsByTagNameNS("http://www.company.com", "customtag");
	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// El código del usuario va aquí
}
```

*inputHtmlPath - user input xhtml file path.

# Console output

Encontrado: 1

El contenido de la etiqueta personalizada del paquete personalizado va aquí...

### Ver también

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
