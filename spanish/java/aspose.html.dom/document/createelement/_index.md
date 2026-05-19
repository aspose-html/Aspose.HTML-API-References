---
title: "Document.CreateElement"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método Document. En un documento HTML, el método document.createElement crea el elemento HTML especificado por tagName o un HTMLUnknownElement si tagName no es reconocido."
type: docs

url: /es/java/com.aspose.html.dom/document/createelement/
---
## Document.CreateElement method

En un documento HTML, el método document.createElement() crea el elemento HTML especificado por tagName, o un [`HTMLUnknownElement`](../../../com.aspose.html/htmlunknownelement/) si tagName no es reconocido.

```java
public Element CreateElement(String localName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | String | Una cadena que especifica el tipo de elemento a crear. El nodeName del elemento creado se inicializa con el valor de tagName. No use nombres calificados (como "html:a") con este método. Cuando se llama en un documento HTML, createElement() convierte tagName a minúsculas antes de crear el elemento. |

### Valor de retorno

El nuevo [`Element`](../../element/).

## Ejemplos

```java
var element = document.CreateElement(tagName);
```

### Ver también

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
