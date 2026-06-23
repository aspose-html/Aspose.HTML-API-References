---
title: "Document.CreateDocumentType"
second_title: "Aspose.HTML för Java API-referens"
description: "Document-metod. Metoden returnerar ett DocumentType-objekt som antingen kan användas med DOMImplementation.createDocument vid dokumentets skapande eller kan läggas in i dokumentet via metoder som Node.insertBefore eller Node.replaceChild"
type: docs

url: /sv/java/com.aspose.html.dom/document/createdocumenttype/
---
## Document.CreateDocumentType method

Metoden returnerar ett [`DocumentType`](../../documenttype/) objekt som antingen kan användas med DOMImplementation.createDocument vid dokumentets skapande eller kan läggas in i dokumentet via metoder som Node.insertBefore() eller Node.replaceChild().

```java
public DocumentType CreateDocumentType(String name, String publicId, String systemId, 
    String internalSubset)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | String | Är en DOMString som innehåller det kvalificerade namnet, till exempel svg:svg. |
| publicId | String | Är en DOMString som innehåller PUBLIC-identifieraren. |
| systemId | String | Är en DOMString som innehåller SYSTEM-identifierarna. |
| internalSubset | String | Den interna delmängden. |

### Returvärde

Den [`DocumentType`](../../documenttype/).

## Exempel

```java
var dt = document.CreateDocumentType("svg:svg", "-//W3C//DTD SVG 1.1//EN", "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd", "");
```

### Se även

* class [DocumentType](../../documenttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
