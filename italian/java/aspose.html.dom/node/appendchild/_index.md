---
title: "Node.AppendChild"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo Node. Il metodo appendChild dell'interfaccia Node aggiunge un nodo alla fine dell'elenco dei figli di un nodo genitore specificato. Se il figlio fornito è un riferimento a un nodo esistente nel documento, appendChild lo sposta dalla sua posizione attuale a quella nuova; non è necessario rimuovere il nodo dal suo genitore prima di aggiungerlo a un altro nodo."
type: docs

url: /it/java/com.aspose.html.dom/node/appendchild/
---
## Node.AppendChild method

Il metodo appendChild() dell'interfaccia Node aggiunge un nodo alla fine dell'elenco dei figli di un nodo genitore specificato. Se il figlio fornito è un riferimento a un nodo esistente nel documento, appendChild() lo sposta dalla sua posizione attuale alla nuova posizione (non è necessario rimuovere il nodo dal suo nodo genitore prima di aggiungerlo a un altro nodo).

Ciò significa che un nodo non può trovarsi in due punti del documento contemporaneamente. Quindi, se il nodo ha già un genitore, il nodo viene prima rimosso, poi aggiunto nella nuova posizione. Il metodo [`Node.cloneNode()`](../clonenode/) può essere usato per creare una copia del nodo prima di aggiungerlo al nuovo genitore. Le copie create con [`cloneNode`](../clonenode/) non vengono sincronizzate automaticamente.

```java
public Node AppendChild(Node node)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nodo | Node | Il nodo da aggiungere al genitore specificato (di solito un elemento). |

### Valore di ritorno

Un Node che è il figlio aggiunto (aChild), eccetto quando aChild è un [`DocumentFragment`](../../documentfragment/), nel qual caso viene restituito il [`DocumentFragment`](../../documentfragment/) vuoto.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../domexception/) | Generato quando le restrizioni dell'albero DOM vengono violate. |

### Vedi anche

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
