---
title: "Document.CreateDocumentType"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método Document. El método devuelve un objeto DocumentType que puede usarse con DOMImplementation.createDocument al crear el documento o puede insertarse en el documento mediante métodos como Node.insertBefore o Node.replaceChild"
type: docs

url: /es/java/com.aspose.html.dom/document/createdocumenttype/
---
## Document.CreateDocumentType method

El método devuelve un objeto [`DocumentType`](../../documenttype/) que puede usarse con DOMImplementation.createDocument al crear el documento o puede insertarse en el documento mediante métodos como Node.insertBefore() o Node.replaceChild().

```java
public DocumentType CreateDocumentType(String name, String publicId, String systemId, 
    String internalSubset)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | Es una DOMString que contiene el nombre calificado, como svg:svg. |
| publicId | String | Es una DOMString que contiene el identificador PUBLIC. |
| systemId | String | Es una DOMString que contiene los identificadores SYSTEM. |
| internalSubset | String | El subconjunto interno. |

### Valor de retorno

El [`DocumentType`](../../documenttype/).

## Ejemplos

```java
var dt = document.CreateDocumentType("svg:svg", "-//W3C//DTD SVG 1.1//EN", "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd", "");
```

### Ver también

* class [DocumentType](../../documenttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
