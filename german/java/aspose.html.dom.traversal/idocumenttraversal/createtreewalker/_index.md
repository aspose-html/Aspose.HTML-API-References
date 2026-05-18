---
title: "IDocumentTraversal.CreateTreeWalker"
second_title: "Aspose.HTML für Java API-Referenz"
description: "IDocumentTraversal-Methode. Erstellt einen neuen TreeWalker über dem Teilbaum, der bei dem angegebenen Knoten verwurzelt ist."
type: docs

url: /de/java/com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

Erstellt einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten verwurzelt ist.

```java
public ITreeWalker CreateTreeWalker(Node root)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wurzel | Node | Knoten, der als Wurzel für den TreeWalker dient. Die whatToShow-Flags und der NodeFilter werden bei der Festlegung dieses Wertes nicht berücksichtigt; jeder Knotentyp wird als Wurzel akzeptiert. Der currentNode des TreeWalkers wird auf diesen Knoten initialisiert, unabhängig davon, ob er sichtbar ist oder nicht. Die Wurzel fungiert als Stoppunkt für Traversalmethoden, die im Dokumentenaufbau nach oben schauen, wie parentNode und nextNode. Die Wurzel darf nicht null sein. |

### Rückgabewert

Der neu erstellte TreeWalker.

### Siehe auch

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Erstellt einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten verwurzelt ist.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wurzel | Node | Knoten, der als Wurzel für den TreeWalker dient. Die whatToShow-Flags und der NodeFilter werden bei der Festlegung dieses Wertes nicht berücksichtigt; jeder Knotentyp wird als Wurzel akzeptiert. Der currentNode des TreeWalkers wird auf diesen Knoten initialisiert, unabhängig davon, ob er sichtbar ist oder nicht. Die Wurzel fungiert als Stoppunkt für Traversalmethoden, die im Dokumentenaufbau nach oben schauen, wie parentNode und nextNode. Die Wurzel darf nicht null sein. |
| whatToShow | Int64 | Das flag gibt an, welche Knotentypen in der logischen Ansicht des vom tree-walker präsentierten Baums erscheinen dürfen. Siehe die Beschreibung von NodeFilter für die Menge der möglichen SHOW_-Werte. Diese Flags können mit OR kombiniert werden. |

### Rückgabewert

Der neu erstellte TreeWalker.

### Siehe auch

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Erstellt einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten verwurzelt ist.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wurzel | Node | Knoten, der als Wurzel für den TreeWalker dient. Die whatToShow-Flags und der NodeFilter werden bei der Festlegung dieses Wertes nicht berücksichtigt; jeder Knotentyp wird als Wurzel akzeptiert. Der currentNode des TreeWalkers wird auf diesen Knoten initialisiert, unabhängig davon, ob er sichtbar ist oder nicht. Die Wurzel fungiert als Stoppunkt für Traversalmethoden, die im Dokumentenaufbau nach oben schauen, wie parentNode und nextNode. Die Wurzel darf nicht null sein. |
| whatToShow | Int64 | Das flag gibt an, welche Knotentypen in der logischen Ansicht des vom tree-walker präsentierten Baums erscheinen dürfen. Siehe die Beschreibung von NodeFilter für die Menge der möglichen SHOW_-Werte. Diese Flags können mit OR kombiniert werden. |
| Filter | INodeFilter | NodeFilter, der mit diesem TreeWalker verwendet werden soll, oder null, um keinen Filter anzugeben. |

### Rückgabewert

Der neu erstellte TreeWalker.

### Siehe auch

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
