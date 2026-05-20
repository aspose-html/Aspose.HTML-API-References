---
title: "IDocumentTraversal.CreateTreeWalker"
second_title: "Aspose.HTML för Java API-referens"
description: "IDocumentTraversal-metod. Skapa en ny TreeWalker över delträdet som har den angivna noden som rot."
type: docs

url: /sv/java/com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

Skapa en ny TreeWalker över delträdet som har den angivna noden som rot.

```java
public ITreeWalker CreateTreeWalker(Node root)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rot | Node | nod som kommer att fungera som rot för TreeWalker. whatToShow-flaggorna och NodeFilter beaktas inte när detta värde sätts; vilken nodtyp som helst accepteras som rot. TreeWalkers currentNode initieras till denna nod, oavsett om den är synlig eller inte. Roten fungerar som en stoppunkt för traverseringsmetoder som går uppåt i dokumentstrukturen, såsom parentNode och nextNode. Roten får inte vara null. |

### Returvärde

Den nyss skapade TreeWalker.

### Se även

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Skapa en ny TreeWalker över delträdet som har den angivna noden som rot.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rot | Node | nod som kommer att fungera som rot för TreeWalker. whatToShow-flaggorna och NodeFilter beaktas inte när detta värde sätts; vilken nodtyp som helst accepteras som rot. TreeWalkers currentNode initieras till denna nod, oavsett om den är synlig eller inte. Roten fungerar som en stoppunkt för traverseringsmetoder som går uppåt i dokumentstrukturen, såsom parentNode och nextNode. Roten får inte vara null. |
| whatToShow | Int64 | flag specificerar vilka nodtyper som kan visas i den logiska vyn av trädet som presenteras av tree-walkern. Se beskrivningen av NodeFilter för mängden möjliga SHOW_-värden. Dessa flaggor kan kombineras med OR. |

### Returvärde

Den nyss skapade TreeWalker.

### Se även

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Skapa en ny TreeWalker över delträdet som har den angivna noden som rot.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rot | Node | nod som kommer att fungera som rot för TreeWalker. whatToShow-flaggorna och NodeFilter beaktas inte när detta värde sätts; vilken nodtyp som helst accepteras som rot. TreeWalkers currentNode initieras till denna nod, oavsett om den är synlig eller inte. Roten fungerar som en stoppunkt för traverseringsmetoder som går uppåt i dokumentstrukturen, såsom parentNode och nextNode. Roten får inte vara null. |
| whatToShow | Int64 | flag specificerar vilka nodtyper som kan visas i den logiska vyn av trädet som presenteras av tree-walkern. Se beskrivningen av NodeFilter för mängden möjliga SHOW_-värden. Dessa flaggor kan kombineras med OR. |
| filter | INodeFilter | NodeFilter som ska användas med denna TreeWalker, eller null för att ange att inget filter används. |

### Returvärde

Den nyss skapade TreeWalker.

### Se även

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
