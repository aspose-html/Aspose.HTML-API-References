---
title: "Node.InsertBefore"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo Node. Il metodo insertBefore dell'interfaccia Node inserisce un nodo prima di un nodo di riferimento come figlio di un nodo genitore specificato"
type: docs

url: /it/java/com.aspose.html.dom/node/insertbefore/
---
## Node.InsertBefore method

Il metodo insertBefore() dell'interfaccia Node inserisce un nodo prima di un nodo di riferimento come figlio di un nodo genitore specificato.

Se il nodo fornito esiste già nel documento, insertBefore() lo sposta dalla sua posizione attuale alla nuova posizione. (In altre parole, verrà automaticamente rimosso dal suo genitore esistente prima di essere aggiunto al nuovo genitore specificato.)

Ciò significa che un nodo non può trovarsi in due posizioni del documento simultaneamente.

```java
public Node InsertBefore(Node node, Node child)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nodo | Node | Il nodo da inserire. |
| figlio | Node | Il nodo prima del quale viene inserito newNode. Se è null, newNode viene inserito alla fine dei nodi figli del nodo. |

### Valore di ritorno

Restituisce il figlio aggiunto (a meno che newNode non sia un [`DocumentFragment`](../../documentfragment/), nel qual caso viene restituito il [`DocumentFragment`](../../documentfragment/) vuoto).

### Vedi anche

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
