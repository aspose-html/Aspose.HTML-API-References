---
title: "Document.GetElementsByTagNameNS"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método Document. Devuelve una lista de elementos con el nombre de etiqueta dado que pertenecen al paquete especificado. Se busca en todo el documento, incluido el nodo raíz."
type: docs

url: /es/java/com.aspose.html.dom/document/getelementsbytagnamens/
---
## Document.GetElementsByTagNameNS method

Devuelve una lista de elementos con el nombre de etiqueta dado que pertenecen al paquete especificado. Se busca en todo el documento, incluido el nodo raíz.

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| packageURI | Cadena | El URI del paquete de los elementos a buscar. |
| localName | Cadena | Ya sea el nombre local de los elementos a buscar o el valor especial *, que coincide con todos los elementos. |

### Valor devuelto

Una lista viva [`NodeList`](../../../com.aspose.html.collections/nodelist/) (pero vea la nota a continuación) de los elementos encontrados en el orden en que aparecen en el árbol.

## Observaciones

Consulte la [especificación](https://dom.spec.whatwg.org/#dom-document-getelementsbytagnamens) oficial.

El contenido práctico de desarrollo web se puede encontrar en [w3schools](https://www.w3schools.com/xml/met_document_getelementsbytagnamens.asp).

Puedes descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Ejemplos

```java
var elements = document.GetElementsByTagNameNS(@package, name);
```

```java
# HTML content. File extension - xhtml
<!DOCTYPE html>
<html lang="en"
	xmlns="http://www.w3.org/1999/xhtml"
	xmlns:xml="http://www.w3.org/XML/1998/package">
...
<xml:uniquetag>
  xml package uniquetag content goes here...
</xml:uniquetag>
...
</html>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
    HTMLCollection htmlCollection = document.GetElementsByTagNameNS("http://www.w3.org/XML/1998/package","uniquetag");
    Console.WriteLine($"Found: {htmlCollection.Length}" );
    foreach (Element element in htmlCollection)
    {
      Console.WriteLine(element.InnerHTML);
    }  
    // El código del usuario va aquí
}





# Console output

Found: 1

xml package uniquetag content goes here...




```

*inputHtmlPath - user input xhtml file path

```java
# HTML content. File extension - xhtml
<!DOCTYPE html>
<html lang="en"
   xmlns="http://www.w3.org/1999/xhtml"
   xmlns:custom="http://www.company.com"
   xmlns:xml="http://www.w3.org/XML/1998/package">
...
<xml:CATALOG>
	<xml:CD>
    <xml:TITLE>Empire Burlesque</xml:TITLE>
    <xml:ARTIST>Bob Dylan</xml:ARTIST>
    <xml:COUNTRY>USA</xml:COUNTRY>
    <xml:COMPANY>Columbia</xml:COMPANY>
    <xml:PRICE>10.90</xml:PRICE>
    <xml:YEAR>1985</xml:YEAR>
  </xml:CD>
...

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = 
          document.GetElementsByTagNameNS("http://www.w3.org/XML/1998/package", "ARTIST");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// El código del usuario va aquí
}
```

# Console output

Encontrado: 3

Bob Dylan

Bonnie Tyler

Dolly Parton

*inputHtmlPath - user input xhtml file path

### Ver también

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
