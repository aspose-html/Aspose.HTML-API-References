---
title: "Document.GetElementById"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método del documento. El método Document getElementById devuelve un objeto Element que representa el elemento cuya propiedad id coincide con la cadena especificada. Dado que los IDs de los elementos deben ser únicos si se especifican, son una forma útil de acceder rápidamente a un elemento específico."
type: docs

url: /es/java/com.aspose.html.dom/document/getelementbyid/
---
## Document.GetElementById method

El método Document getElementById() devuelve un objeto [`Element`](../../element/) que representa el elemento cuya propiedad id coincide con la cadena especificada. Dado que los IDs de los elementos deben ser únicos si se especifican, son una forma útil de acceder rápidamente a un elemento específico.

Si necesitas acceder a un elemento que no tiene ID, puedes usar querySelector() para encontrar el elemento usando cualquier selector.

```java
public Element GetElementById(String elementId)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| elementId | Cadena | El ID del elemento a localizar. El ID es una cadena sensible a mayúsculas y minúsculas que es única dentro del documento; solo un elemento puede tener un ID dado. |

### Valor devuelto

Un objeto [`Element`](../../element/) que describe el objeto del elemento DOM que coincide con el ID especificado, o null si no se encontró ningún elemento coincidente en el documento.

## Observaciones

Consulta la [spec](https://dom.spec.whatwg.org/#dom-nonelementparentnode-getelementbyid) oficial.

El contenido de desarrollo web práctico se puede encontrar en [w3schools](https://www.w3schools.com/jsref/met_document_getelementbyid.asp).

Puedes descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Ejemplos

```java
// Contenido HTML
<div id="uniqueIdentifier">Container with ID - identifier</div>

// Código C#
import System;
import Aspose.Html;
import com.aspose.html.dom;
...
	using (var document = new HTMLDocument(inputHtmlPath))
		{
			Element element = document.GetElementById("uniqueIdentifier");
			HTMLDivElement divElement = (HTMLDivElement) element;
			Console.WriteLine(divElement.InnerHTML);

			// El código del usuario va aquí
   }
```

// Salida de consola

Contenedor con ID - identificador

*inputHtmlPath - user input html file path

### Ver también

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
