---
title: "INodeFilter‑Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.traversal.INodeFilter‑Schnittstelle. Filter sind Objekte, die wissen, wie man Knoten herausfiltert. Wenn einem NodeIterator oder TreeWalker ein NodeFilter übergeben wird, wendet er den Filter an, bevor er den nächsten Knoten zurückgibt. Wenn der Filter den Knoten akzeptiert, gibt die Traversallogik ihn zurück, andernfalls sucht die Traversal nach dem nächsten Knoten und tut so, als wäre der abgelehnte Knoten nicht vorhanden."
type: docs

url: /de/java/com.aspose.html.dom.traversal/inodefilter/
---
## INodeFilter interface

Filter sind Objekte, die wissen, wie man Knoten „herausfiltert“. Wenn einem NodeIterator oder TreeWalker ein NodeFilter übergeben wird, wendet er den Filter an, bevor er den nächsten Knoten zurückgibt. Wenn der Filter den Knoten akzeptiert, gibt die Traversal‑Logik ihn zurück; andernfalls sucht die Traversal‑Logik nach dem nächsten Knoten und tut so, als wäre der abgelehnte Knoten nicht vorhanden.

Das DOM stellt keine Filter bereit. NodeFilter ist lediglich eine Schnittstelle, die Benutzer implementieren können, um eigene Filter bereitzustellen.

NodeFilters müssen nicht wissen, wie man von Knoten zu Knoten traversiert, und sie müssen nichts über die Datenstruktur wissen, die traversiert wird. Das macht das Schreiben von Filtern sehr einfach, da sie nur wissen müssen, wie ein einzelner Knoten zu evaluieren ist. Ein Filter kann mit verschiedenen Arten von Traversals verwendet werden, was die Wiederverwendung von Code fördert.

Siehe auch die [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface INodeFilter
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [acceptNode](../../com.aspose.html.dom.traversal/inodefilter/acceptnode/)(Node) | Prüft, ob ein bestimmter Knoten in der logischen Ansicht eines TreeWalker oder NodeIterator sichtbar ist. Diese Funktion wird von der Implementierung von TreeWalker und NodeIterator aufgerufen; sie wird normalerweise nicht direkt aus dem Benutzercode heraus aufgerufen. (Obwohl Sie dies tun könnten, wenn Sie denselben Filter verwenden möchten, um Ihre eigene Anwendungslogik zu steuern.) |

### Siehe auch

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
