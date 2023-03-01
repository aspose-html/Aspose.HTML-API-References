---
title: Interface ITreeWalker
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Traversal.ITreeWalker interfaccia. Gli oggetti TreeWalker vengono utilizzati per navigare in un albero del documento o in un sottoalbero utilizzando la vista del documento definita dai flag e filtri whatToShow se presenti. Qualsiasi funzione che esegue la navigazione utilizzando un TreeWalker supporterà automaticamente qualsiasi vista definita da un TreeWalker.
type: docs
weight: 2520
url: /it/net/aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

Gli oggetti TreeWalker vengono utilizzati per navigare in un albero del documento o in un sottoalbero utilizzando la vista del documento definita dai flag e filtri whatToShow (se presenti). Qualsiasi funzione che esegue la navigazione utilizzando un TreeWalker supporterà automaticamente qualsiasi vista definita da un TreeWalker.

L'omissione dei nodi dalla vista logica di un sottoalbero può comportare una struttura sostanzialmente diversa dallo stesso sottoalbero nel documento completo e non filtrato. I nodi che sono fratelli nella vista TreeWalker possono essere figli di nodi diversi, ampiamente separati nella vista originale. Ad esempio, considera un NodeFilter che ignora tutti i nodi ad eccezione dei nodi di testo e il nodo radice di un documento. Nella vista logica che ne risulta, tutti i nodi di testo saranno fratelli e appariranno come figli diretti del nodo radice, indipendentemente da quanto sia profondamente nidificata la struttura del documento originale.

Vedi anche il[Document object Model (DOM) Livello 2 Traversal e Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface ITreeWalker : ITraversal
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CurrentNode](../../aspose.html.dom.traversal/itreewalker/currentnode/) { get; set; } | Il nodo in cui il TreeWalker è attualmente posizionato. Le modifiche all'albero DOM possono far sì che il nodo corrente non sia più accettato dal filtro associato del TreeWalker. currentNode può anche essere impostato esplicitamente su qualsiasi nodo, indipendentemente dal fatto che lo sia o meno all'interno della sottostruttura specificata dal nodo radice o verrebbe accettato dal filtro e dai flag whatToShow. L'ulteriore attraversamento avviene rispetto a currentNode anche se non fa parte della vista corrente, applicando i filtri nella direzione richiesta; se nessun traversal è possibile, currentNode non viene modificato. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [FirstChild](../../aspose.html.dom.traversal/itreewalker/firstchild/)() | Sposta il TreeWalker al primo figlio visibile del nodo corrente e restituisce il nuovo nodo. Se il nodo corrente non ha figli visibili, restituisce null e conserva il nodo current . |
| [LastChild](../../aspose.html.dom.traversal/itreewalker/lastchild/)() | Sposta il TreeWalker sull'ultimo figlio visibile del nodo corrente e restituisce il nuovo nodo. Se il nodo corrente non ha figli visibili, restituisce null e conserva il nodo current . |
| [NextNode](../../aspose.html.dom.traversal/itreewalker/nextnode/)() | Sposta TreeWalker al successivo nodo visibile nell'ordine document relativo al nodo corrente e restituisce il nuovo nodo. Se il nodo corrente non ha un nodo successivo, o se la ricerca di nextNode tenta di salire dal nodo root di TreeWalker, restituisce null e mantiene il nodo corrente. |
| [NextSibling](../../aspose.html.dom.traversal/itreewalker/nextsibling/)() | Sposta il TreeWalker al fratello successivo del nodo current e restituisce il nuovo nodo. Se il nodo corrente non ha un fratello visibile successivo, restituisce null e conserva il nodo corrente. |
| [ParentNode](../../aspose.html.dom.traversal/itreewalker/parentnode/)() | Si sposta e restituisce il nodo antenato visibile più vicino del nodo current . Se la ricerca di parentNode tenta di avanzare verso l'alto dal nodo radice di TreeWalker, o se non riesce a trovare un nodo antenato visibile, questo metodo mantiene la posizione corrente e restituisce null. |
| [PreviousNode](../../aspose.html.dom.traversal/itreewalker/previousnode/)() | Sposta il TreeWalker al precedente nodo visibile nell'ordine del documento rispetto al nodo corrente e restituisce il nuovo nodo. Se il nodo corrente non ha un nodo precedente o se la ricerca di previousNode tenta di risalire dal nodo radice di TreeWalker, restituisce null e mantiene il nodo corrente. |
| [PreviousSibling](../../aspose.html.dom.traversal/itreewalker/previoussibling/)() | Sposta il TreeWalker al fratello precedente del nodo corrente e restituisce il nuovo nodo. Se il nodo corrente non ha alcun di pari livello precedente visibile, restituisce null e conserva il nodo corrente. |

### Guarda anche

* interface [ITraversal](../itraversal/)
* spazio dei nomi [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* assemblea [Aspose.HTML](../../)


