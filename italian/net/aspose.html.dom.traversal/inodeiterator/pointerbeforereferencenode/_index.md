---
title: INodeIterator.PointerBeforeReferenceNode
second_title: Aspose.HTML per riferimento API .NET
description: INodeIterator proprietà. Il valore di questo flag determina se i figli dei nodi di riferimento entity sono visibili alliteratore. Se false loro e i loro discendenti saranno respinti. Tieni presente che questo rifiuto ha la precedenza su whatToShow e sul filtro. Si noti inoltre che questa è attualmente lunica situazione in cui NodeIterator può rifiutare un sottoalbero completo piuttosto che saltare singoli nodi. Per produrre una vista del documento con i riferimenti dellentità espansi e non esporre il nodo di riferimento dellentità stesso utilizzare i flag whatToShow per nascondere il riferimento allentità node e impostare expandEntityReferences su true durante la creazione delliteratore . Per produrre una vista del documento che abbia i nodi di riferimento dellentità ma nessuna espansione dellentità usa whatToShow flags per mostrare il nodo del riferimento allentità e set expandEntityReferences su false.
type: docs
weight: 10
url: /it/net/aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

Il valore di questo flag determina se i figli dei nodi di riferimento entity sono visibili all'iteratore. Se false, loro e i loro discendenti saranno respinti. Tieni presente che questo rifiuto ha la precedenza su whatToShow e sul filtro. Si noti inoltre che questa è attualmente l'unica situazione in cui NodeIterator può rifiutare un sottoalbero completo piuttosto che saltare singoli nodi. Per produrre una vista del documento con i riferimenti dell'entità espansi e non esporre il nodo di riferimento dell'entità stesso, utilizzare i flag whatToShow per nascondere il riferimento all'entità node e impostare expandEntityReferences su true durante la creazione dell'iteratore . Per produrre una vista del documento che abbia i nodi di riferimento dell'entità ma nessuna espansione dell'entità, usa whatToShow flags per mostrare il nodo del riferimento all'entità e set expandEntityReferences su false.

```csharp
public bool PointerBeforeReferenceNode { get; }
```

### Valore della proprietà

`VERO`if [espandi riferimenti entità]; Altrimenti,`falso` .

### Guarda anche

* interface [INodeIterator](../)
* spazio dei nomi [Aspose.Html.Dom.Traversal](../../inodeiterator/)
* assemblea [Aspose.HTML](../../../)


