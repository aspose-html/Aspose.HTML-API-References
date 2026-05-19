---
title: "Enum XPathResultType"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Enum com.aspose.html.dom.xpath.XPathResultType. Un unsigned short che indica il tipo di risultato. Se viene specificato un tipo specifico, il risultato verrà restituito come il tipo corrispondente usando le conversioni di tipo XPath dove necessario e possibile."
type: docs

url: /it/java/com.aspose.html.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

Un unsigned short che indica il tipo di risultato. Se viene specificato un `type` specifico, il risultato verrà restituito come il tipo corrispondente, utilizzando le conversioni di tipo XPath dove richiesto e possibile.

```java
public enum XPathResultType
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Any | `0` | Questo codice non rappresenta un tipo specifico. Una valutazione di un'espressione XPath non produrrà mai questo tipo. Se viene richiesto questo tipo, la valutazione restituisce qualsiasi tipo risulti naturalmente dalla valutazione dell'espressione. Se il risultato naturale è un set di nodi quando è stato richiesto il tipo `Any`, allora `UnorderedNodeIterator`is sempre il tipo risultante. Qualsiasi altra rappresentazione di un set di nodi deve essere richiesta esplicitamente. |
| Number | `1` | Il risultato è un numero come definito da [XPath 1.0]. La modifica del documento non invalida il numero, ma potrebbe significare che una rivalutazione non produrrebbe lo stesso numero. |
| String | `2` | Il risultato è una Stringa come definita da [XPath 1.0]. La modifica del documento non invalida la Stringa, ma potrebbe significare che la Stringa non corrisponde più al documento corrente. |
| Boolean | `3` | Il risultato è un booleano come definito da [XPath 1.0]. La modifica del documento non invalida il booleano, ma potrebbe significare che una rivalutazione non produrrebbe lo stesso valore booleano. |
| UnorderedNodeIterator | `4` | Il risultato è un set di nodi come definito da [XPath 1.0] che sarà accessibile in modo iterativo, il che potrebbe non produrre nodi in un ordine particolare. La modifica del documento invalida l'iterazione. Questo è il tipo predefinito restituito se il risultato è un set di nodi e viene richiesto il tipo `Any`type. |
| OrderedNodeIterator | `5` | Il risultato è un set di nodi come definito da [XPath 1.0] che sarà accessibile in modo iterativo, producendo nodi ordinati secondo il documento. La modifica del documento invalida l'iterazione. |
| UnorderedNodeSnapshot | `6` | Il risultato è un set di nodi come definito da [XPath 1.0] che sarà accessibile come una lista snapshot di nodi che potrebbe non essere in un ordine particolare. La modifica del documento non invalida lo snapshot ma potrebbe significare che una rivalutazione non produrrebbe lo stesso snapshot e i nodi nello snapshot potrebbero essere stati modificati, spostati o rimossi dal documento. |
| OrderedNodeSnapshot | `7` | Il risultato è un set di nodi come definito da [XPath 1.0] che sarà accessibile come una lista snapshot di nodi che saranno nell'ordine originale del documento. La modifica del documento non invalida lo snapshot ma potrebbe significare che una rivalutazione non produrrebbe lo stesso snapshot e i nodi nello snapshot potrebbero essere stati modificati, spostati o rimossi dal documento. |
| AnyUnorderedNode | `8` | Il risultato è un set di nodi come definito da [XPath 1.0] e sarà accessibile come nodo singolo, che può essere `null` se il set di nodi è vuoto. La modifica del documento non invalida il nodo, ma potrebbe significare che il nodo risultato non corrisponde più al documento corrente. Questa è una comodità che consente ottimizzazioni poiché l'implementazione può fermarsi non appena viene trovato qualsiasi nodo nel set risultante. Se c'è più di un nodo nel risultato effettivo, il nodo singolo restituito potrebbe non essere il primo nell'ordine del documento. |
| FirstOrderedNode | `9` | Il risultato è un set di nodi come definito da [XPath 1.0] e sarà accessibile come nodo singolo, che può essere `null` se il set di nodi è vuoto. La modifica del documento non invalida il nodo, ma potrebbe significare che il nodo risultato non corrisponde più al documento corrente. Questa è una comodità che consente ottimizzazioni poiché l'implementazione può fermarsi una volta trovato il primo nodo nell'ordine del documento del set risultante. Se ci sono più di un nodo nel risultato effettivo, il nodo singolo restituito sarà il primo nell'ordine del documento. |

### Vedi anche

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
