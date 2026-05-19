---
title: "SVGListBase-1.Item"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Proprietà SVGListBase. Restituisce l'elemento all'indice nella lista"
type: docs

url: /it/java/com.aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

Restituisce l'elemento all'indice nella lista.

```java
public T this[ulong index] { get; set; }
```

| Parametro | Descrizione |
| --- | --- |
| index | Indice nella lista. |

### Valore di ritorno

L'oggetto memorizzato nella posizione all'indice nella lista.

### Property Value

Il tipo di elemento memorizzato nella lista.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Codice [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Generato quando l'elenco non può essere modificato. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Codice [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Generato se il numero dell'indice è maggiore o uguale a numberOfItems. |

### Vedi anche

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
