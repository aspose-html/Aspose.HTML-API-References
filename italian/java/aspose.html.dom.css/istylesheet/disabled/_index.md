---
title: "IStyleSheet.Disabled"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Proprietà IStyleSheet. La proprietà disabled dell'interfaccia StyleSheet determina se il foglio di stile è impedito di applicarsi al documento."
type: docs

url: /it/java/com.aspose.html.dom.css/istylesheet/disabled/
---
## IStyleSheet.Disabled property

La proprietà disabled dell'interfaccia [`StyleSheet`](../) determina se il foglio di stile è impedito di applicarsi al documento.

Un foglio di stile può essere disabilitato impostando manualmente questa proprietà a true o se è un foglio di stile alternativo inattivo. Nota che disabled == false non garantisce che il foglio di stile venga applicato (potrebbe essere rimosso dal documento, ad esempio).

Modificare questo attributo può provocare una nuova risoluzione dello stile per il documento. Un foglio di stile si applica solo se è presente una definizione di media appropriata e l'attributo disabled è false. Quindi, se il media non si applica all'agente utente corrente, l'attributo disabled viene ignorato.

```java
public bool Disabled { get; set; }
```

### Valore di ritorno

L'attributo disabled, in lettura, deve restituire true se il flag disabled è impostato, altrimenti false. In scrittura, l'attributo disabled deve impostare il flag disabled se il nuovo valore è true, altrimenti rimuovere il flag disabled.

### Property Value

L'attributo disabled, in lettura, deve restituire true se il flag disabled è impostato, altrimenti false. In scrittura, l'attributo disabled deve impostare il flag disabled se il nuovo valore è true, altrimenti rimuovere il flag disabled.

## Osservazioni

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Riferimento

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-disabled](https://drafts.csswg.org/cssom/#dom-stylesheet-disabled) – The CSSOM definition.

### Vedi anche

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
