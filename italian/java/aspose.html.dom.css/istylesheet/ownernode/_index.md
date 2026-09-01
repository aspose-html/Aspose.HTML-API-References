---
title: "IStyleSheet.OwnerNode"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Proprietà IStyleSheet. Il nodo che associa questo foglio di stile al documento. Per HTML può essere l'elemento LINK o STYLE corrispondente. Per XML può essere l'istruzione di elaborazione di collegamento. Per i fogli di stile inclusi da altri fogli di stile il valore di questo attributo è null."
type: docs

url: /it/java/com.aspose.html.dom.css/istylesheet/ownernode/
---
## IStyleSheet.OwnerNode property

Il nodo che associa questo foglio di stile al documento. Per HTML, può essere l'elemento LINK o STYLE corrispondente. Per XML, può essere l'istruzione di elaborazione di collegamento. Per i fogli di stile inclusi da altri fogli di stile, il valore di questo attributo è null.

```java
public Node OwnerNode { get; }
```

### Property Value

L'attributo ownerNode deve restituire il nodo proprietario.

## Osservazioni

Per i fogli di stile inclusi da altri fogli di stile, ad esempio con @import, il valore di questa proprietà è null.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Riferimento

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-ownernode](https://drafts.csswg.org/cssom/#dom-stylesheet-ownernode) – The CSSOM definition.

### Vedi anche

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
