---
title: "SVGListBase-1.InsertItemBefore"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo SVGListBase. Inserisce un nuovo elemento nella lista nella posizione specificata. Il primo elemento è il numero 0"
type: docs

url: /it/java/com.aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

Inserisce un nuovo elemento nell'elenco nella posizione specificata. Il primo elemento è il numero 0.

```java
public T InsertItemBefore(T newItem, ulong index)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newItem | T | L'elemento da inserire nell'elenco. |
| index | UInt64 | L'indice dell'elemento davanti al quale il nuovo elemento deve essere inserito. Il primo elemento è il numero 0. Se l'indice è uguale a 0, il nuovo elemento viene inserito all'inizio della lista. Se l'indice è maggiore o uguale a numberOfItems, il nuovo elemento viene aggiunto alla fine della lista. |

### Valore di ritorno

L'elemento inserito.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Codice [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Generato quando la lista non può essere modificata. |

### Vedi anche

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
