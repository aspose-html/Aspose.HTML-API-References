---
title: "INodeIterator.PointerBeforeReferenceNode"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Proprietà INodeIterator. Il valore di questo flag determina se i figli dei nodi di riferimento entità sono visibili all'iteratore. Se false, essi e i loro discendenti saranno rifiutati. Nota che questo rifiuto ha precedenza su whatToShow e sul filtro. Inoltre, nota che attualmente è l'unica situazione in cui i NodeIterators possono rifiutare un intero sottoalbero anziché saltare nodi individuali. Per produrre una vista del documento con i riferimenti entità espansi e che non espone il nodo di riferimento entità stesso, usa i flag whatToShow per nascondere il nodo di riferimento entità e imposta expandEntityReferences su true quando crei l'iteratore. Per produrre una vista del documento con nodi di riferimento entità ma senza espansione dell'entità, usa i flag whatToShow per mostrare il nodo di riferimento entità e imposta expandEntityReferences su false."
type: docs

url: /it/java/com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

Il valore di questo flag determina se i figli dei nodi di riferimento entità sono visibili all'iteratore. Se false, essi e i loro discendenti saranno rifiutati. Nota che questo rifiuto ha precedenza su whatToShow e sul filtro. Inoltre, nota che attualmente è l'unica situazione in cui i NodeIterators possono rifiutare un intero sottoalbero anziché saltare nodi individuali. Per produrre una vista del documento con i riferimenti entità espansi e che non espone il nodo di riferimento entità stesso, usa i flag whatToShow per nascondere il nodo di riferimento entità e imposta expandEntityReferences su true quando crei l'iteratore. Per produrre una vista del documento con nodi di riferimento entità ma senza espansione dell'entità, usa i flag whatToShow per mostrare il nodo di riferimento entità e imposta expandEntityReferences su false.

```java
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true` se [expand entity references]; altrimenti, `false`.

### Vedi anche

* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
