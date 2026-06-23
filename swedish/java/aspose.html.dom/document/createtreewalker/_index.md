---
title: "Document.CreateTreeWalker"
second_title: "Aspose.HTML för Java API-referens"
description: "Document‑metod. Skapar en ny TreeWalker över delträdet som är rotat vid den angivna noden."
type: docs

url: /sv/java/com.aspose.html.dom/document/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

Skapa en ny TreeWalker över delträdet som är rotat vid den angivna noden.

```java
public ITreeWalker CreateTreeWalker(Node root)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rot | Node | nod som kommer att fungera som rot för TreeWalker. whatToShow-flaggorna och NodeFilter beaktas inte när detta värde sätts; vilken nodtyp som helst accepteras som rot. TreeWalkers currentNode initieras till denna nod, oavsett om den är synlig eller inte. Roten fungerar som en stoppunkt för traverseringsmetoder som går uppåt i dokumentstrukturen, såsom parentNode och nextNode. Roten får inte vara null. |

### Returvärde

Den nyss skapade TreeWalker.

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Uppstår om den angivna roten är null. |

### Se även

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Skapa en ny TreeWalker över delträdet som är rotat vid den angivna noden.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rot | Node | nod som kommer att fungera som rot för TreeWalker. whatToShow-flaggorna och NodeFilter beaktas inte när detta värde sätts; vilken nodtyp som helst accepteras som rot. TreeWalkers currentNode initieras till denna nod, oavsett om den är synlig eller inte. Roten fungerar som en stoppunkt för traverseringsmetoder som går uppåt i dokumentstrukturen, såsom parentNode och nextNode. Roten får inte vara null. |
| whatToShow | Int64 | flag specificerar vilka nodtyper som kan visas i den logiska vyn av trädet som presenteras av tree-walkern. Se beskrivningen av NodeFilter för mängden möjliga SHOW_-värden. Dessa flaggor kan kombineras med OR. |

### Returvärde

Den nyss skapade TreeWalker.

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Uppstår om den angivna roten är null. |

### Se även

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Skapa en ny TreeWalker över delträdet som är rotat vid den angivna noden.

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

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Uppstår om den angivna roten är null. |

### Se även

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* interface [INodeFilter](../../../com.aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
