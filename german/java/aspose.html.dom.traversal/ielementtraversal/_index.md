---
title: "IElementTraversal Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.traversal.IElementTraversal‑Schnittstelle. Das ElementTraversal‑Interface ist ein Satz von schreibgeschützten Attributen, die es einem Autor ermöglichen, einfach zwischen Elementen in einem Dokument zu navigieren. In konformen Implementierungen von Element Traversal müssen alle Objekte, die Element implementieren, ebenfalls das ElementTraversal‑Interface implementieren."
type: docs

url: /de/java/com.aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

Das ElementTraversal-Interface ist ein Satz von schreibgeschützten Attributen, die es einem Autor ermöglichen, einfach zwischen Elementen in einem Dokument zu navigieren. In konformen Implementierungen von Element Traversal müssen alle Objekte, die Element implementieren, ebenfalls das ElementTraversal-Interface implementieren.

```java
public interface IElementTraversal
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getChildElementCount](../../com.aspose.html.dom.traversal/ielementtraversal/childelementcount/) Gibt die aktuelle Anzahl von Elementknoten zurück, die Kinder dieses Elements sind. 0, wenn dieses Element keine Kindknoten vom Typ nodeType 1 hat. |
| [getFirstElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/firstelementchild/) Gibt den ersten Kind-Elementknoten dieses Elements zurück. null, wenn dieses Element keine Kind-Elemente hat. |
| [getLastElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/lastelementchild/) Gibt den letzten Kind-Elementknoten dieses Elements zurück. null, wenn dieses Element keine Kind-Elemente hat. |
| [getNextElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) Gibt den nächsten Geschwister‑Elementknoten dieses Elements zurück. null, wenn dieses Element keine nachfolgenden Element‑Geschwisterknoten im Dokumentbaum hat. |
| [getPreviousElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) Gibt den vorherigen Geschwister‑Elementknoten dieses Elements zurück. null, wenn dieses Element keine vorherigen Element‑Geschwisterknoten im Dokumentbaum hat. |

### Siehe auch

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
