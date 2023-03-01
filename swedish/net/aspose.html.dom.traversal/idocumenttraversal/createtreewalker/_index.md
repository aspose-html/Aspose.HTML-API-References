---
title: IDocumentTraversal.CreateTreeWalker
second_title: Aspose.HTML för .NET API Referens
description: IDocumentTraversal metod. Skapa en ny TreeWalker över underträdet som är rotat vid den specificerade noden.
type: docs
weight: 20
url: /sv/net/aspose.html.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

Skapa en ny TreeWalker över underträdet som är rotat vid den specificerade noden.

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| root | Node | nod som kommer att fungera som roten för the TreeWalker. WhatToShow-flaggorna och NodeFilter beaktas inte när detta värde ställs in; någon nodtyp kommer att accepteras som rot. The currentNode för TreeWalker är initierad till denna nod, oavsett om den är synlig eller inte. Roten fungerar som en stopppunkt för traversal -metoder som ser uppåt i dokumentstrukturen, såsom parentNode och nextNode. Roten måste inte vara null. |

### Returvärde

Den nyskapade TreeWalker.

### Se även

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* namnutrymme [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* hopsättning [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Skapa en ny TreeWalker över underträdet som är rotat vid den specificerade noden.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| root | Node | nod som kommer att fungera som roten för the TreeWalker. WhatToShow-flaggorna och NodeFilter beaktas inte när detta värde ställs in; någon nodtyp kommer att accepteras som rot. The currentNode för TreeWalker är initierad till denna nod, oavsett om den är synlig eller inte. Roten fungerar som en stopppunkt för traversal -metoder som ser uppåt i dokumentstrukturen, såsom parentNode och nextNode. Roten måste inte vara null. |
| whatToShow | Int64 | flaggan anger vilka nodtyper som kan visas i den logiska vyn av trädet som presenteras av trädvandraren. Se beskrivningen av NodeFilter för uppsättningen av möjliga SHOW_-värden. Dessa flaggor kan kombineras med ELLER. |

### Returvärde

Den nyskapade TreeWalker.

### Se även

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* namnutrymme [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* hopsättning [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Skapa en ny TreeWalker över underträdet som är rotat vid den specificerade noden.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| root | Node | nod som kommer att fungera som roten för the TreeWalker. WhatToShow-flaggorna och NodeFilter beaktas inte när detta värde ställs in; någon nodtyp kommer att accepteras som rot. The currentNode för TreeWalker är initierad till denna nod, oavsett om den är synlig eller inte. Roten fungerar som en stopppunkt för traversal -metoder som ser uppåt i dokumentstrukturen, såsom parentNode och nextNode. Roten måste inte vara null. |
| whatToShow | Int64 | flaggan anger vilka nodtyper som kan visas i den logiska vyn av trädet som presenteras av trädvandraren. Se beskrivningen av NodeFilter för uppsättningen av möjliga SHOW_-värden. Dessa flaggor kan kombineras med ELLER. |
| filter | INodeFilter | NodeFilter som ska användas med this TreeWalker, eller null för att indikera inget filter. |

### Returvärde

Den nyskapade TreeWalker.

### Se även

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* namnutrymme [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* hopsättning [Aspose.HTML](../../../)


