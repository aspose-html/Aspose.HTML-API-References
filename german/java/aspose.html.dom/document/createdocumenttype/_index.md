---
title: "Document.CreateDocumentType"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Document-Methode. Die Methode gibt ein DocumentType-Objekt zurück, das entweder mit DOMImplementation.createDocument bei der Dokumenterstellung verwendet werden kann oder über Methoden wie Node.insertBefore oder Node.replaceChild in das Dokument eingefügt werden kann."
type: docs

url: /de/java/com.aspose.html.dom/document/createdocumenttype/
---
## Document.CreateDocumentType method

Die Methode gibt ein [`DocumentType`](../../documenttype/)‑Objekt zurück, das entweder mit DOMImplementation.createDocument bei der Dokumenterstellung verwendet werden kann oder über Methoden wie Node.insertBefore() oder Node.replaceChild() in das Dokument eingefügt werden kann.

```java
public DocumentType CreateDocumentType(String name, String publicId, String systemId, 
    String internalSubset)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Ist ein DOMString, der den qualifizierten Namen enthält, z. B. svg:svg. |
| publicId | String | Ist ein DOMString, der den PUBLIC‑Identifier enthält. |
| systemId | String | Ist ein DOMString, der die SYSTEM‑Identifier enthält. |
| internalSubset | String | Das interne Subset. |

### Rückgabewert

Der [`DocumentType`](../../documenttype/).

## Beispiele

```java
var dt = document.CreateDocumentType("svg:svg", "-//W3C//DTD SVG 1.1//EN", "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd", "");
```

### Siehe auch

* class [DocumentType](../../documenttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
