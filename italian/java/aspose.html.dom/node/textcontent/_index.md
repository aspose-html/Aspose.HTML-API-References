---
title: "Node.TextContent"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Proprietà Node. La proprietà textContent dell'interfaccia Node rappresenta il contenuto testuale del nodo e dei suoi discendenti"
type: docs

url: /it/java/com.aspose.html.dom/node/textcontent/
---
## Node.TextContent property

La proprietà textContent dell'interfaccia [`Node`](../) rappresenta il contenuto testuale del nodo e dei suoi discendenti.

```java
public String TextContent { get; set; }
```

### Property Value

Una stringa, o null. Il suo valore dipende dalla situazione:

Se il nodo è un documento o un doctype, textContent restituisce null. Nota: per ottenere tutto il testo e i dati CDATA dell'intero documento, usa document.documentElement.textContent. Se il nodo è una sezione CDATA, un commento, un'istruzione di elaborazione o un nodo di testo, textContent restituisce, o imposta, il testo all'interno del nodo, cioè il [`Node.nodeValue`](../nodevalue/). Per altri tipi di nodo, textContent restituisce la concatenazione del textContent di ogni nodo figlio, escludendo i commenti e le istruzioni di elaborazione.

## Osservazioni

Riferimento:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-textcontent](https://dom.spec.whatwg.org/#dom-node-textcontent).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Vedi anche

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
