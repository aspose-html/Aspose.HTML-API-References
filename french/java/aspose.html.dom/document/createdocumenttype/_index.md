---
title: "Document.CreateDocumentType"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Document. La méthode renvoie un objet DocumentType qui peut être utilisé avec DOMImplementation.createDocument lors de la création du document ou peut être inséré dans le document via des méthodes comme Node.insertBefore ou Node.replaceChild"
type: docs

url: /fr/java/com.aspose.html.dom/document/createdocumenttype/
---
## Document.CreateDocumentType method

La méthode renvoie un [`DocumentType`](../../documenttype/) objet qui peut être utilisé avec DOMImplementation.createDocument lors de la création du document ou peut être inséré dans le document via des méthodes comme Node.insertBefore() ou Node.replaceChild().

```java
public DocumentType CreateDocumentType(String name, String publicId, String systemId, 
    String internalSubset)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom | String | Est une DOMString contenant le nom qualifié, comme svg:svg. |
| publicId | String | Est une DOMString contenant l'identifiant PUBLIC. |
| systemId | String | Est une DOMString contenant les identifiants SYSTEM. |
| internalSubset | String | Le sous-ensemble interne. |

### Valeur de retour

Le [`DocumentType`](../../documenttype/).

## Exemples

```java
var dt = document.CreateDocumentType("svg:svg", "-//W3C//DTD SVG 1.1//EN", "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd", "");
```

### Voir aussi

* class [DocumentType](../../documenttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
