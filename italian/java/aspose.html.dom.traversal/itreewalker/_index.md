---
title: "Interfaccia ITreeWalker"
second_title: "Aspose.HTML per Java Riferimento API"
description: "interfaccia com.aspose.html.dom.traversal.ITreeWalker. Gli oggetti TreeWalker sono usati per navigare un albero o sottoalbero del documento utilizzando la vista del documento definita dalle loro flag whatToShow e dal filtro, se presente. Qualsiasi funzione che esegue la navigazione usando un TreeWalker supporterà automaticamente qualsiasi vista definita da un TreeWalker."
type: docs

url: /it/java/com.aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

Gli oggetti TreeWalker sono usati per navigare un albero o sottoalbero del documento utilizzando la vista del documento definita dalle loro flag whatToShow e dal filtro (se presente). Qualsiasi funzione che esegue la navigazione usando un TreeWalker supporterà automaticamente qualsiasi vista definita da un TreeWalker.

Omettere nodi dalla vista logica di un sottoalbero può produrre una struttura sostanzialmente diversa rispetto allo stesso sottoalbero nel documento completo e non filtrato. I nodi che sono fratelli nella vista TreeWalker possono essere figli di nodi diversi, ampiamente separati, nella vista originale. Per esempio, considera un NodeFilter che salta tutti i nodi tranne i nodi di testo e il nodo radice di un documento. Nella vista logica risultante, tutti i nodi di testo saranno fratelli e appariranno come figli diretti del nodo radice, indipendentemente da quanto sia annidata la struttura del documento originale.

Vedi anche il [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITreeWalker : ITraversal
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
[getCurrentNode]
[setCurrentNode] The node at which the TreeWalker is currently positioned. Alterations to the DOM tree may cause the current node to no longer be accepted by the TreeWalker's associated filter. currentNode may also be explicitly set to any node, whether or not it is within the subtree specified by the root node or would be accepted by the filter and whatToShow flags. Further traversal occurs relative to currentNode even if it is not part of the current view, by applying the filters in the requested direction; if no traversal is possible, currentNode is not changed. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [firstChild](../../com.aspose.html.dom.traversal/itreewalker/firstchild/)() | Sposta il TreeWalker sul primo figlio visibile del nodo corrente e restituisce il nuovo nodo. Se il nodo corrente non ha figli visibili, restituisce null e mantiene il nodo corrente. |
| [lastChild](../../com.aspose.html.dom.traversal/itreewalker/lastchild/)() | Sposta il TreeWalker sull'ultimo figlio visibile del nodo corrente e restituisce il nuovo nodo. Se il nodo corrente non ha figli visibili, restituisce null e mantiene il nodo corrente. |
| [nextNode](../../com.aspose.html.dom.traversal/itreewalker/nextnode/)() | Sposta il TreeWalker sul prossimo nodo visibile in ordine documentale rispetto al nodo corrente e restituisce il nuovo nodo. Se il nodo corrente non ha un nodo successivo, o se la ricerca di nextNode tenta di risalire dal nodo radice del TreeWalker, restituisce null e mantiene il nodo corrente. |
| [nextSibling](../../com.aspose.html.dom.traversal/itreewalker/nextsibling/)() | Sposta il TreeWalker sul fratello successivo del nodo corrente e restituisce il nuovo nodo. Se il nodo corrente non ha un fratello successivo visibile, restituisce null e mantiene il nodo corrente. |
| [parentNode](../../com.aspose.html.dom.traversal/itreewalker/parentnode/)() | Sposta e restituisce il nodo antenato visibile più vicino al nodo corrente. Se la ricerca di parentNode tenta di risalire dal nodo radice del TreeWalker, o se non riesce a trovare un nodo antenato visibile, questo metodo mantiene la posizione corrente e restituisce null. |
| [previousNode](../../com.aspose.html.dom.traversal/itreewalker/previousnode/)() | Sposta il TreeWalker al nodo visibile precedente nell'ordine del documento relativo al nodo corrente e restituisce il nuovo nodo. Se il nodo corrente non ha un nodo precedente, o se la ricerca di previousNode tenta di salire dal nodo radice del TreeWalker, restituisce null e mantiene il nodo corrente. |
| [previousSibling](../../com.aspose.html.dom.traversal/itreewalker/previoussibling/)() | Sposta il TreeWalker al fratello precedente del nodo corrente e restituisce il nuovo nodo. Se il nodo corrente non ha un fratello precedente visibile, restituisce null e mantiene il nodo corrente. |

### Vedi anche

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
