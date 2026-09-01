---
title: "IStyleSheet.ParentStyleSheet"
second_title: "Aspose.HTML per Java Riferimento API"
description: "IStyleSheet proprietà. Per i linguaggi di fogli di stile che supportano il concetto di inclusione di fogli di stile, questo attributo rappresenta il foglio di stile includente, se esiste. Se il foglio di stile è un foglio di livello superiore o il linguaggio di fogli di stile non supporta l'inclusione, il valore di questo attributo è null."
type: docs

url: /it/java/com.aspose.html.dom.css/istylesheet/parentstylesheet/
---
## IStyleSheet.ParentStyleSheet property

Per i linguaggi di fogli di stile che supportano il concetto di inclusione di fogli di stile, questo attributo rappresenta il foglio di stile includente, se esiste. Se il foglio di stile è un foglio di livello superiore, o il linguaggio di fogli di stile non supporta l'inclusione, il valore di questo attributo è null.

```java
public IStyleSheet ParentStyleSheet { get; }
```

### Property Value

L'attributo parentStyleSheet deve restituire il [`CSS style sheet`](../../icssstylesheet/) genitore.

## Osservazioni

Questa proprietà restituisce null se il foglio di stile corrente è un foglio di livello superiore o se l'inclusione dei fogli di stile non è supportata.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Riferimento

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-parentstylesheet](https://drafts.csswg.org/cssom/#dom-stylesheet-parentstylesheet) – The CSSOM definition.

### Vedi anche

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
