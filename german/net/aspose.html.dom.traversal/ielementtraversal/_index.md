---
title: Interface IElementTraversal
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Dom.Traversal.IElementTraversal koppel. Die ElementTraversalSchnittstelle ist ein Satz von schreibgeschützten Attributen die es einem Autor ermöglichen einfach zwischen Elementen in einem Dokument zu navigieren. In konformen Implementierungen von Element Traversal müssen alle Objekte die Element implementieren auch die ElementTraversalSchnittstelle implementieren.
type: docs
weight: 2480
url: /de/net/aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

Die ElementTraversal-Schnittstelle ist ein Satz von schreibgeschützten Attributen, die es einem Autor ermöglichen, einfach zwischen Elementen in einem Dokument zu navigieren. In konformen Implementierungen von Element Traversal müssen alle Objekte, die Element implementieren, auch die ElementTraversal-Schnittstelle implementieren.

```csharp
public interface IElementTraversal
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ChildElementCount](../../aspose.html.dom.traversal/ielementtraversal/childelementcount/) { get; } | Gibt die aktuelle Anzahl der Elementknoten zurück, die Kinder dieses Elements sind. 0, wenn dieses Element keine untergeordneten Knoten hat, die vom nodeType 1. sind |
| [FirstElementChild](../../aspose.html.dom.traversal/ielementtraversal/firstelementchild/) { get; } | Gibt den ersten untergeordneten Elementknoten dieses Elements zurück. null, wenn dieses Element keine untergeordneten Elemente hat. |
| [LastElementChild](../../aspose.html.dom.traversal/ielementtraversal/lastelementchild/) { get; } | Gibt den letzten untergeordneten Elementknoten dieses Elements zurück. null, wenn dieses Element keine untergeordneten Elemente hat. |
| [NextElementSibling](../../aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) { get; } | Gibt den nächsten gleichgeordneten Elementknoten dieses Elements zurück. null, wenn dieses Element keine untergeordneten Elementknoten hat, die im Dokumentbaum nach diesem Knoten kommen. |
| [PreviousElementSibling](../../aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) { get; } | Gibt den vorherigen gleichgeordneten Elementknoten dieses Elements zurück. null, wenn dieses Element keine Element-Geschwisterknoten hat, die vor diesem im Dokumentbaum stehen. |

### Siehe auch

* namensraum [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* Montage [Aspose.HTML](../../)


