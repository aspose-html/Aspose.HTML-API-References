---
title: "Document.CreateDocumentType"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Document-methode. De methode retourneert een DocumentType-object dat ofwel kan worden gebruikt met DOMImplementation.createDocument bij het aanmaken van een document, of kan worden geplaatst in het document via methoden zoals Node.insertBefore of Node.replaceChild."
type: docs

url: /nl/java/com.aspose.html.dom/document/createdocumenttype/
---
## Document.CreateDocumentType method

De methode retourneert een [`DocumentType`](../../documenttype/) object dat ofwel kan worden gebruikt met DOMImplementation.createDocument bij het aanmaken van een document, of kan worden geplaatst in het document via methoden zoals Node.insertBefore() of Node.replaceChild().

```java
public DocumentType CreateDocumentType(String name, String publicId, String systemId, 
    String internalSubset)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | String | Is een DOMString die de gekwalificeerde naam bevat, zoals svg:svg. |
| publicId | String | Is een DOMString die de PUBLIC-identificatie bevat. |
| systemId | String | Is een DOMString die de SYSTEM-identificaties bevat. |
| internalSubset | String | De interne subset. |

### Retourwaarde

De [`DocumentType`](../../documenttype/).

## Voorbeelden

```java
var dt = document.CreateDocumentType("svg:svg", "-//W3C//DTD SVG 1.1//EN", "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd", "");
```

### Zie ook

* class [DocumentType](../../documenttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
