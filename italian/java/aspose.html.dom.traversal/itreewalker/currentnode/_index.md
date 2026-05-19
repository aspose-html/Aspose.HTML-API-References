---
title: "ITreeWalker.CurrentNode"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Proprietà ITreeWalker. Il nodo su cui il TreeWalker è attualmente posizionato. Modifiche all'albero DOM possono far sì che il nodo corrente non sia più accettato dal filtro associato al TreeWalker. currentNode può anche essere impostato esplicitamente su qualsiasi nodo, indipendentemente dal fatto che sia all'interno del sottoalbero specificato dal nodo radice o che sarebbe accettato dal filtro e dalle flag whatToShow. Ulteriori traversate avvengono rispetto a currentNode anche se non fa parte della vista corrente, applicando i filtri nella direzione richiesta; se non è possibile alcuna traversata, currentNode non viene modificato."
type: docs

url: /it/java/com.aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

Il nodo su cui il TreeWalker è attualmente posizionato. Modifiche all'albero DOM possono far sì che il nodo corrente non sia più accettato dal filtro associato al TreeWalker. currentNode può anche essere impostato esplicitamente su qualsiasi nodo, indipendentemente dal fatto che sia all'interno del sottoalbero specificato dal nodo radice o che sarebbe accettato dal filtro e dalle flag whatToShow. Ulteriori traversate avvengono rispetto a currentNode anche se non fa parte della vista corrente, applicando i filtri nella direzione richiesta; se non è possibile alcuna traversata, currentNode non viene modificato.

```java
public Node CurrentNode { get; set; }
```

### Property Value

Il nodo corrente.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Generato se si tenta di impostare currentNode a null. |

### Vedi anche

* class [Node](../../../com.aspose.html.dom/node/)
* interface [ITreeWalker](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
