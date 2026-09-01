---
title: "SVGListBase-1.ReplaceItem"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo SVGListBase. Sostituisce un elemento esistente nell'elenco con un nuovo elemento"
type: docs

url: /it/java/com.aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

Sostituisce un elemento esistente nell'elenco con un nuovo elemento.

```java
public T ReplaceItem(T newItem, ulong index)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newItem | T | L'elemento da inserire nell'elenco. |
| index | UInt64 | L'indice dell'elemento da sostituire. Il primo elemento è il numero 0. |

### Valore di ritorno

L'elemento inserito.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Codice [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Generato quando la lista non può essere modificata. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Codice [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Generato se il numero dell'indice è maggiore o uguale a numberOfItems. |

### Vedi anche

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
