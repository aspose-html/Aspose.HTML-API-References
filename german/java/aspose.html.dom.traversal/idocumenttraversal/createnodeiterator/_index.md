---
title: "IDocumentTraversal.CreateNodeIterator"
second_title: "Aspose.HTML für Java API-Referenz"
description: "IDocumentTraversal-Methode. Erstellt einen neuen NodeIterator über dem Teilbaum, der bei dem angegebenen Knoten verwurzelt ist."
type: docs

url: /de/java/com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

Erstellt einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten verwurzelt ist.

```java
public INodeIterator CreateNodeIterator(Node root)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wurzel | Node | Knoten, der zusammen mit seinen Kindern iteriert wird. Der Iterator wird zunächst direkt vor diesem Knoten positioniert. Die whatToShow-Flags und der Filter, falls vorhanden, werden bei der Festlegung dieser Position nicht berücksichtigt. Die Wurzel darf nicht null sein. |

### Rückgabewert

Der neu erstellte NodeIterator.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Wird ausgelöst, wenn die angegebene Wurzel null ist. |

### Siehe auch

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

Erstellt einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten verwurzelt ist.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wurzel | Node | Knoten, der zusammen mit seinen Kindern iteriert wird. Der Iterator wird zunächst direkt vor diesem Knoten positioniert. Die whatToShow-Flags und der Filter, falls vorhanden, werden bei der Festlegung dieser Position nicht berücksichtigt. Die Wurzel darf nicht null sein. |
| whatToShow | Int64 | Flag gibt an, welche Knotentypen in der logischen Ansicht des vom Iterator präsentierten Baums erscheinen dürfen. Siehe die Beschreibung von NodeFilter für die Menge möglicher SHOW_-Werte. Diese Flags können mit OR kombiniert werden. |

### Rückgabewert

Der neu erstellte NodeIterator.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Wird ausgelöst, wenn die angegebene Wurzel null ist. |

### Siehe auch

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

Erstellt einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten verwurzelt ist.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wurzel | Node | Knoten, der zusammen mit seinen Kindern iteriert wird. Der Iterator wird zunächst direkt vor diesem Knoten positioniert. Die whatToShow-Flags und der Filter, falls vorhanden, werden bei der Festlegung dieser Position nicht berücksichtigt. Die Wurzel darf nicht null sein. |
| whatToShow | Int64 | Flag gibt an, welche Knotentypen in der logischen Ansicht des vom Iterator präsentierten Baums erscheinen dürfen. Siehe die Beschreibung von NodeFilter für die Menge möglicher SHOW_-Werte. Diese Flags können mit OR kombiniert werden. |
| Filter | INodeFilter | NodeFilter, der mit diesem TreeWalker verwendet werden soll, oder null, um keinen Filter anzugeben. |

### Rückgabewert

Der neu erstellte NodeIterator.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Wird ausgelöst, wenn die angegebene Wurzel null ist. |

### Siehe auch

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
