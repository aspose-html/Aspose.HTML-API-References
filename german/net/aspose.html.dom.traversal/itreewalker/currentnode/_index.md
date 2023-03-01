---
title: ITreeWalker.CurrentNode
second_title: Aspose.HTML für .NET-API-Referenz
description: ITreeWalker eigendom. Der Knoten an dem sich der TreeWalker derzeit befindet. Änderungen am DOMBaum können dazu führen dass der aktuelle Knoten nicht mehr vom zugehörigen Filter des TreeWalkers akzeptiert wird. currentNode kann auch explizit auf einen beliebigen Knoten gesetzt werden unabhängig davon ob dies der Fall ist oder nicht innerhalb des Unterbaums der durch den Stammknoten angegeben ist oder würde von den Flags filter and whatToShow akzeptiert werden. Eine weitere Traversierung erfolgt relativ zu aktuellem Knoten selbst wenn er nicht Teil der aktuellen Ansicht ist durch Anwenden der Filter in der angeforderten Richtung wenn kein Traversal möglich ist wird currentNode nicht geändert.
type: docs
weight: 10
url: /de/net/aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

Der Knoten, an dem sich der TreeWalker derzeit befindet. Änderungen am DOM-Baum können dazu führen, dass der aktuelle Knoten nicht mehr vom zugehörigen Filter des TreeWalkers akzeptiert wird. currentNode kann auch explizit auf einen beliebigen Knoten gesetzt werden, unabhängig davon, ob dies der Fall ist oder nicht innerhalb des Unterbaums, der durch den -Stammknoten angegeben ist, oder würde von den Flags filter and whatToShow akzeptiert werden. Eine weitere Traversierung erfolgt relativ zu aktuellem Knoten, selbst wenn er nicht Teil der aktuellen Ansicht ist, durch Anwenden der Filter in der angeforderten Richtung; wenn kein Traversal möglich ist, wird currentNode nicht geändert.

```csharp
public Node CurrentNode { get; set; }
```

### Eigentumswert

Der aktuelle Knoten.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Wird ausgelöst, wenn versucht wird, currentNode auf null zu setzen. |

### Siehe auch

* class [Node](../../../aspose.html.dom/node/)
* interface [ITreeWalker](../)
* namensraum [Aspose.Html.Dom.Traversal](../../itreewalker/)
* Montage [Aspose.HTML](../../../)


