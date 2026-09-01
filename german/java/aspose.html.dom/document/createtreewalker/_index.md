---
title: "Document.CreateTreeWalker"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Document-Methode. Erstellt einen neuen TreeWalker über den Teilbaum, der bei dem angegebenen Knoten wurzelt."
type: docs

url: /de/java/com.aspose.html.dom/document/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

Erstelle einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten wurzelt.

```java
public ITreeWalker CreateTreeWalker(Node root)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Root | Node | Knoten, der als Wurzel für den TreeWalker dient. Die whatToShow-Flags und der NodeFilter werden bei der Festlegung dieses Wertes nicht berücksichtigt; jeder Knotentyp wird als Wurzel akzeptiert. Der currentNode des TreeWalkers wird auf diesen Knoten initialisiert, unabhängig davon, ob er sichtbar ist oder nicht. Die Wurzel fungiert als Stoppunkt für Traversalmethoden, die im Dokumentenstruktur nach oben schauen, wie parentNode und nextNode. Die Wurzel darf nicht null sein. |

### Rückgabewert

Der neu erstellte TreeWalker.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Ausgelöst, wenn die angegebene Wurzel null ist. |

### Siehe auch

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Erstelle einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten wurzelt.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Root | Node | Knoten, der als Wurzel für den TreeWalker dient. Die whatToShow-Flags und der NodeFilter werden bei der Festlegung dieses Wertes nicht berücksichtigt; jeder Knotentyp wird als Wurzel akzeptiert. Der currentNode des TreeWalkers wird auf diesen Knoten initialisiert, unabhängig davon, ob er sichtbar ist oder nicht. Die Wurzel fungiert als Stoppunkt für Traversalmethoden, die im Dokumentenstruktur nach oben schauen, wie parentNode und nextNode. Die Wurzel darf nicht null sein. |
| whatToShow | Int64 | Flag gibt an, welche Knotentypen in der logischen Ansicht des vom tree-walker präsentierten Baums erscheinen dürfen. Siehe die Beschreibung von NodeFilter für die Menge möglicher SHOW_-Werte. Diese Flags können mit OR kombiniert werden. |

### Rückgabewert

Der neu erstellte TreeWalker.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Ausgelöst, wenn die angegebene Wurzel null ist. |

### Siehe auch

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Erstelle einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten wurzelt.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Root | Node | Knoten, der als Wurzel für den TreeWalker dient. Die whatToShow-Flags und der NodeFilter werden bei der Festlegung dieses Wertes nicht berücksichtigt; jeder Knotentyp wird als Wurzel akzeptiert. Der currentNode des TreeWalkers wird auf diesen Knoten initialisiert, unabhängig davon, ob er sichtbar ist oder nicht. Die Wurzel fungiert als Stoppunkt für Traversalmethoden, die im Dokumentenstruktur nach oben schauen, wie parentNode und nextNode. Die Wurzel darf nicht null sein. |
| whatToShow | Int64 | Flag gibt an, welche Knotentypen in der logischen Ansicht des vom tree-walker präsentierten Baums erscheinen dürfen. Siehe die Beschreibung von NodeFilter für die Menge möglicher SHOW_-Werte. Diese Flags können mit OR kombiniert werden. |
| Filter | INodeFilter | NodeFilter, der mit diesem TreeWalker verwendet werden soll, oder null, um keinen Filter anzuzeigen. |

### Rückgabewert

Der neu erstellte TreeWalker.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Ausgelöst, wenn die angegebene Wurzel null ist. |

### Siehe auch

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* interface [INodeFilter](../../../com.aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
