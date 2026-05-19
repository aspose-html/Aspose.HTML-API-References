---
title: "Document.CreateDocumentType"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo Document. Il metodo restituisce un oggetto DocumentType che può essere utilizzato con DOMImplementation.createDocument durante la creazione del documento o può essere inserito nel documento tramite metodi come Node.insertBefore o Node.replaceChild"
type: docs

url: /it/java/com.aspose.html.dom/document/createdocumenttype/
---
## Document.CreateDocumentType method

Il metodo restituisce un oggetto [`DocumentType`](../../documenttype/) che può essere utilizzato con DOMImplementation.createDocument durante la creazione del documento o può essere inserito nel documento tramite metodi come Node.insertBefore() o Node.replaceChild().

```java
public DocumentType CreateDocumentType(String name, String publicId, String systemId, 
    String internalSubset)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | String | È una DOMString che contiene il nome qualificato, ad esempio svg:svg. |
| publicId | String | È una DOMString che contiene l'identificatore PUBLIC. |
| systemId | String | È una DOMString che contiene gli identificatori SYSTEM. |
| internalSubset | String | Il sottoinsieme interno. |

### Valore di ritorno

Il [`DocumentType`](../../documenttype/).

## Esempi

```java
var dt = document.CreateDocumentType("svg:svg", "-//W3C//DTD SVG 1.1//EN", "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd", "");
```

### Vedi anche

* class [DocumentType](../../documenttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
