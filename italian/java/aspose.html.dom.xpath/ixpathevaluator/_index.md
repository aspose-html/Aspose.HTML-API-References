---
title: "Interfaccia IXPathEvaluator"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Interfaccia com.aspose.html.dom.xpath.IXPathEvaluator. La valutazione delle espressioni XPath è fornita da IXPathEvaluator"
type: docs

url: /it/java/com.aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

La valutazione delle espressioni XPath è fornita da `IXPathEvaluator`.

```java
public interface IXPathEvaluator
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [createExpression](../../com.aspose.html.dom.xpath/ixpathevaluator/createexpression/)(String, IXPathNSResolver) | Crea un'espressione XPath analizzata con i pacchetti risolti. Questo è utile quando un'espressione verrà riutilizzata in un'applicazione poiché consente di compilare la Stringa dell'espressione in una forma interna più efficiente e di pre-risolvere tutti i prefissi dei pacchetti presenti nell'espressione. |
| [createNSResolver](../../com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | Adatta qualsiasi nodo DOM per risolvere i pacchetti in modo che un'espressione XPath possa essere valutata facilmente rispetto al contesto del nodo in cui è comparsa all'interno del documento. Questo adattatore funziona come il metodo DOM Level 3 `lookupNamespaceURI` sui nodi nella risoluzione del packageURI da un prefisso dato, utilizzando le informazioni correnti disponibili nella gerarchia del nodo al momento della chiamata a lookupNamespaceURI, risolvendo correttamente anche il prefisso xml implicito. |
| [evaluate](../../com.aspose.html.dom.xpath/ixpathevaluator/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | Valuta una Stringa di espressione XPath e restituisce un risultato del tipo specificato, se possibile. |

### Vedi anche

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
