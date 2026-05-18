---
title: "ITraversal‑Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.traversal.ITraversal‑Schnittstelle. Iteratoren werden verwendet, um durch eine Menge von Knoten zu schritteln, z. B. die Menge der Knoten in einer NodeList, das Dokument-Teilbaum, das von einem bestimmten Knoten gesteuert wird, die Ergebnisse einer Abfrage oder jede andere Knotengruppe. Die zu iterierende Knotengruppe wird durch die Implementierung des NodeIterator bestimmt. DOM Level 2 definiert eine einzige NodeIterator‑Implementierung für die Traversierung eines Dokument‑Teilbaums in Dokumentenreihenfolge. Instanzen dieser Iteratoren werden durch Aufruf von DocumentTraversal.createNodeIterator erzeugt."
type: docs

url: /de/java/com.aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

Iteratoren werden verwendet, um durch eine Menge von Knoten zu gehen, z. B. die Menge von Knoten in einer NodeList, das Dokumentunterbaum, der von einem bestimmten Node gesteuert wird, die Ergebnisse einer Abfrage oder jede andere Knotenmengen. Die zu iterierende Knotenmengen wird durch die Implementierung des NodeIterator bestimmt. DOM Level 2 definiert eine einzelne NodeIterator‑Implementierung für die Dokumentreihenfolge‑Traversierung eines Dokumentunterbaums. Instanzen dieser Iteratoren werden durch Aufruf von DocumentTraversal .createNodeIterator().

Siehe auch die [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITraversal : IDisposable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getFilter](../../com.aspose.html.dom.traversal/itraversal/filter/) Der NodeFilter, der zum Filtern von Knoten verwendet wird. |
| [getRoot](../../com.aspose.html.dom.traversal/itraversal/root/) Der Wurzelknoten des NodeIterator, wie bei seiner Erstellung angegeben. |
| [getWhatToShow](../../com.aspose.html.dom.traversal/itraversal/whattoshow/) Dieses Attribut bestimmt, welche Knotentypen über den Iterator präsentiert werden. Der verfügbare Satz von Konstanten ist in der NodeFilter‑Schnittstelle definiert. Knoten, die von whatToShow nicht akzeptiert werden, werden übersprungen, aber ihre Kinder können weiterhin berücksichtigt werden. Beachten Sie, dass dieses Überspringen Vorrang vor dem Filter hat, falls vorhanden. |

### Siehe auch

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
