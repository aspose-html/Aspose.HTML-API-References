---
title: "ITreeWalker.CurrentNode"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ITreeWalker-Eigenschaft. Der Knoten, an dem der TreeWalker derzeit positioniert ist. Änderungen am DOM-Baum können dazu führen, dass der aktuelle Knoten vom zugehörigen Filter des TreeWalkers nicht mehr akzeptiert wird. currentNode kann auch explizit auf jeden Knoten gesetzt werden, unabhängig davon, ob er sich innerhalb des vom Wurzelknoten angegebenen Teilbaums befindet oder vom Filter und den whatToShow‑Flags akzeptiert würde. Weitere Traversierungen erfolgen relativ zu currentNode, selbst wenn er nicht Teil der aktuellen Ansicht ist, indem die Filter in die gewünschte Richtung angewendet werden; ist keine Traversierung möglich, wird currentNode nicht geändert."
type: docs

url: /de/java/com.aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

Der Knoten, an dem der TreeWalker derzeit positioniert ist. Änderungen am DOM-Baum können dazu führen, dass der aktuelle Knoten vom zugehörigen Filter des TreeWalkers nicht mehr akzeptiert wird. currentNode kann auch explizit auf jeden Knoten gesetzt werden, unabhängig davon, ob er sich innerhalb des vom Wurzelknoten angegebenen Teilbaums befindet oder vom Filter und den whatToShow‑Flags akzeptiert würde. Weitere Traversierungen erfolgen relativ zu currentNode, selbst wenn er nicht Teil der aktuellen Ansicht ist, indem die Filter in die gewünschte Richtung angewendet werden; ist keine Traversierung möglich, wird currentNode nicht geändert.

```java
public Node CurrentNode { get; set; }
```

### Property Value

Der aktuelle Knoten.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Wird ausgelöst, wenn versucht wird, currentNode auf null zu setzen. |

### Siehe auch

* class [Node](../../../com.aspose.html.dom/node/)
* interface [ITreeWalker](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
