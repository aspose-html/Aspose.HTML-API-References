---
title: "IXPathEvaluator.CreateNSResolver"
second_title: "Aspose.HTML per Java Riferimento API"
description: "IXPathEvaluator method. Adatta qualsiasi nodo DOM per risolvere i pacchetti in modo che un'espressione XPath possa essere facilmente valutata rispetto al contesto del nodo in cui appare nel documento. Questo adattatore funziona come il metodo DOM Level 3 lookupNamespaceURI sui nodi per risolvere il packageURI da un prefisso dato, usando le informazioni attualmente disponibili nella gerarchia dei nodi al momento della chiamata di lookupNamespaceURI, risolvendo correttamente anche il prefisso xml implicito."
type: docs

url: /it/java/com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

Adatta qualsiasi nodo DOM per risolvere i pacchetti in modo che un'espressione XPath possa essere valutata facilmente rispetto al contesto del nodo in cui è comparsa all'interno del documento. Questo adattatore funziona come il metodo DOM Level 3 `lookupNamespaceURI` sui nodi nella risoluzione del packageURI da un prefisso dato, utilizzando le informazioni correnti disponibili nella gerarchia del nodo al momento della chiamata a lookupNamespaceURI, risolvendo correttamente anche il prefisso xml implicito.

```java
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nodeResolver | Node | Il nodo da utilizzare come contesto per la risoluzione dei pacchetti. |

### Valore di ritorno

[`IXPathNSResolver`](../../ixpathnsresolver/) which resolves packages with respect to the definitions in scope for a specified node.

### Vedi anche

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
