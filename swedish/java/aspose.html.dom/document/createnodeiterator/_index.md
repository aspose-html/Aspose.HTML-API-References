---
title: "Document.CreateNodeIterator"
second_title: "Aspose.HTML för Java API-referens"
description: "Document‑metod. Skapa en ny NodeIterator över delträdet med den angivna noden som rot"
type: docs

url: /sv/java/com.aspose.html.dom/document/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

Skapa en ny NodeIterator över delträdet som har den angivna noden som rot.

```java
public INodeIterator CreateNodeIterator(Node root)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rot | Node | nod som kommer att itereras tillsammans med sina barn. Iteratorn är initialt placerad precis före denna nod. whatToShow-flaggorna och filtret, om något, beaktas inte när denna position sätts. Roten får inte vara null. |

### Returvärde

Den nyss skapade NodeIterator.

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Uppstår om den angivna roten är null. |

### Se även

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

Skapa en ny NodeIterator över delträdet som har den angivna noden som rot.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rot | Node | nod som kommer att itereras tillsammans med sina barn. Iteratorn är initialt placerad precis före denna nod. whatToShow-flaggorna och filtret, om något, beaktas inte när denna position sätts. Roten får inte vara null. |
| whatToShow | Int64 | flaggan anger vilka nodtyper som kan visas i iteratorns logiska trädvy. Se beskrivningen av NodeFilter för de möjliga SHOW_-värdena. Dessa flaggor kan kombineras med OR. |

### Returvärde

Den nyss skapade NodeIterator.

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Uppstår om den angivna roten är null. |

### Se även

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

Skapa en ny NodeIterator över delträdet som har den angivna noden som rot.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rot | Node | nod som kommer att itereras tillsammans med sina barn. Iteratorn är initialt placerad precis före denna nod. whatToShow-flaggorna och filtret, om något, beaktas inte när denna position sätts. Roten får inte vara null. |
| whatToShow | Int64 | flaggan anger vilka nodtyper som kan visas i iteratorns logiska trädvy. Se beskrivningen av NodeFilter för de möjliga SHOW_-värdena. Dessa flaggor kan kombineras med OR. |
| filter | INodeFilter | NodeFilter som ska användas med denna TreeWalker, eller null för att ange att inget filter används. |

### Returvärde

Den nyss skapade NodeIterator.

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Uppstår om den angivna roten är null. |

### Se även

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../com.aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
