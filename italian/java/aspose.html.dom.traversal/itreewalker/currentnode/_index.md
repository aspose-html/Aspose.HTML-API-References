---
title: "ITreeWalker.CurrentNode"
second_title: "Aspose.HTML per Java Riferimento API"
description: "ITreeWalker proprietà. Il nodo al quale il TreeWalker è attualmente posizionato. Modifiche all'albero DOM possono far sì che il nodo corrente non sia più accettato dal filtro associato al TreeWalker. currentNode può anche essere impostato esplicitamente su qualsiasi nodo, indipendentemente dal fatto che sia all'interno del sottoalbero specificato dal nodo radice o che sarebbe accettato dal filtro e dalle flag whatToShow. Ulteriori traversamenti avvengono rispetto a currentNode anche se non fa parte della vista corrente, applicando i filtri nella direzione richiesta; se non è possibile alcun attraversamento, currentNode non viene modificato."
type: docs

url: /it/java/com.aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

Il nodo al quale il TreeWalker è attualmente posizionato. Le modifiche all'albero DOM possono far sì che il nodo corrente non sia più accettato dal filtro associato al TreeWalker. currentNode può anche essere impostato esplicitamente su qualsiasi nodo, sia esso all'interno del sottoalbero specificato dal nodo radice o meno, o sarebbe accettato dal filtro e dalle flag whatToShow. Ulteriori traversamenti avvengono rispetto a currentNode anche se non fa parte della vista corrente, applicando i filtri nella direzione richiesta; se non è possibile alcun attraversamento, currentNode non viene modificato.

```java
public Node CurrentNode { get; set; }
```

### Property Value

Il nodo corrente.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Sollevato se si tenta di impostare currentNode a null. |

### Vedi anche

* class [Node](../../../com.aspose.html.dom/node/)
* interface [ITreeWalker](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
