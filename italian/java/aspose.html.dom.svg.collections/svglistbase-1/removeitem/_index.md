---
title: "SVGListBase-1.RemoveItem"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo SVGListBase. Rimuove un elemento esistente dalla lista"
type: docs

url: /it/java/com.aspose.html.dom.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase&lt;T&gt;.RemoveItem method

Rimuove un elemento esistente dall'elenco.

```java
public T RemoveItem(ulong index)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | UInt64 | L'indice dell'elemento da rimuovere. Il primo elemento è il numero 0. |

### Valore di ritorno

L'elemento rimosso.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Codice [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Generato quando l'elenco non può essere modificato. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Codice [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Generato se il numero dell'indice è maggiore o uguale a numberOfItems. |

### Vedi anche

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
