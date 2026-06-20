---
title: "Document.CreateNodeIterator"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Document Methode. Erstellt einen neuen NodeIterator über den Teilbaum, der an dem angegebenen Knoten verwurzelt ist."
type: docs

url: /de/java/com.aspose.html.dom/document/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

Erstelle einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten wurzelt.

```java
public INodeIterator CreateNodeIterator(Node root)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Root | Node | Knoten, der zusammen mit seinen Kindern iteriert wird. Der Iterator wird zunächst direkt vor diesem Knoten positioniert. Die whatToShow-Flags und der Filter, falls vorhanden, werden bei der Festlegung dieser Position nicht berücksichtigt. Die Wurzel darf nicht null sein. |

### Rückgabewert

Der neu erstellte NodeIterator.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Ausgelöst, wenn die angegebene Wurzel null ist. |

### Siehe auch

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

Erstelle einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten wurzelt.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Root | Node | Knoten, der zusammen mit seinen Kindern iteriert wird. Der Iterator wird zunächst direkt vor diesem Knoten positioniert. Die whatToShow-Flags und der Filter, falls vorhanden, werden bei der Festlegung dieser Position nicht berücksichtigt. Die Wurzel darf nicht null sein. |
| whatToShow | Int64 | Flag gibt an, welche Knotentypen in der logischen Ansicht des vom Iterator präsentierten Baums erscheinen dürfen. Siehe die Beschreibung von NodeFilter für die Menge möglicher SHOW_-Werte. Diese Flags können mit OR kombiniert werden. |

### Rückgabewert

Der neu erstellte NodeIterator.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Ausgelöst, wenn die angegebene Wurzel null ist. |

### Siehe auch

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

Erstelle einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten wurzelt.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Root | Node | Knoten, der zusammen mit seinen Kindern iteriert wird. Der Iterator wird zunächst direkt vor diesem Knoten positioniert. Die whatToShow-Flags und der Filter, falls vorhanden, werden bei der Festlegung dieser Position nicht berücksichtigt. Die Wurzel darf nicht null sein. |
| whatToShow | Int64 | Flag gibt an, welche Knotentypen in der logischen Ansicht des vom Iterator präsentierten Baums erscheinen dürfen. Siehe die Beschreibung von NodeFilter für die Menge möglicher SHOW_-Werte. Diese Flags können mit OR kombiniert werden. |
| Filter | INodeFilter | NodeFilter, der mit diesem TreeWalker verwendet werden soll, oder null, um keinen Filter anzuzeigen. |

### Rückgabewert

Der neu erstellte NodeIterator.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Ausgelöst, wenn die angegebene Wurzel null ist. |

### Siehe auch

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../com.aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
