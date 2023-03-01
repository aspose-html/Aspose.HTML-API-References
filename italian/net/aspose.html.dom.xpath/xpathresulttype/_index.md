---
title: Enum XPathResultType
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.XPath.XPathResultType enum. Uno short senza segno che indica di che tipo di risultato si tratta. Se un specificotipoviene specificato il risultato verrà restituito come il tipo corrispondente utilizzando conversioni di tipo XPath ove richiesto e possibile.
type: docs
weight: 2610
url: /it/net/aspose.html.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

Uno short senza segno che indica di che tipo di risultato si tratta. Se un specifico`tipo`viene specificato, il risultato verrà restituito come il tipo corrispondente, utilizzando conversioni di tipo XPath ove richiesto e possibile.

```csharp
public enum XPathResultType
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Any | `0` | Questo codice non rappresenta un tipo specifico. Una valutazione di un'espressione XPath non produrrà mai questo tipo. Se questo tipo è richiesto, la valutazione restituisce qualsiasi tipo risulti naturalmente dalla valutazione dell'espressione. Se il risultato naturale è un nodo impostato quando`Qualunque` tipo è stato richiesto, quindi`UnorderedNodeIterator` è sempre il tipo risultante. Qualsiasi altra rappresentazione di un set di nodi deve essere esplicitamente richiesta. |
| Number | `1` | Il risultato è un numero come definito da [XPath 1.0]. La modifica del documento non invalida il numero, ma può significare che la rivalutazione non produrrebbe lo stesso numero. |
| String | `2` | Il risultato è una stringa come definita da [XPath 1.0]. La modifica del documento non invalida la stringa, ma può significare che la stringa non corrisponde più al documento corrente. |
| Boolean | `3` | Il risultato è un valore booleano come definito da [XPath 1.0]. La modifica del documento non invalida il valore booleano, ma può significare che la rivalutazione non produrrebbe lo stesso valore booleano. |
| UnorderedNodeIterator | `4` | Il risultato è un set di nodi come definito da [XPath 1.0] a cui si accederà in modo iterativo, che potrebbe non produrre nodi in un ordine particolare. La modifica del documento invalida l'iterazione . Questo è il tipo predefinito restituito se il risultato è un set di nodi e`Qualunque` è richiesto il tipo. |
| OrderedNodeIterator | `5` | Il risultato è un set di nodi come definito da [XPath 1.0] a cui si accederà in modo iterativo, che produrrà nodi ordinati dal documento. La modifica del documento invalida l'iterazione. |
| UnorderedNodeSnapshot | `6` | Il risultato è un set di nodi come definito da [XPath 1.0] a cui si accederà come un'istantanea elenco di nodi che potrebbero non trovarsi in un ordine particolare. La modifica del documento non invalida lo snapshot ma può significare che la rivalutazione non produrrebbe lo stesso snapshot e i nodi nello snapshot potrebbero essere stati alterati, spostati o rimossi dal documento. |
| OrderedNodeSnapshot | `7` | Il risultato è un set di nodi come definito da [XPath 1.0] a cui si accederà come un'istantanea elenco di nodi che saranno nell'ordine del documento originale. La modifica del documento non invalida lo snapshot ma può significare che la rivalutazione non produrrebbe lo stesso snapshot e i nodi nello snapshot potrebbero essere stati alterati, spostati o rimossi dal documento. |
| AnyUnorderedNode | `8` | Il risultato è un set di nodi come definito da [XPath 1.0] e sarà accessibile come un singolo nodo, che può essere`nullo`se il set di nodi è vuoto. La modifica del documento non invalida il nodo, ma può significare che il nodo risultato non corrisponde più al documento corrente. Questa è una comodità che consente l'ottimizzazione poiché l'implementazione può interrompersi una volta trovato un qualsiasi nodo nell'insieme risultante. Se nel risultato effettivo è presente più di un nodo, il singolo nodo restituito potrebbe non essere il primo nell'ordine del documento. |
| FirstOrderedNode | `9` | Il risultato è un set di nodi come definito da [XPath 1.0] e sarà accessibile come un singolo nodo, che può essere`nullo`se il set di nodi è vuoto. La modifica del documento non invalida il nodo, ma può significare che il nodo risultato non corrisponde più al documento corrente. Questa è una comodità che consente l'ottimizzazione poiché l'implementazione può interrompersi una volta trovato il primo nodo nell'ordine del documento dell'insieme risultante. Se sono presenti più di un nodo nel risultato effettivo, il singolo nodo restituito sarà il primo nell'ordine del documento. |

### Guarda anche

* spazio dei nomi [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* assemblea [Aspose.HTML](../../)


