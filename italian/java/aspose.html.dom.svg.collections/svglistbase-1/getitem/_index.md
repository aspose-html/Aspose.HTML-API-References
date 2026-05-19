---
title: "SVGListBase-1.GetItem"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo SVGListBase. Restituisce l'elemento specificato dalla lista"
type: docs

url: /it/java/com.aspose.html.dom.svg.collections/svglistbase-1/getitem/
---
## SVGListBase&lt;T&gt;.GetItem method

Restituisce l'elemento specificato dall'elenco.

```java
public T GetItem(ulong index)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | UInt64 | L'indice dell'elemento della lista da restituire. Il primo elemento è il numero 0. |

### Valore di ritorno

L'elemento selezionato.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Codice [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Generato se il numero dell'indice è maggiore o uguale a numberOfItems. |

### Vedi anche

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
