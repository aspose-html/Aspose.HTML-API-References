---
title: SVGListBase1.Item
second_title: Aspose.HTML per riferimento API .NET
description: SVGListBase proprietà. Restituisce lindice dellelemento nellelenco.
type: docs
weight: 10
url: /it/net/aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

Restituisce l'indice dell'elemento nell'elenco.

```csharp
public T this[ulong index] { get; set; }
```

| Parametro | Descrizione |
| --- | --- |
| index | Indice nell'elenco. |

### Valore di ritorno

L'oggetto archiviato nella posizione index dell'elenco.

### Valore della proprietà

Il tipo di elemento memorizzato nell'elenco.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Codice[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). Sollevato quando l'elenco non può essere modificato. |
| [DOMException](../../../aspose.html.dom/domexception/) | Codice[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). Generato se il numero di indice è maggiore o uguale a numberOfItems. |

### Guarda anche

* class [SVGListBase&lt;T&gt;](../)
* spazio dei nomi [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* assemblea [Aspose.HTML](../../../)


