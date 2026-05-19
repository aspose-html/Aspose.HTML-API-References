---
title: "IXPathResult.SnapshotItem"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo IXPathResult. Restituisce l'elemento all'indice specificato nella collezione snapshot. Se l'indice è maggiore o uguale al numero di nodi nella lista, questo metodo restituisce null. A differenza del risultato dell'iteratore, lo snapshot non diventa non valido ma potrebbe non corrispondere al documento corrente se questo viene modificato."
type: docs

url: /it/java/com.aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

Restituisce l'elemento `index`‑esimo nella collezione snapshot. Se `index` è maggiore o uguale al numero di nodi nella lista, questo metodo restituisce `null`. A differenza del risultato iteratore, lo snapshot non diventa invalido, ma potrebbe non corrispondere al documento corrente se questo viene modificato.

```java
public Node SnapshotItem(int index)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | Indice nella collezione snapshot. |

### Valore di ritorno

Il nodo nella posizione `index` della `NodeList`, o `null` se l'indice non è valido.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: sollevato se `resultType` non è di tipo `UnorderedNodeSnapshot` o `OrderedNodeSnapshot`. |

### Vedi anche

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
