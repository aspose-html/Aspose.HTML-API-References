---
title: "Node.RemoveChild"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo Node. Il metodo removeChild dell'interfaccia Node rimuove un nodo figlio dal DOM e restituisce il nodo rimosso"
type: docs

url: /it/java/com.aspose.html.dom/node/removechild/
---
## Node.RemoveChild method

Il metodo removeChild() dell'interfaccia Node rimuove un nodo figlio dal DOM e restituisce il nodo rimosso.

Nota: Finché viene mantenuto un riferimento al figlio rimosso, esso esiste ancora in memoria, ma non fa più parte del DOM. Può comunque essere riutilizzato più tardi nel codice. Se il valore di ritorno di removeChild() non viene memorizzato e non viene mantenuto alcun altro riferimento, verrà eliminato automaticamente dalla memoria dopo poco tempo.

```java
public Node RemoveChild(Node child)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| child | Node | Un [`Node`](../) che è il nodo figlio da rimuovere dal DOM. |

### Valore di ritorno

A differenza di [`Node.cloneNode()`](../clonenode/) il valore restituito conserva gli oggetti [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/) associati.

### Vedi anche

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
