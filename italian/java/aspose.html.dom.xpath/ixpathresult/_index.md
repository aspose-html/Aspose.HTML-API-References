---
title: "Interfaccia IXPathResult"
second_title: "Aspose.HTML per Java Riferimento API"
description: "com.aspose.html.dom.xpath.IXPathResult interface. L'interfaccia XPathResult rappresenta il risultato della valutazione di un'espressione XPath 1.0 nel contesto di un nodo particolare. Poiché la valutazione di un'espressione XPath può produrre vari tipi di risultato, questo oggetto consente di scoprire e manipolare il tipo e il valore del risultato."
type: docs

url: /it/java/com.aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

L'interfaccia `XPathResult` rappresenta il risultato della valutazione di un'espressione XPath 1.0 nel contesto di un nodo specifico. Poiché la valutazione di un'espressione XPath può produrre vari tipi di risultato, questo oggetto consente di scoprire e manipolare il tipo e il valore del risultato.

```java
public interface IXPathResult
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getBooleanValue](../../com.aspose.html.dom.xpath/ixpathresult/booleanvalue/) Il valore di questo risultato booleano. |
| [getInvalidIteratorState](../../com.aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) Indica che l'iteratore è diventato non valido. Vero se `resultType` è di tipo `UnorderedNodeIterator` o `OrderedNodeIterator` e il documento è stato modificato da quando questo risultato è stato restituito. |
| [getNumberValue](../../com.aspose.html.dom.xpath/ixpathresult/numbervalue/) Il valore di questo risultato numerico. |
| [getResultType](../../com.aspose.html.dom.xpath/ixpathresult/resulttype/) Un codice che rappresenta il tipo di questo risultato, come definito dall'enumerazione http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult[`XPathResultType`](../xpathresulttype/). |
| [getSingleNodeValue](../../com.aspose.html.dom.xpath/ixpathresult/singlenodevalue/) Il valore di questo risultato a nodo singolo, che può essere `null`. |
| [getSnapshotLength](../../com.aspose.html.dom.xpath/ixpathresult/snapshotlength/) Il numero di nodi nello snapshot del risultato. I valori validi per gli indici snapshotItem sono da `0` a `snapshotLength-1` inclusi. |
| [getStringValue](../../com.aspose.html.dom.xpath/ixpathresult/Stringvalue/) Il valore di questo risultato String. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [iterateNext](../../com.aspose.html.dom.xpath/ixpathresult/iteratenext/)() | Itera e restituisce il nodo successivo dal set di nodi o `null` se non ci sono più nodi. |
| [snapshotItem](../../com.aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | Restituisce l'elemento `index`‑esimo nella collezione snapshot. Se `index` è maggiore o uguale al numero di nodi nella lista, questo metodo restituisce `null`. A differenza del risultato dell'iteratore, lo snapshot non diventa invalido, ma potrebbe non corrispondere al documento corrente se questo viene modificato. |

### Vedi anche

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
