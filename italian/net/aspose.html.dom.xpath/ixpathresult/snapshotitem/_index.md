---
title: IXPathResult.SnapshotItem
second_title: Aspose.HTML per riferimento API .NET
description: IXPathResult metodo. Restituisce ilindice esimo elemento nella raccolta di istantanee. Seindiceè maggiore di o uguale al numero di nodi nellelenco questo metodo restituiscenullo . A differenza del risultato delliteratore  lo snapshot non diventa non valido ma potrebbe non corrispondere al documento corrente se viene modificato.
type: docs
weight: 90
url: /it/net/aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

Restituisce il`indice` esimo elemento nella raccolta di istantanee. Se`indice`è maggiore di o uguale al numero di nodi nell'elenco, questo metodo restituisce`nullo` . A differenza del risultato dell'iteratore , lo snapshot non diventa non valido, ma potrebbe non corrispondere al documento corrente se viene modificato.

```csharp
public Node SnapshotItem(int index)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | Indicizza nella raccolta di istantanee. |

### Valore di ritorno

Il nodo al`indice` esima posizione nel`NodeList` , O`nullo` se non è un indice valido.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: sollevato se`resultType` non è `UnorderedNodeSnapshot` digitare o`Snapshot del nodo ordinato` tipo. |

### Guarda anche

* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathResult](../)
* spazio dei nomi [Aspose.Html.Dom.XPath](../../ixpathresult/)
* assemblea [Aspose.HTML](../../../)


