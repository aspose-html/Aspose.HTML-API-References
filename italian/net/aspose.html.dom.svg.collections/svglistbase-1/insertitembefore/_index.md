---
title: SVGListBase1.InsertItemBefore
second_title: Aspose.HTML per riferimento API .NET
description: SVGListBase metodo. Inserisce un nuovo elemento nellelenco nella posizione specificata. Il primo elemento è il numero 0.
type: docs
weight: 90
url: /it/net/aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

Inserisce un nuovo elemento nell'elenco nella posizione specificata. Il primo elemento è il numero 0.

```csharp
public T InsertItemBefore(T newItem, ulong index)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newItem | T | L'elemento che deve essere inserito nell'elenco. |
| index | UInt64 | L'indice dell'elemento prima del quale deve essere inserito il nuovo elemento. Il primo elemento è il numero 0. Se l'indice è uguale a 0, il nuovo elemento viene inserito all'inizio dell'elenco. Se l'indice è maggiore o uguale a numberOfItems, il nuovo elemento viene aggiunto alla fine dell'elenco. |

### Valore di ritorno

L'elemento inserito.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Codice[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). Generato quando l'elenco non può essere modificato. |

### Guarda anche

* class [SVGListBase&lt;T&gt;](../)
* spazio dei nomi [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* assemblea [Aspose.HTML](../../../)


